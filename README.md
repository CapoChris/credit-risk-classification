# Read Me Report

## Overview of the Analysis

In this analysis, I developed a machine learning model to assess credit risk using a dataset of loan applications. The objective was to predict whether a loan was high risk (1 in the loan_status column) or healthy (0) based on borrower financial attributes.

Key variables included:

  - Borrower income
  - Interest rate
  - Loan amount
  - Debt-to-income ratio
  - Number of open accounts
  - Presence of derogatory marks
  - Total debt

The process involved:

  - Splitting the data into training and testing sets
  - Training a Logistic Regression model
  - Evaluating performance using a confusion matrix and classification report

This model aimed to determine how accurately these financial indicators could be used to classify loan risk.

## Results

The model demonstrates exceptional accuracy in identifying healthy loans, correctly classifying nearly all of the approximately 19,000 instances, achieving an accuracy rate of 99.9%. While its performance in detecting high-risk loans is slightly lower, it remains robust with an accuracy of around 94%.

## Summary

I would recommend using this model due to its exceptionally high overall accuracy. However, it is important to note that the model misclassifies high-risk loans as healthy approximately 15% of the time, which could present some risk.
