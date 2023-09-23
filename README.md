# credit-risk-classification
##Background:
use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.There are two category healthy loan (good credit or good payment history), and high_risk loan(bad credit or low payment history or don't pay on time).So Bank has to predict how many percent of high risk loan depend on some factors like mainly size of the loan, interest rate, income, debt etc.
. Split the Data into Training and Testing Sets

. Create a Logistic Regression Model with the Original Data

. Write a Credit Risk Analysis Report

Create a Logistic Regression Model with the Original Data:
Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:
original data classification
<img width="398" alt="image" src="https://github.com/stargily2017/credit-risk-classification/assets/117419179/0fe36adb-379e-4c58-a870-d13a54640ff5">


Generate a confusion matrix.
This is oversamples data , classification

<img width="473" alt="image" src="https://github.com/stargily2017/credit-risk-classification/assets/117419179/becfc431-e498-4136-80fe-9a4882e35882">



An overview of the analysis: Explain the purpose of this analysis.

The results: 
comparatively, oversampled data prediction is preferred over the original sampled ones. recall value is 1.00 in oversampled, that means prediction of high risk loan is 100% correct.
False negative(error showing, actually they are in high risk loan category, but not showing in the actual value(558 or 623) is down from 67 to 2, 
This means error is less in the over sampled data, to give strong prediction in high risk loan.Bank can give attention to the potential high risk people and to find the fraudulants too. Bank can investagate the reason behind the high risk loans and take proper decsions thta help to hold the company growth.
