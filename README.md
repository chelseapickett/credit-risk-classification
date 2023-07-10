# credit-risk-classification

## Credit Risk Analysis Report
### Overview
A machine learning model was used to predict healthy and high risk loan labels to identify the creditworthiness of borrowers from a dataset of historical lending activity provided by a peer-to-peer lending services company. The data was split into training and test data sets which were used in a logistic regression model with the original data. A logistic regression model using resampled training data was also created to compare to the original model. The models were scored using the balanced accuracy score, confusion matrix and classification report imports from scikit-learn library. 

### Results
Logistic Regression Model with Original Data Scores:
- Balanced Accuracy Score: 95%
- Accuracy: 99%
- Precision: (weighted avg) 99%           
- Recall: 99%

Logistic Regression Model with Resampled Data Scores:
- Balanced Accuracy Score: 99%
- Accuracy: 99%
- Precision: (weighted avg) 99%           
- Recall: 99%

### Summary
Analysis shows the second logistic regression model using resampled data is a more reliable method for predicting healthy loan and high risk loan labels based on the training data provided. The classification report shows accuracy, precision and recall scores of 99% in both models which provide a high level of confidence in both models. However, the balanced accuracy score is 4% higher in the second model and perhaps most importantly, the second model produces a lower incidence of false positives, or predictions that a loan is healthy when it is actually high risk and an increased prediction of high risk loans that are actually high risk. Overall the second model produces more conservative predictions about the loan status and would be more beneficial for a lending servicers' needs. 

