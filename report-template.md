# Module 12 Report Template

## Overview of the Analysis

The credit risk analysis is meant to predict the risk level of loan borrowers. 
The dataset comes with a list of information regarding income, debt-to-income ratio, loan size, interest rates, derogatory marks, total debt, and number of accounts. 
The outcome variables such as value_counts gave us the number of loan requests made, with 0 representing the “healthy loans” and 1 representing the “risky loans”.
The machine learning process began with splitting the data into labels and features, and then from there created training datasets and testing datasets.
Then we used LogisticRegression to test the dataset.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * The precision score of 100% for the healthy loans and 85% for the high-risk loans. 
  * The recall score was 99% for the healthy loans and 91% for the high-risk loans.
  * The model correctly predicted the status of 99.2% of the loans.



* Machine Learning Model 2:
  * The precision score was 84% for high-risk loans, and 100% for healthy loans.
  * The recall for was 99% for both high-risk loans and healthy loans.
  * The balanced accuracy score increased to 99.4%.


## Summary

Summarize the results of the machine learning models.
  * It seemed like Model 2 had more accurate results with a higher recall score for the high-risk loans.


