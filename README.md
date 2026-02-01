Customer Churn Analysis & Prediction

🔍 Project Overview

This project focuses on analyzing customer behavior for a telecom company and building a machine learning model to predict customer churn. The goal is to identify customers who are likely to leave the service and uncover the key factors driving churn, enabling businesses to take proactive retention actions.

🎯 Objectives

Analyze customer data to understand churn patterns

Identify important factors influencing customer churn

Build and evaluate machine learning models to predict churn

Support data-driven decision-making for customer retention

📊 Dataset Description

Total records: 7,043 customers

Key features:

Demographics (gender, senior citizen, dependents)

Account information (tenure, contract type, payment method)

Service usage (internet service, add-ons, support services)

Billing details (monthly charges, total charges)

Target variable: Churn (Yes / No)

🛠️ Tools & Technologies

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Machine Learning: Scikit-learn, XGBoost

Techniques: EDA, feature engineering, data preprocessing, model evaluation

🔎 Key Steps Performed

Data cleaning and handling missing values

Exploratory Data Analysis (EDA) to identify churn trends

Encoding categorical variables and scaling numerical features

Training and evaluating multiple classification models

Comparing models using accuracy, ROC-AUC, and confusion matrices

🤖 Models Used

Logistic Regression

Random Forest

XGBoost

📈 Results & Insights

Random Forest achieved the best overall performance among tested models

Customers with short tenure, month-to-month contracts, and higher monthly charges showed higher churn rates

Lack of support services (online security, tech support) increased churn probability

💡 Business Impact

The model can help businesses:

Identify high-risk customers early

Design targeted retention strategies

Reduce revenue loss due to customer churn

📁 Repository Structure
Customer-Churn-Prediction/
│── README.md
│── Customer Churn Analysis.py
│── Dataset.csv   

✅ Conclusion

This project demonstrates an end-to-end data science workflow, from data exploration to machine learning model evaluation. It highlights how predictive analytics can be applied to solve real-world business problems in customer retention.



















