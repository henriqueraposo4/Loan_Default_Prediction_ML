# Loan Default Prediction
The main goal of the project is to use the information that is available before a loan is issued to provide a method to predict if a loan request will be defaulted or not.

## About the data
This project will be working with a dataset made available through Lending Club. The original data is made available through Kaggle. The original data included information for the years starting from 2007. However, to avoid the adverse effects of the recession, the data will consist of a sample between 2009 and 2011.

Lending Club is a peer-to-peer lending company, where individuals can take personal loans based on their creditworthiness. The loan issue and approval processes are typically not as stringent as a bank and are usually unsecured. Hence, it is very important for Lending Club, as a platform to know ahead of time which loans will default and which loans will be successfully repaid.

## Results
Two models were used for the prediction, logistic regression, and a decision tree. The first had 82.97% accuracy while the latter had 79.87%. The logistic regression had fewer false positives which is predicting someone will default when they do not actually default while the decision tree model had fewer false negatives, which is predicting someone will not default who actually defaults.
