# Heart-Disease-Prediction

## Overview

This project builds a machine learning workflow to predict heart disease using structured clinical data.
The pipeline includes data cleaning, missing value handling, feature encoding, feature scaling, and model training using classification algorithms.
The goal is to demonstrate a complete preprocessing + modeling workflow using scikit-learn.

## Objectives

- Handle missing values in categorical and numerical features
- Encode categorical variables using OneHotEncoder
- Standardize numerical features using StandardScaler
- Train classification models
- Evaluate model performance
- Compare models trained with and without structured preprocessing

## Dataset

Heart Disease Dataset (Kaggle):
https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

## Workflow

- Data Cleaning:
  Identified categorical and numerical columns
  Filled missing values: Numerical features → mean and Categorical features → mode

- Feature Encoding:
  Categorical features were converted to numeric format using OneHotEncoder.

- Feature Scaling:
  Numerical features were standardized using StandardScaler.

- Model Training:
  Using Logistic Regression and Random Forest

- Model Evaluation:
  Metrics used: Accuracy, Precision, Recall, F1-score, Confusion Matrix

## Models Used
- Logistic Regression
- Random Forest Classifier

## Results

- Both models successfully trained on the processed dataset.
- Logistic Regression performed well on scaled features.
- Random Forest handled feature interactions effectively without requiring scaling.
- Preprocessing ensured no missing values and consistent feature representation.

## Key Insights

- Handling missing values before encoding is essential.
- OneHotEncoding ensures categorical features are usable by ML models.
- StandardScaler improves performance for linear models.
- Random Forest is robust to feature scaling.
- Structured preprocessing improves reproducibility.

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature selection
- Model deployment using Streamlit
- Adding pipeline-based preprocessing

Comparing more classification models
