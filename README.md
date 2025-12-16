# Employee-Attrition
📌 Project Overview

Employee attrition (employee turnover) is a major challenge for organizations, as losing experienced employees leads to increased recruitment cost and productivity loss.
This project focuses on predicting whether an employee is likely to leave the organization using machine learning techniques.

The model is trained on the IBM Employee Attrition dataset, performing data analysis, feature engineering, class imbalance handling, and classification using Random Forest.

🎯 Objectives

Analyze employee-related factors influencing attrition

Handle class imbalance in the dataset

Build a reliable machine learning model to predict attrition

Identify the most important features affecting employee attrition

🗂️ Dataset

Dataset Name: Employee Attrition Dataset

Source: IBM HR Analytics Dataset

Target Variable: Attrition

Yes → Employee left

No → Employee stayed

🛠️ Technologies & Libraries Used

Programming Language: Python

Data Processing: NumPy, Pandas

Data Visualization: Matplotlib, Seaborn, Plotly

Machine Learning: Scikit-Learn

Imbalanced Data Handling: SMOTE (imbalanced-learn)

🔍 Exploratory Data Analysis (EDA)

KDE plots to study relationships between:

Age vs Total Working Years

Daily Rate vs Job Satisfaction

Work-Life Balance vs Job Satisfaction

Correlation heatmap to identify relationships among numerical features

⚙️ Data Preprocessing

Converted categorical target variable (Yes/No) into numerical format

One-Hot Encoding applied to categorical features

Combined numerical and categorical features into a final dataset

Train-test split with stratification to preserve class distribution

⚖️ Handling Class Imbalance

Employee attrition data is imbalanced.
To solve this, SMOTE (Synthetic Minority Over-sampling Technique) was applied to the training dataset to balance classes and improve model performance.

🤖 Machine Learning Model

Model Used: Random Forest Classifier

Key Parameters:

Number of trees: 1000

Max depth: 4

Feature selection: √(features)

Random Forest was chosen for its robustness and ability to handle non-linear data.

📈 Model Evaluation

The model performance was evaluated using:

Accuracy Score

Precision, Recall, and F1-Score (Classification Report)

Recall and F1-Score were emphasized due to the imbalanced nature of the dataset.

🔑 Feature Importance

Feature importance was visualized using an interactive Plotly scatter plot

This helps identify key factors influencing employee attrition, such as:

Job Satisfaction

Years at Company

Work-Life Balance

Monthly Income

📊 Results

The Random Forest model achieved strong predictive performance

SMOTE significantly improved minority class prediction

Important HR factors affecting attrition were successfully identified
