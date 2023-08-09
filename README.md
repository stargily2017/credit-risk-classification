# credit-risk-classification
##Background:
use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
. Split the Data into Training and Testing Sets

. Create a Logistic Regression Model with the Original Data

. Write a Credit Risk Analysis Report

Create a Logistic Regression Model with the Original Data:
Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.
            precision    recall  f1-score   support

  healthy loan       1.00      1.00      1.00     18759
high-risk loan       0.87      1.00      0.93       625

      accuracy                           1.00     19384
     macro avg       0.94      1.00      0.96     19384
  weighted avg       1.00      1.00      1.00     19384


An overview of the analysis: Explain the purpose of this analysis.

The results: Using a bulleted list, describe the accuracy score, the precision score, and the recall score of the machine learning model.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. Resampled data prediction is better. Accuracy and recall are both 100%. That means prediction is true.
