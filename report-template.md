# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to biuld and evaluate a machine learning model to predict loan status based on financial data. We analyzed wheter a Logistic Regression model could predict loan risk based on financial factoras such as interest rate, loan size, debt to income, number of accounts, total debt, etc. The dataset contained financial information derived from pior credit reports and public loan data

In this ananlysis, what was made was:
 - Split the data into training and testing sets.
 - Trained a Logistic Regression model to predict loan status.
- Evaluated the model using a confusion matrix and a classification report to assess accuracy, precision, and recall.
## Results

Logistic Regression Model
Accuracy: 99%
Precision: 
    - Class 0 (Fully Paid): 100%
    - Class 1 (Charged Off): 87%
Recall:
    - Class 0: 100%
    - Class 1: 95%

Confusion Matrix:
    - TP: 593
    - TN: 18673
    - FP: 86
    - FN: 32
## Summary

The logistic regression model perfomed exceptionally well with a 99% accuracy and high precision and recall scores.

Since only one model was tested, logistic regression is the recommended choice for this problem
The model is particulary good at identifying loans that will be fully paid

If the goal is to minimize risk, this model is effective beacuase it captures most charged-off loans