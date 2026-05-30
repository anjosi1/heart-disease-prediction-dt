# Heart Disease Prediction Using Machine Learning

## Project Overview

This project aims to predict the presence of heart disease in patients using machine learning techniques. The analysis includes data preprocessing, exploratory data analysis (EDA), model training, hyperparameter tuning, and performance evaluation.

## Problem Statement

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals take preventive measures and improve patient outcomes. This project develops a machine learning model to predict whether a patient is likely to have heart disease based on clinical attributes.

## Dataset

The dataset contains patient health information, including:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate Achieved
* Exercise Induced Angina
* Oldpeak
* ST Slope

Target Variable:

* 0 = No Heart Disease
* 1 = Heart Disease

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Methodology

### 1. Data Preprocessing

* Loaded the dataset
* Checked for missing values
* Performed data cleaning
* Split the dataset into training and testing sets

### 2. Exploratory Data Analysis

Several visualizations were created to understand:

* Feature distributions
* Correlations between variables
* Relationships between patient attributes and heart disease

### 3. Model Development

The following models were implemented:

* Decision Tree Classifier
* Logistic Regression

Hyperparameter tuning was performed using GridSearchCV to improve model performance.

### 4. Handling Class Imbalance

To reduce bias toward the majority class, class balancing techniques such as class weights or SMOTE were applied during model training.

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

These metrics are particularly important in medical applications where identifying patients with disease is critical.

## Key Findings

* Chest Pain Type was one of the most influential features.
* Maximum Heart Rate and Oldpeak significantly affected predictions.
* The optimized Decision Tree model showed strong predictive performance.
* ROC-AUC analysis demonstrated good discrimination capability.
* Recall was carefully evaluated because false negatives are critical in medical diagnosis.

## Results

The trained model successfully predicted heart disease using patient clinical information and achieved good classification performance based on multiple evaluation metrics.

## Future Improvements

* Random Forest Classifier
* XGBoost
* Cross-validation techniques
* Explainable AI methods such as SHAP and LIME
* Deployment as a web application

## Author

Anjo


