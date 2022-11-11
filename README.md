# Credit-Card-Fruad-Detection

In this project, I will apply machine learning concept to detect whether a transaction is fruadulent or legitimate. I will employ logistic regression as the model and utilizing scikit learn to split the data into training data and testing data in order to develop a efficient model to predict the result

Data Link is from kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

0 represents real transaction
1 represents fruadulent transaction

Dataset is taken from credit card companies and it presents transactions that occurred in two days where we have 492 frauds out of 284,807 transactions. the positive class (frauds) account for 0.172% of all transactions. Thus Dataset is biased and highly unbalanced.


I applied Data smpling technique to take 492 random sample from the legitimate transactions to combined with the fradulent transaction to make a temp dataset for our modeling as this should be better than the original biased dataset.

Spliting the data into training data and testing data with 10% the testing data and 90% as the training data.

After fitting our data to the logistic regression model, the accuracy score on training data is 92% and for the accuracy score on testint data is 91% which is quite identical


Last, building a predictive system to check with our result to see if they r accurate
