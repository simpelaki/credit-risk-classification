# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.


Analysis

The aim of this is analysis is to use the historical lending activity dataset, to build and implement a model that can identify the credit worthiness of borrowers. The model will predict the risk levels for each borrower and classify their loan status as either healthy or high-risk. The financial information used to build the model consisted fo the loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks and total debt. These are key information that assesses the borrower's ability to repay the loan.

In order to create a working model to best predict the loan status, the dataset was split into training and testing sets. The first model used for the loan status predictions was Logistic Regression. The second model, was RandomOVerSampler with resampled data from the dataset. After processing the data with the model, the prediction results were then displayed with the confusion matrix and classification report was generated.


ML Model 1
Accuracy: 95.20%
Recall: healthy-99%, high-risk-91%
Precision: healthy-100%, high-risk-85%

ML Model 2 
Accuracy: 99.36%
Recall: healthy-99%, high-risk-99%
Precision: healthy-100%, high-risk-84%

Summary

ML Model 2 appeared to have better performance than Model 1. Also the high-risk precision decreased by 1%. 
The recall results for the high-risk loans improved with Model 2. We can also see improvement in the accuracy score. 
I am rwould commend the Model 2 instead of Model 1 for the assessment when checking for high-risk loans. I belive Model 2 fites better than Model 1. 

