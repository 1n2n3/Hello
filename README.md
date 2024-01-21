# Credit-Card-Fraud-Detection
Using Logistic Regression / Decision tree / Random Forest / XgBoost with Hyperparameter Tuning

# Dataset Overview
A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

# Data Dictionary
Time - It contains the seconds elapsed between each transaction and the first transaction in the dataset
V1 to V28 - This features are the principal components obtained with PCA
Amount - Transaction amount
Class - response variable / value contains 0 and 1 (where 0 = Not Fraud and 1 = Fraud transcation) / (Target variable)

# Dependencies
pandas
numpy
matplotlib
seaborn
sweetviz
sklear
LogisticRegression
RandomForestClassifier
DecisionTreeClassifier
SVM
GridSearchCV
RandomizedSearchCV

# Usage
1) LogisticRegression / RandomForestClassifier / DecisionTreeClassifier / XGboost Classifier model with Hyperparameter tuning notebook.ipynb is Jupyter Notebook which contains classifier model and comparision of GridSearchCV & RandomizedSearchCV Models.
2) conclusion.csv contains outputs of xgboost models of notebook. This file is made by me and I used it to plot various conclusive plots in jupyter notebook.
3) Project details.txt is a txt file which details about the project
4) Correlation matrix of all features is a png file which contains Correlation matrix of all columns of the dataset to understand and visualize the data in a better way.
