# Naive_Bayes_Spam_Email_Detection

## Introduction
This Jupyter Notebook presents an email spam classifier using the Naive Bayes supervised machine learning algorithm. The primary goal of this project is to demonstrate the implementation of the Naive Bayes algorithm in classifying emails as spam or non-spam.

## Features
- Implementation of Naive Bayes algorithm.
- Analysis of email data for spam detection.
- Usage of Python libraries such as NumPy, Pandas, and scikit-learn.

## Installation and Setup
To run this notebook:
1. Ensure that Python is installed on your system.
2. Install necessary Python libraries: NumPy, Pandas, scikit-learn. This can be done via pip:
   ```
   pip install numpy pandas scikit-learn
   ```
3. Clone this repository or download the Jupyter Notebook.
4. Ensure the data folders 'train-mails' and 'test-mails' are placed in the same directory as the notebook. The paths should be './train-mails' and './test-mails'.

## Data
The dataset consists of two folders:
1. `train-mails`: This folder contains the training set of emails.
2. `test-mails`: This folder contains the test set of emails.

Each email is stored as a separate file in these folders. The dataset should be structured such that these folders are in the same directory as the Jupyter Notebook to maintain the relative paths.

## Usage
To use this notebook:
1. Open the notebook in Jupyter Lab or Jupyter Notebook.
2. Run the cells in order to train the Naive Bayes model and evaluate its performance on the test data.
3. The notebook includes markdown texts and code comments explaining each part of the code for better understanding.

## Code Structure
1. Import necessary libraries (os, numpy, pandas, scikit-learn).
2. Load and preprocess the email data.
3. Train the Naive Bayes model using the training data.
4. Evaluate the model's performance with the test data.

## Contribution Guidelines
If you'd like to contribute to this project:
1. Fork the repository.
2. Create a new branch for your feature.
3. Add your changes and commit them.
4. Push to your branch and open a pull request.

## Important Note
The dataset paths must be './train-mails' and './test-mails'. This ensures compatibility for peer reviews and testing across different systems.
