# LAB | Imbalance Data

## Building a churn predictor for a Telecom Company

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

#### Table of content
· Lab Brief
· Data
· Process & Tools
· Visualization
· Key Take Aways
Project Brief
Scenario: We are risk analysts employed at a bank. Our team is focusing on credit card services. We are given data from 18.000 of our customers and our boss wants us to work out how we can improve our credit card marketing campaign.

Challenge: Use the given data set to find out what characteristics impact the customers decision on accepting or declining our credit card offer.

Problem: Can we build a machine learning model that predicts if our customer accepts or declines the credit card offer?

(https://www.google.com)



Github: set up our Github repo to collaborate on. We did 104 commits in 4 days.
Trello: set up our Trello board to help us keep sane and reprioritise daily.
SQL: started with the independent task of completing the SQL queries
EDA: assessment of dataframe to prepare for cleaning
Data cleaning & wrangling in Python: drop 'customer_number' column, drop null values, convert float columns to int
Prepocessing: 3 methods - Normalizer, Dummies and SMOTE
Machine Learning Model: using scikit learn
- iteration 1 (X): In our first iteration we only used preprocessing and encoding and used this as a benchmark for the following iterations as comparison
- iteration 2 (X_i2): SMOTE sampling to improve the imbalance of the target
- iteration 3 (X_i3): dropping quarterly balance columns to reduce noise
- iteration 4 (X_i4): encoding numerical features to categorical ones
- iteration 5 (X_i5): using KNN on the i3

Code: Jupyter Notebook - Link to code folder


Key Take Aways
1. Our model can predict a customer accepting or declining the credit card offer with an accuracy of 84%
2. We suspect the following features to impact the customers decision to accept the most:
mailer type
credit rating
income level
reward
