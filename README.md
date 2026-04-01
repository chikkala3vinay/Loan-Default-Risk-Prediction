# Loan-Default-Risk-Prediction Using machine Learning
## Project Overview
Developed a machine learning model to predict loan default risk using customer financial and demographic data, helping financial institutions make better lending decisions and reduce risk.
## Problem Statement
Financial institutions face significant challenges in identifying customers who are likely to default on loans. Incorrect assessment of credit risk can lead to financial losses and poor decision-making in loan approvals. Therefore, there is a need for an intelligent system that can accurately predict loan default risk using available customer data.
This project aims to build a machine learning model that analyzes demographic, financial, and credit-related features to classify whether a customer will default or not. The problem is formulated as a binary classification task, where the output indicates default risk (1) or no default (0).
By predicting high-risk customers in advance, the model can help institutions reduce credit risk, improve loan approval strategies, and enhance overall financial stability. The solution should be accurate, reliable, and scalable for real-world financial applications.

## Objective
The main objective of this project is to predict whether a customer is likely to default on a loan.  
This system helps financial institutions to:  
Reduce credit risk  
Identify high-risk customers early  
Make accurate and data-driven loan approval decisions 
## DataSet Description
The dataset contains customer demographic and financial information such as:  
Income  
Savings  
Monthly expenses  
Loan amount  
Credit score  
Employment details  
Loan history 
The target variable is Loan Default Status, where:  
0 = No Default  
1 = Default  
## Methodology  
The project follows a complete end-to-end machine learning workflow:  
Data loading and inspection  
Exploratory Data Analysis (EDA)  
Handling missing values using imputation  
Feature scaling and encoding  
Train-test split  
Model training  
Model evaluation and comparison 
## Models Implemented  
The following classification models were implemented and compared:  
Logistic Regression  
Decision Tree  
Random Forest  
Support Vector Machine (SVM)  
XGBoost  
## Evaluation  
The models were evaluated using:  
Accuracy Precision  
Recall  
F1-Score  
Confusion Matrix 
## Model Performance Summary  
Logistic Regression → ~94%  
Decision Tree → ~92%  
Random Forest → ~94%  
SVM → ~92–93%  
XGBoost → ~95–96% (Best Model)  
Among all models, XGBoost achieved the highest accuracy with balanced precision and recall, making it 
the most reliable model for this dataset.  
## Conclusion  
In this project, an end-to-end Credit Default Risk Prediction system was successfully developed using 
machine learning techniques. The complete data science workflow—from data preprocessing and EDA 
to model training and evaluation—was implemented.  
Among all models, XGBoost delivered the best performance with an accuracy of approximately 95–96%, 
indicating strong predictive capability. This demonstrates that machine learning can effectively support 
financial institutions in predicting credit default risk and improving lending decisions. 
