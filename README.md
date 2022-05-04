# LAB | Imbalance Data

## Building a churn predictor for a Telecom Company

![alt text](https://github.com/MiguelVilloslada/Beautiful-readme/blob/main/94357telecom%20churn.png)

#### Table of content

· Lab Brief
· Process & Tools
· Visualization
· Key Take Aways
___________________
Lab Brief

We are given data from over 7000 customers and our aim is to build a churn predictor using a logistic regression.  

Challenge: Use the given data set to find out if Tenure, Monthly Carges or Senior Citizen are relaible variables to predict wether a customer might leave the company.  

Problem: We are missing important varaibles in the dataset to validate our model as a good predictor 
___________________
Process & Tools

EDA: assessment of dataframe to prepare for cleaning
Data cleaning & wrangling in Python: convert No Yes to 0 1drop 'customer_number' column, drop null values, convert float columns to int

Machine Learning Model: - Logistic Regression
  - iteration 1 (X_lt): SMOTE sampling to improve the imbalance of the target
  - iteration 2 (X_lm): Tomek links removing the instances of the majority class

Code: Jupyter Notebook - ![alt text](https://github.com/MiguelVilloslada/Beautiful-readme/blob/main/LAB%20Imbalance%20data.ipynb)
___________________
Visualization

![alt text](https://github.com/MiguelVilloslada/Beautiful-readme/blob/main/LogisticRegression.png)
___________________
Key Take Aways
1. Our model can predict customer churn with an accurancy of 78%

2. However we are missing important varaibles in the dataset to validate our model as a good predictor. We would like to see relevant data like; age, customer satisfaction survey, negative customer experiences, lower cost substitutes from competitors
