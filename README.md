# credit-risk-classification
Module 20 HW

# Overview
The purpose of this analysis is to create a machine learning model that predicts healthy loan versus high risk loans based on application data. The criteria include loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, and total debt. 


# Model Performance
*  Accuracy - The accuracy of the model was 94% prior to oversampling and 99% after oversampling.
*  Precision - The precision for the model was good for identifying healthy loans, but significantly less performant when identifying high risk loans. With oversampling the latter result improved significantly. 
*  Recall -The recall for the model was good for identifying healthy loans, but significantly less performant when identifying high risk loans. With oversampling the latter result improved significantly. 

# Summary
The original model is good at predicting healthy loans, however significantly less successful at predicting high risk loans. Using an oversampling technique, the model performance is improved significantly with respect to identifying high risk loans. The latter model, with oversampling training is recommended, due to 99% accuracy with respect both healthy and high risk loans and a similar result for false positives. 
