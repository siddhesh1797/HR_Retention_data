# HR_Retention_data
A brief analysis on HR Retention data using some Machine Learning techniques

### Problem Statement - Figuring Out Which Employees May Quit

## Data Overview

The dataset has 14999 observations for past/present employees.
The observations span 9 different variables.
Each observation includes the employee’s current employment status.

Target variable
'left' – Current employment status Employed(0) / Left(1)

Features

'department' – Department employees belong to

'salary' – Salary level relative to rest of their department

'n_projects' – Number of projects employee is staffed on

'avg_monthly_hrs' – Average number of hours worked per month

'satisfaction' – Score for employee’s satisfaction with the company (higher is better)

'last_evaluation' – Score for most recent evaluation of employee (higher is better)

'promotion_last_5years' - Employee promoted in last 5years


### Model Building & Comparison:
We've used quite a few models to check which fits best on our data. Models used are –

•	Logistic Regression
•	Random Forest Classifier
•	Decision Tree Classifier
•	k-NN Classifier
•	SVC
•	XGBoost Classifier

Since this is binary classification problem, we use the following metrics:

Confusion matrix - For getting a better clarity of the no of correct/incorrect predictions by the model

ROC-AUC - It considers the rank of the output probabilities and intuitively measures the likelihood that model can distinguish between a positive point and a negative point. (Note: ROC-AUC is typically used for binary classification only). We will use AUC to select the best model.
