# Customer_churn_prediction_using_ML

Project Description
This project focuses on predicting customer churn using machine learning techniques. Customer churn is a critical challenge for businesses, and predicting it can help companies take proactive measures to retain customers. The project employs data preprocessing, exploratory analysis, and machine learning to develop a robust churn prediction model.

Table of Contents
. Introduction
. Dataset
. Technologies Used
. Project Workflow
. Model Evaluation
. Results
. How to Use
. Contributions

Introduction

Customer churn refers to the loss of customers over time. This project predicts customer churn by analyzing key factors like tenure, monthly charges, and total charges, along with demographic and subscription details. The target variable is Churn:

1: Customer churned.
0: Customer retained.
By building a machine learning model, the project aims to identify high-risk customers and understand the factors contributing to churn.

Dataset

The dataset used includes the following features:

. Customer Demographics: Gender, Partner, Dependents.
. Subscription Details: Internet service, contract type, payment method.
. Usage Statistics: Tenure, MonthlyCharges, TotalCharges.
. Target: Churn (Yes/No).

Technologies Used
. Programming Language: Python
Libraries:
. Data Manipulation: pandas, numpy
. Visualization: matplotlib, seaborn
. Machine Learning: scikit-learn

Project Workflow

1. Data Loading and Exploration
. Load the dataset and inspect its structure using .info() and .head().
. Check for missing values and identify key features.
2. Data Visualization
. Explore the distribution of churned vs. non-churned customers.
. Analyze correlations between numeric features.
. Visualize monthly charges and their relationship with churn.
3. Data Preprocessing
. Drop non-informative columns like customerID.
. Encode categorical features using LabelEncoder.
. Scale numeric features (tenure, MonthlyCharges, TotalCharges) using StandardScaler.
4. Model Building
. Define features (X) and the target variable (y).
.Split data into training and testing sets using train_test_split.
. Train a Random Forest Classifier on the training set.
5. Model Evaluation
. Evaluate the model using metrics:
. Confusion matrix.
. Classification report.
. Accuracy score.

Model Evaluation
. Accuracy: Approximately 64%

Insights:

Features like tenure and monthly charges significantly influence churn rates.
The Random Forest Classifier provides robust predictions for binary classification tasks.

Results
The model effectively predicts customer churn, providing actionable insights into customer behavior and enabling businesses to take preventive measures to reduce churn rates.




