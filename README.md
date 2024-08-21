# Credit Risk Classification

## Overview of the Analysis

In this challenge, a dataset of lending activity from a peer-to-peer lending services company is used to build a model to identify the creditworthiness of borrowers. A borrower's loan size, interest rate, income, debt-to-income ratio, number of accounts, derogatory marks, and total debt are taken into consideration when determining their loan status. 

To create the prediction model, lending activity data was split into training and testing datasets. SciKit Learn was used to call the LogisticRegression algorithm (with a random state of 1) to fit the training data. A predication model was then created with the fitted model and testing freature data. The model's performance was evaluated by generating a confusion matrix and classification report. 

## Results

* Machine Learning Model 1:
  - Healthy Loan - Precision: 100%  Recall: 100%
  - High-risk Loan - Precision: 87%  Recall: 89%
  - Overall Accuracy: 99%
 
## Summary
The logistic regression model predicts healthy loans with 100% precision and recall, while high-risk loan predictions perform slightly lower for each although still receiving high scores. Possibly more high-risk data is needed to increase the accuracy of prediction. With an overall accuracy off 99%, this model is recommended for predicting both healthy and high-risk loans. 