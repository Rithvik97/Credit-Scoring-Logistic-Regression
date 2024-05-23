# Credit-Scoring-Logistic-Regression

This repository contains the implementation of a credit scoring model using Logistic Regression. The goal of the project is to predict the creditworthiness of individuals based on their financial history and other related features.

## Project Overview
This project involves building a credit scoring model using logistic regression. The dataset used in this project contains various features related to an individual's financial history, and the target variable indicates their creditworthiness.

## Data Description
The dataset consists of 3000 rows and 30 columns, with features such as:
- `DerogCnt`: Number of derogatory reports
- `CollectCnt`: Number of collection accounts
- `BankruptcyInd`: Bankruptcy indicator
- `InqCnt06`: Number of inquiries in the last 6 months
- `TARGET`: The target variable indicating creditworthiness (1: Good, 0: Bad)

### Handling Missing Values
Missing values were filled with the mean of the respective columns.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

### Accuracy Score
The model achieved an accuracy of 83.33%.

          precision    recall  f1-score   support

       0       0.85      0.97      0.91       500
       1       0.50      0.13      0.21       100

accuracy                           0.83       600

