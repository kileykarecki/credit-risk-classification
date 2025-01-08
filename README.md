# credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge.

Purpose of the analysis.
The analysis aims to help decide if a loan should be approved or not, it is trying to asses if a borrower is likely to pay back the loan or not.

Financial information the data was on, and what needed to be predicted
The lending data included, regarding the loan: the amount, interest rate and status, and regarding the borrower: income, debt to income ratio, number of accounts, derogatory marks on their record and total debt amount.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Looking at the report we can see that the model had a 100% precision classifying Healthy loans, but only 84% precision for High-risk loans, meaning that some all loans predicted as 'healthy' were indeed 'healthy', but 16% of the loans predicted as 'high-risk' were actually 'healthy'.

Reviewing the recall, we can see the model had an overall high performance in identifying the loans correctly, with a low false-negative rate for both labels.

The accuracy of 99% shows that the model is very effective in distinguishing between healthy and high-risk loans. However, the 84% precision for high-risk loans shows that there may be some false positives that could be addressed to increase it's ability to make correct predictions. Currently the model might lead to denying 'healthy loans'.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

We used the Regression model to try to predict the loan status, 'Healthy loan', or 'High-risk loan'

For this, we imported the available lending data, separated the features from our target variable, 'Loan Status', then using the train_test_split model from the Sklearn library we split the data into training and testing.

After training the model with the training data, we used the model to predict the testing data and evaluated the model's performance using a confusion matrix and classification report.
