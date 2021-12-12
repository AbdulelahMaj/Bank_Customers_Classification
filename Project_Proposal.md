# Churn for bank customers


> ## Introduction
> 
>> The purpose of the model I plan to build is to predict whether an individual customer will churn from the bank (or not) given various data points and information from a historical database.

So in the future, when we have a customer, we can predict if this person will leave or not. This will help with the decision making framework for whether a customer will leave or not.

With this prediction model, the bank will benefit from being able to predict the risk of the customer on whether they will leave or not.

> ## Goals
> 
>> To predict if the customer will churn from the bank or not.



> ## Data Description
> 
>> I will take the data from [Kaggle](https://www.kaggle.com/mathchi/churn-for-bank-customers), I plan to use these **classes & features**:
>
 | class  |  Description |
 | ------------- | ------------- |
 | exited  | customer will leave |
 | not exited | customer will stay |

 >
 ----
 >
 | Feature  |  description |
 | ------------- | ------------- |
 | RowNumber | corresponds to the record (row) number and has no effect on the output. |
 | CustomerId | contains random values and has no effect on customer leaving the bank. |
 | Surname | the surname of a customer has no impact on their decision to leave the bank. |
 | CreditScore | can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank. |
 | Geography | a customer’s location can affect their decision to leave the bank. |
 | Gender | it’s interesting to explore whether gender plays a role in a customer leaving the bank. |
 | Age | this is certainly relevant, since older customers are less likely to leave their bank than younger ones. |
 | Tenure | refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank. |
 | Balance | also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances. |
 | NumOfProducts | refers to the number of products that a customer has purchased through the bank. |
 | HasCrCard | denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank. |
 | IsActiveMember | active customers are less likely to leave the bank. |
 | EstimatedSalary | as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries. |
 
 
 > ## Tools
 > 
 >> - Python
 >> - Jupyter notebook
 >> - Seaborn
 >> - Matplotlib
 >> - Pandas
 >> - sklearn

> ## Conclusion 
> 
>> I expect the classification model will predict if a customer will leave or not.