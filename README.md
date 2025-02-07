# credit-risk-classification

## Overview of the Analysis

For this machile learning model, a set of lending data was analyzed that included:

The size of the loan, 
The interest rate, 
The borrower's income, 
The debt to income ratio, 
The number of accounts the borrower held, 
Derogatory marks against the borrower, 
The total debt.

The dataset was then separated and split into training and testing sets in order to understand the accuracy of the model.  A logistic regression model was implemented using sklearn and fit to our training data to allow us to make predictions on the loans from our lending data. After making our predictions, the model's performance was evaluated by calculating accuracy scores, as well as, generating a confusion matrix and classification report. Using this data and model, the predictions were tested on 19,384 values.

## Results

This section will describe the accuracy score, the precision score, and recall score of the machine learning model:

<img width="452" alt="Screenshot 2025-02-07 at 9 25 17 AM" src="https://github.com/user-attachments/assets/c1c24ec7-12b2-4e29-843d-5bfdf2f608c8" />

* With an accuracy score of 99%, the model proves to successfully do its job at predicting the classifications of healthy `0` and high-risk `1` loans at an exceptional rate.
* The precision score for healthy `0` loans in this model is 100%.  The precision score for high-risk `1` loans in this model is 87%.
* The recall score for healthy `0` loans in this model is 100%.  The recall score for high-risk `1` loans in this model is 95%. The scores display that for each instance where the loans were healthy, they were classified correctly 100% of the time.  For each instance of a high-risk loan, they were classified correctly 95% of the time.

## Summary

Based on the results, the model performed quite well with the lending data provided. The model had no score below 87% in the classification report.  The model could potentially produce better accuracy with more data provided for high-risk `1` loans, as there was an imbalance with a vastly larger amount of healthy `0` loans being tested.  I would not recommend this model to a company until more testing is done as it is of utmost importance to be able to predict high-risk loans with as much accuracy as possible. 


