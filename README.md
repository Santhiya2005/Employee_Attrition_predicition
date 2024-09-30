# Employee Attrition Prediction System

### Name: Santhiya E  
### Date: 30.9.2024  
### College: Kongu Engineering College  
### Course: Machine Learning Assignment 2  

## Project Title
Employee Attrition Prediction System

## Description
This project aims to develop a machine learning model that predicts whether an employee will leave a corporate organization based on various job-related and personal factors. The prediction will help the organization identify employees at risk of leaving and implement targeted retention strategies.

## Objective
The objective is to build a predictive model that classifies employees into two categories:
- **Attrition (Yes)**: Employee is predicted to leave the organization.
- **Attrition (No)**: Employee is predicted to stay.

The model will be evaluated using relevant metrics such as accuracy, precision, recall, and F1-score. Additionally, insights will be provided into the key factors that contribute to employee attrition.

## Dataset Description
The dataset contains the following features:
- **EmployeeID**: Unique identifier for each employee.
- **Age**: Age of the employee.
- **Gender**: Gender of the employee (Male/Female).
- **MaritalStatus**: Marital status of the employee (Single, Married, Divorced).
- **Education**: Level of education (High School, Bachelor, Master, PhD).
- **Department**: Department where the employee works (HR, IT, Finance, Sales).
- **JobRole**: Specific job role of the employee (Manager, Analyst, Developer).
- **YearsAtCompany**: Number of years the employee has been with the company.
- **YearsInCurrentRole**: Number of years the employee has been in their current role.
- **MonthlyIncome**: Monthly income of the employee.
- **JobSatisfaction**: Job satisfaction level on a scale of 1-5.
- **WorkLifeBalance**: Work-life balance on a scale of 1-5.
- **TrainingTimesLastYear**: Number of training sessions the employee attended last year.
- **OverTime**: Whether the employee works overtime frequently (Yes/No).
- **DistanceFromHome**: Distance from the employee’s home to the workplace (in miles).
- **Attrition**: Whether the employee has left the company (Yes/No) - Target variable.

## Key Design Decisions
### 1. Training and Test Data Split
- **Split Ratio**: 80% training data and 20% test data.
- **Justification**: Sufficient data for training while evaluating model performance on unseen data.

### 2. Outlier Removal
- Outliers in continuous features (e.g., "MonthlyIncome" and "YearsAtCompany") will be detected and removed using the Interquartile Range (IQR) method.

### 3. Machine Learning Algorithms
- **Logistic Regression**: Baseline model for binary classification.
- **Decision Trees**: Non-linear model suitable for both numerical and categorical data.
- **Random Forest**: Ensemble method to improve predictions by aggregating outputs.
- **Gradient Boosting (XGBoost)**: High-accuracy model suitable for structured data.

### 4. Data Preprocessing
- **Handling Categorical Variables**: One-hot encoding for categorical features.
- **Standardizing Continuous Features**: StandardScaler for continuous variables.
- **Dimensionality Reduction**: PCA for reducing correlated features if necessary.

## Model Evaluation Metrics
- **Accuracy**: Proportion of correctly classified instances.
- **Precision**: Proportion of predicted "Yes" that were correct.
- **Recall**: Proportion of actual "Yes" identified correctly.
- **F1-Score**: Harmonic mean of precision and recall.

## Model Versioning
Each trained model will be versioned as follows:
- **v1.0**: Logistic Regression baseline model.
- **v1.1**: Decision Tree with hyperparameter tuning.
- **v2.0**: Random Forest with feature importance analysis.
- **v2.1**: Gradient Boosting (XGBoost) with fine-tuning.

## Dimensionality Reduction and Feature Engineering
- **Feature Selection**: Importance from Random Forest will identify key features affecting attrition.
- **PCA**: Reduces dimensionality while retaining significant variance.

## Conclusion
This document outlines the design and technical approach for the Employee Attrition Prediction system. The combination of multiple machine learning algorithms, rigorous preprocessing, and model evaluation ensures the creation of a robust predictive system. Feature importance analysis will offer valuable insights into factors contributing to employee attrition, enabling organizations to take data-driven actions to retain their workforce.

## Installation
Instructions for installing necessary packages can be added here.

## Usage
Instructions for how to use the model can be added here.
## Accuracy 
![image](https://github.com/user-attachments/assets/5dcd6221-d492-48ac-89fb-93e5a3eb22c5)
## Model Comparsion
![image](https://github.com/user-attachments/assets/ef9fb9e1-ec7e-4fc5-bb7e-a537f173e2f4)
## Feature Importance
![image](https://github.com/user-attachments/assets/feb64e9b-1175-479b-bd80-03354817c47b)
## Output
![image](https://github.com/user-attachments/assets/4196bd1b-9d23-455f-9e7c-9a13786e7bcd)
![image](https://github.com/user-attachments/assets/15fcfb9f-5ee8-49a8-bfd3-3d21698e7b2e)




