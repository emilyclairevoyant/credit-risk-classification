# Module 12 Report Template

## Overview of the Analysis
For the following analysis, I was using logistic regression to try and predict the creditworthiness of lenders. Logistic regression showed to be the best model to use for this case as the data being used for predicting was binary, and predicting the outcome of this data set aligned with the purpose of a logistic regression. The information given in the initial dataset included: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogaatory marks, total debt, and their current loan status. In order to make appropriate predictions, I utilized the loan status, which was presented as 0 being equal to a high-risk loan and 1 being equal to a healthy loan. 
In order to correctly run this model, I first split the dayta into training and testing sets using X and y, with y being equal to the loan status and X being equal to the remainder of the data frame. Once the data was split accordingly, I fit a logistic regression model using the training data, and then created a new data frame comparing the predicted loan status value and the actual loan status value. Finally, the model's performance was evaluated using both a confusion matrix and a classification report. 

## Results
* Logistic Regression:
    * Accuracy: 99%
    * Healthy Loan Precision: 100%
    * Healthy Loan Recall: 99%
    * High-Risk Loan Precision: 84%
    * High-Risk Loan Recall: 94%
    

## Summary
Overall, the logistic regression model actually performs quite well at predicting creditworthiness, especially when it comes to healthy loans as those scores are either at 100% or almost 100%. The accuracy is almost at 100% as well, meaning it correctly classified almost every single instance while training and testing. Based on the numbers given, I would say the logistic regression model works for this set of data and I do believe this would be the right model to use for this purpose. As someone with a healthy loan status has a higher precision and recall, and therefore have better credit, this is an appropriate model to use for this purpose.
