# Predicting-using-Machine-Learning-Regression
This notebook will show you step by step to build machine learning to predict compensation of some employee.

## Step by Step:
## 1. Data Understanding: Before we start to process our data we MUST understand a feautures of the data
### Feautures
- Name = Full name of the employee.
- Benefits Category = Benefit category of employee.
- Department = Employee department.
- Job Title = Job title of employee.
- Full/Part Time = Employee full or part-time status.
- Hire Date = Employee hire date.
- Termination Date = Employee termination date (if applicable).
- Hourly Rate = Employee hourly pay rate.
- Regular Pay = Annualized base pay of employee.
- Oveprtime Pay = Employee overtime paid.
- Other Pay = Other Pay includes productivity enhancement pay, shift differential pay, standby pay, allowances, leave payout, and incentives

## 2. Data Preprocessing: In this step we will processing our raw data using several techniques like eliminated, manipulated,etc.
### Preprocess:
- Clear rows with with negative values
- Convert Hire Date & Termination Date from object into datetime
- Add new column Experience (Termination Date – Hire Date)
- Drop column Hire Date & Termination Date 
- Encoding Full/Part Time (‘F’ = 1 ,  ‘P’ = 0)
- Checking and Handling Missing Values
- Checking and Handling Outliers

**Checking and Handling missing values and outliers is IMPORTANT step when we want to build machine learning with Linear Regression, cuz this model is very sensitive with outliers.**

## 3. Build and Find the best model for our Machine Learning: We will compare several Regression Algorithm and choose the right model that we can use to our Machine Learning.
### Linear Regression:
- Standard Linear Regression (Baseline)
- Ridge Regression
- Lasso Regression
### Non-Linear Regression
- Decicision Tree
- XGBOOST
- Random Forest


