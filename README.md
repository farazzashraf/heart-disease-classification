# Predicting Heart Disease Using Machine Learning

## Overview
This project aims to predict whether a patient has heart disease based on clinical parameters. Various machine learning models were tested and evaluated to achieve high accuracy.

## Dataset
The dataset contains clinical features such as age, sex, chest pain type, blood pressure, cholesterol levels, and other heart-related parameters.

## Problem Statement
Given clinical data about a patient, can we accurately predict if they have heart disease?

## Data Preprocessing
To prepare the data for modeling, the following steps were performed:
- Handled missing values
- Standardized numerical features using `StandardScaler`
- Categorical variables were encoded appropriately
- Data was split into training and test sets using `train_test_split`

## Models Used
The following models were trained and compared:
- Logistic Regression - `0.88`
- K-Nearest Neighbors (KNN) - `0.68`
- Random Forest Classifier - `0.83`

## Model Evaluation
The models were evaluated using accuracy and cross-validation techniques:
- **Logistic Regression Accuracy:** Extracted from `model_scores` 
- **Random Forest Accuracy:** Extracted from `rs_rf.score(x_test, y_test)`
- **Cross-validated Accuracy:** Extracted using `cross_val_score`

## Results
A comparison of the models was visualized using a bar chart. The final selected model `LogisticRegression` achieved a high accuracy in predicting heart disease, making it a reliable solution.

## Conclusion
This project successfully demonstrated that machine learning can be used to predict heart disease based on clinical parameters. Future improvements can include hyperparameter tuning and testing deep learning models.

