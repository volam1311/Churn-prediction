# Churn Prediction
## Problem statement:
Nowadays, many companies experience customer churn, which can cause big lost in the revenue.
    
__What is churn?__
- Churn refers to the rate at which customers stop doing business with a company, often expressed as a percentage of total customers or revenue.
- Churn rate can be expressed as $$ \frac{\text{number\_of\_churn}}{\text{total\_custormer}} * 100\% $$

__Necessary of churn analysis and prediction__
- Many companies need data analysts and data scientists to find the causes of this problem and reduces the number of customer churn
- By analyzing the data of churn, companies can find the solution for this problem. Also by predicting which types of customer is likely to leave the service, companies can come up with other short-term service for them.

## Data analyzing:
![image](https://github.com/user-attachments/assets/ba071d4a-11c1-42ae-a04b-05d5b0fcbad1)

From the analyze, we can see that the churn rate is more than 25%. Customers who are likely to leave the service has the Senior Citizen = 1 and people who sign for the short-term contract, especially the "Month-to-month" contract.
People who sign for the Fiber optic Internet Service also makes up a high proportion of people who are likely to be classified as churn.

## Data Preprocessing:

After analyzing the data and choose the best features for the model, we should then clean the features before train it.

## Training the model:

There is no linear correlation between the numeric values in the training data so we will not use Logistics Regression. Instead we will use SVC.

### Skills and Tools:

- Jupyter Notebook
- Tableau
- Machine Learning algorithms

