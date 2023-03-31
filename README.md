# Credit Risk Analysis

This repository contains code for analyzing credit risk using machine learning models. The analysis includes the following steps:

## Data Splitting

1. The `lending_data.csv` data file from the Resources folder is read into a Pandas DataFrame using `pandas.read_csv()`.
2. The `loan_status` column is used to create the labels set (y), and the remaining columns are used to create the features DataFrame (X).
3. The data is split into training and testing datasets using the `train_test_split` function from scikit-learn.

## Logistic Regression Model

1. A logistic regression model is fit using the training data (X_train and y_train).
2. The model's predictions are saved using the testing feature data (X_test) and the fitted model.
3. The model's performance is evaluated using a confusion matrix and a classification report.
4. The question "How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?" is answered.

## Credit Risk Analysis Report

1. An overview that explains the purpose of the analysis is provided.
2. The accuracy, precision, and recall scores of the machine learning model are described using a bulleted list.
3. The results from the machine learning model are summarized, and a justification is provided for recommending or not recommending the model for use by the company.

## Coding Conventions and Formatting

1. Imports are placed at the top of the file, just after any module comments and docstrings and before module globals and constants.
2. Functions and variables are named with lowercase characters, with words separated by underscores.
3. DRY (Don’t Repeat Yourself) principles are followed, creating maintainable and reusable code.
4. Concise logic and creative engineering are used where possible.
