# Project Report:

## Abstract
The main goal of this project is to create a classification model to predict a customer will leave the bank or not.

## Design
The data provided by kaggle has the main information about bank custoemrs such as the salary, age, gender then we cleaned the data and preform EDA to visually present the data, preprocessing then modeling and evaluating the best model with F1 score as our metric.

## Data
In this project we used the data from kaggle [HERE](https://www.kaggle.com/santoshd3/bank-customers) it contains 10000 rows with 14 columns.

## Algorithms
we’ve done the data cleaning and removing the nulls and we did some feature engineering by removing outliers and balance the target, also we transformed the categorical features into label encoder then we split our data and created our baseline model witch was logistic regression then we wanted to improve the model, we used decision tree and random forest and eXtreme Gradient Boosting classifier and ensemble using max voting and we found that random forest has the best accuracy score since it’s our chosen metric.

## Tools
- Python and Jupyter Notebook
- Numpy and Pandas for data manipulation
- Matplotlib, Seaborn for visuializations
- Sklearn and Dabl for ML algorithms
