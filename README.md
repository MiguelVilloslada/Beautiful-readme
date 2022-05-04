# LAB | Imbalance Data

## Building a churn predictor for a Telecom Company

![alt text](https://github.com/MiguelVilloslada/Beautiful-readme/blob/main/94357telecom%20churn.png)

#### Table of content

. Lab Brief
. Data
. Process & Tools
. Visualization
. Key Take Aways
___________________
Lab Brief

We are given data from over 7000 customers and our aim is to build a churn predictor using a logistic regression machine learning model.  

Challenge: Using data from Tenure, Monthly Carges and Senior Citizen as the variables to predict whether a customer might leave the company.  

Problem: We are missing important variables in the dataset to validate our model as a good predictor 
___________________
Data: 

csv data 
___________________
Process & Tools

EDA: assessment of dataframe to prepare for cleaning
Data cleaning & wrangling in Python: convert object to int 

Machine Learning Model: - Logistic Regression
  - iteration 1 (X_lt): SMOTE sampling to improve the imbalance of the target
  - iteration 2 (X_lm): Tomek links removing the instances of the majority class

Code: Jupyter Notebook - [here](https://github.com/MiguelVilloslada/Beautiful-readme/blob/main/LAB%20Imbalance%20data.ipynb)
___________________
Visualization

![alt text](https://github.com/MiguelVilloslada/Beautiful-readme/blob/main/LogisticRegression.png)
___________________
Key Take Aways

1. Our model can predict customer churn with an accurancy of 78%

2. However we are missing important varaibles in the dataset to validate our model as a good predictor. We would like to see relevant data like; age, customer satisfaction survey, negative customer experiences, lower cost substitutes from competitors
