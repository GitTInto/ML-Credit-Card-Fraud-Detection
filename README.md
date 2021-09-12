# Cedit card fraud detection using Mechine Learning

## Problem statement:
Credit Card Fraud is one of the biggest issues faced by the government and banks and the amount of money involved in this is generally enormous. As world is getting more towards digitalization, the risk of online fraud is also increasing. The websites with online payment mode contributes to rise in online frauds. Also, due to this pandemic situation(COVID-19), everyone prefers to do cashless transaction which increases the chances of people getting trapped into such frauds.

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. Among all of the online frauds, one such fraud is credit card fraud which is an ever growing menace in the financial industry. Detecting fraudulent transaction is of great importance for any credit card company.

We are going to approach this real life problem using Data Science to find ways to predict if a new transaction is fraudulent or genuine

## Proposal:
To develop a model that provide best results to identify/predict credit card fraudulent transactions. This will help both, the credit card company and the customers from getting charged unnecessarily by preventing fraudulent transactions.

## Feature selection
Model selection and evaluation
Finding if a transaction is fraudulent or genuine is a classification problem and I am planning to use a. Logistic regression b. Random Forest Classifier We will find the best values for few hyperparameters. Then we will evaluate both the algorithms.

## Data set
The dataset is obtained from Kaggle. https://www.kaggle.com/mlg-ulb/creditcardfraud

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.

There are 284807 number of transactions(rows) and 31 features in this dataset.

Time: It contains the seconds elapsed between each transaction and the first transaction in the dataset.

Amount: It is the transaction Amount.

Class: It is the response variable and it takes value 1 in case of fraud and 0 otherwise
