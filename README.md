# credit-risk-classification-analysis

# Information
The dataset was split into training and testing sets. Used the logistic regression model to train the original data to predict if the loan was either healthy or high-risk. The predictions from the model returned a balanced accuracy score of 95.2% indicating a well performance. Then resampled the training data with the RandomOverSampler model. The resampled data was then used in the logistic regression model for retesting. At a quick glance, model 2 appears to perform better, but we must always review the overall results and consider the purpose of the training. This is extremely important and further supports why multiple training models are used to determine which is the most suitable. The predictions from the resampled data shows an improvement for the high-risk loans. The balanced accuracy score also increased to 99.3%. Model 2 would be best if the goal is to check for high-risk loans.


# Technologies Used
* Jupyter Notebook
* Pandas
* Sklearn
* Matplotlib
* Python
-----------------------------------------------------------------------------------------------------
