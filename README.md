# credit-risk-classification

## Overview and Analysis

In this challenge, the purpose was to use various techniques to train and evaluate a model based on loan risk. We used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. 

The dataset included the following values:

- loan size
- interest rate
- borrower income
- debt to income ratio
- number of accounts
- derogatory remarks
- total debt

Based on this information, we wanted to use a Logistic Regression model to identify if the loans are low-risk, or high-risk, and we also wanted to know how accurate and reliable this model can be.

The first step was to separate the value we want to predict from the features (other columns in dataset). After doing this, it was necessary to separate the dataset into training data and testing data. This is a crucial step in Machine Learning, because we want to train our model on a specific data, and then test it on a different one. This ensures reliability. After training and testing the data, we generated the confusion matrix and printed the classification report, which will help us understand if the model is accurate and reliable. 

## Results

The results for the Logistic Regression model were as follows:

- Balanced Accuracy: 94.5%
- Precision:
    - Low-Risk Loans: 100%
    - High-Risk Loans: 86%
- Recall:
    - Low-Risk Loans: 100%
    - High-Risk Loans: 89%


## Summary

The results of the Logistic Regression model for predicting loan-risk are quite promising. With a balanced accuracy of 94.5%, the model demonstrates strong overall performance distinguishing between low-risk loans and high-risk loans. Moreover, the precision and recall scores for both low-risk and high-risk loans are quite high, indicating that the model is effective in identifying both classes. Specifically, the model achieves perfect precision fow low-risk loans, meaning that all of the predicted low-risk loans are actually low-risk. Additionally, it achieves a commendable precision of 86% high-risk loans, indicating that the majority of loans predicted as high-risk are indeed high-risk. Similarly, the recall scores show that the model effectively captures the majority of true low-risk and high-risk loans. Based on these results, the logistic regression model appears to be reliable and accurate for identifying loan risk. 