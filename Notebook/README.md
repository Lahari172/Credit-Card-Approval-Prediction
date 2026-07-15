# Machine Learning Notebook

## Credit Card Approval Prediction System

### IBM SkillsBuild UE AICTE Internship – June 2026

---

## Overview

This notebook contains the complete implementation of the Credit Card Approval Prediction System. It covers the entire machine learning workflow, including data loading, preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and saving the best-performing model.

The notebook was developed using **Google Colab** and Python.

---

## Notebook Contents

### 1. Import Required Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

### 2. Dataset Loading
- application_record.csv
- credit_record.csv

### 3. Data Exploration
- Dataset overview
- Data types
- Missing values
- Duplicate records
- Statistical summary

### 4. Data Preprocessing
- Handling missing values
- Removing duplicates
- Creating the target variable
- Merging datasets
- Label encoding

### 5. Exploratory Data Analysis (EDA)
- Gender Distribution
- Income Distribution
- Education Level
- Housing Type
- Family Status
- Correlation Heatmap
- Target Variable Distribution

### 6. Machine Learning Models
The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

### 7. Model Evaluation
Each model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

### 8. Model Comparison
The performance of all models was compared to identify the best-performing algorithm.

### 9. Model Saving
The selected model was saved for deployment in the Flask web application.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Output

The notebook successfully predicts whether a credit card application is likely to be approved or rejected based on applicant information.

---

## Note

Open the notebook (`Credit_Card_Approval_Prediction.ipynb`) and run all cells sequentially to reproduce the results and generate the trained machine learning model.
