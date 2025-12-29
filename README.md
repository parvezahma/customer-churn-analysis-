📊 Customer Churn Analysis & Prediction
📌 Project Overview

Customer churn is one of the most critical challenges faced by subscription-based and service-oriented businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project focuses on analyzing customer behavior and predicting churn using statistical analysis, exploratory data analysis (EDA), and machine learning models. The goal is to identify key churn drivers and build predictive models that help businesses take proactive retention actions.


🎯 Business Objectives

Understand customer behavior patterns leading to churn

Identify key factors influencing customer attrition

Build reliable machine learning models to predict churn

Provide actionable business insights to reduce churn rate


🗂️ Dataset Description

The dataset contains customer information related to an internet service provider, including:

Demographic information

Subscription details

Service usage patterns

Billing and payment information

Customer churn status (Target Variable)


 Approach & Methodology
 Data Understanding & Cleaning

Data type validation

Missing value checks

Target variable distribution analysis

Feature classification (categorical vs numerical)



 Exploratory Data Analysis (EDA)

Churn distribution analysis

Numerical feature distribution analysis

Categorical features vs churn visualization

Business-oriented insights extraction




 Data Preprocessing

Label encoding for categorical variables

Feature scaling using StandardScaler

Train-test split with stratification

 Model Development

Two models were implemented and evaluated:

Logistic Regression (Baseline model)

Random Forest Classifier (Advanced ensemble model)

 Model Evaluation

Confusion Matrix

Precision, Recall, F1-Score

ROC-AUC Curve

Feature Importance analysis

# tool that hasbeen used 

Programming Language: Python

Libraries:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Modeling Techniques:

Logistic Regression

Random Forest


Key Results & Insights

Random Forest outperformed Logistic Regression across all major metrics

Features related to contract type, tenure, and monthly charges were strong churn indicators

Customers with short tenure and higher monthly charges showed higher churn probability

Ensemble models provided better generalization and interpretability through feature importance


Visualizations Included

Churn distribution plots

Feature distribution histograms

Categorical feature comparisons

Confusion matrix heatmap

ROC-AUC curve

Feature importance bar chart













