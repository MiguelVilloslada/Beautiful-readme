# LAB | Imbalance Data

## Building a churn predictor for a Telecom Company

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

#### Table of content

· Lab Brief
· Data
· Process & Tools
· Visualization
· Key Take Aways
___________________
Lab Brief

We are given data from over 7000 customers and our aim is to build a churn predictor using a logistic regression.  

Challenge: Use the given data set to find out if Tenure, Monthly Carges or Senior Citizen are relaible variables to predict wether a customer might leavee the company.  

Problem: We are missing important varaibles in the dataset to validate our model as a good predictor 
___________________
Data

I used Python's data visualisation tools to explore the relationships between the variables.
___________________
Process & Tools

EDA: assessment of dataframe to prepare for cleaning
Data cleaning & wrangling in Python: drop 'customer_number' column, drop null values, convert float columns to int

Machine Learning Model: - Logistic Regression
  - iteration 1 (X_lt): SMOTE sampling to improve the imbalance of the target
  - iteration 2 (X_lm): Tomek links removing the instances of the majority class

Code: Jupyter Notebook - Link to code folder
___________________
Visualization


___________________
Key Take Aways
1. Our model can predict a customer accepting or declining the credit card offer with an accuracy of 84%
2. We suspect the following features to impact the customers decision to accept the most:
mailer type
credit rating
income level
reward
