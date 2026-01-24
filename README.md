🏥 End-to-End Healthcare Analytics & Predictive Modeling Project

Predicting 30-Day Hospital Readmissions Using Machine Learning

📌 Project Overview

Hospital readmissions within 30 days are a major concern in healthcare systems, leading to higher treatment costs, resource overload, and poor patient outcomes.

This project focuses on building a complete end-to-end healthcare analytics pipeline to predict 30-day hospital readmissions for diabetes patients using data analysis, visualization, and machine learning techniques.

The project covers the entire analytics lifecycle from raw data ingestion to final model deployment-ready outputs.

🎯 Business Objective

Predict whether a patient will be readmitted within 30 days

Identify key clinical and demographic risk factors

Provide actionable insights for hospital management

Enable early risk stratification for better patient care planning

🧠 Key Problem Statement

Can we accurately predict 30-day hospital readmission risk using patient demographics, clinical history, and treatment patterns?

🗂 Dataset Information

Source: UCI Machine Learning Repository

Dataset: Diabetes 130-US Hospitals (1999–2008)

Records: 101,766 patient encounters

Features: 50+ demographic, clinical & administrative attributes

🛠 Technologies Used
Programming & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Tools & Platforms

Jupyter Notebook

Git & GitHub

VS Code

Machine Learning Models

Logistic Regression

Random Forest Classifier

🔄 Project Workflow
Raw Data → Data Cleaning → Feature Engineering → EDA → Encoding → Scaling → 
Train-Test Split → Model Training → Evaluation → Insights → Reporting

🧹 Data Preprocessing

Removed missing and invalid records

Treated missing values using median imputation

Encoded categorical variables using Label Encoding

Engineered new clinical and utilization features

Removed irrelevant columns

📊 Exploratory Data Analysis (EDA)

Univariate & Bivariate Analysis

Readmission distribution analysis

Diagnosis vs Readmission trends

Medication impact analysis

Correlation analysis

Feature relationship visualization

🤖 Machine Learning Pipeline
Models Trained:

Logistic Regression

Random Forest Classifier

Key Techniques:

Stratified Train-Test Split

Feature Scaling using StandardScaler

Class imbalance handling

ROC-AUC based model evaluation

📈 Model Evaluation Metrics

Accuracy

Precision

Recall

ROC-AUC Score

Confusion Matrix

Best Performing Model: Random Forest Classifier

🧠 Key Business Insights

Patients with higher inpatient visits have significantly higher readmission risk

Medication changes & insulin dependency are strong predictors

Longer hospital stay duration increases readmission probability

High diagnosis complexity directly correlates with readmission likelihood

📊 Visual Outputs Generated

Target distribution

Numeric & categorical distributions

Correlation heatmap

Model performance comparison

Feature importance

Confusion matrices

Risk stratification analysis

Final analytical dashboard

Total: 12 high-quality visualizations

🚀 How To Run This Project
Step 1: Clone Repository
git clone 
cd healthcare-readmission-prediction

Step 2: Install Dependencies
pip install -r requirements.txt

Step 3: Run Main Script
python healthcare_analytics.py

📌 Final Deliverables

Cleaned dataset

Machine learning prediction models

Business-ready visual dashboards

Executive summary report

Complete documentation

🏆 Key Learnings

End-to-end data analytics pipeline development

Healthcare data cleaning & preprocessing

Feature engineering techniques

ML model building & evaluation

Business-driven insight generation

Data storytelling via dashboards

👤 Author

Abhishek Saxena
📧 abhishek.saxena_cs22@gla.ac.in
