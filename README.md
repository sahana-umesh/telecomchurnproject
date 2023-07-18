# Telecom-Churn-Case-Study

## Objective

This project is the case study on the problem churn in the telecom industry based on the indian and south east asian market, to identify the churn rate and the cause behind such rate.
Their problem is that, usage-based churn needs to be identified and tackled to avoid high churn in user base of high revenue customers.
So, a solution is demanded to curb the same.
In this project we have tried to implement a model based on Logistic Regression Model Building to achieve the above goal.

## Details of files given

For this project we have following documents to build and support our case study apart from this read.me file: -
- Telecom Churn Case Study DSC50.ipynb : Assignment Python Notebook file.
- Telecom Churn PPT.pdf : presentation file

## Steps Followed

This project case study is useful for all such platforms which are dealing with lot of applicants on the platform but a much smaller customer conversion rate e.g., let’s say people tend to try a free trial but won’t go for the paid version. It is hard for the companies to find potential customers.
This is how we have approached to the solution:
1.	Reading data dictionary
2.	Loading dataframe
3.	Treating null values with either imputing or dropping them
4.	Filtering the data to keep only high revenue customers in the dataset
5.	Using activity of the first two months, which is the good phase to identify churn.
6.	Tagging churners by assigning a binary variable and removing the churn phase data to prepare the dataset for final model building
7.	Building Logistic Regression Model
8.	Identifying multicollinearity and using SMOTE method to handle the same
9.	Deploying on test dataframe
10.	Evaluating model
11.	Drawing conclusions and recommendations from the results obtained

This case study is built by a group of three students of a master’s program. - Kush, Sahana and Sanjeev
