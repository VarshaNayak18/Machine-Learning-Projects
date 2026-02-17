# House Price Prediction using Machine Learning

## Overview

This project builds a machine learning model to predict house prices using the **Ames Housing dataset**.
It demonstrates a complete end-to-end ML workflow including **data preprocessing, feature engineering, model training, and evaluation**.

The goal of this project is to understand how different housing features influence sale price and to build accurate regression models.

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Correlation analysis
* Missing value inspection
* Feature relationship visualization
* Heatmaps using Seaborn

### 2. Data Preprocessing

* Handling missing values
* Neighborhood-based imputation
* Numerical imputation using zero where appropriate
* One-hot encoding for categorical variables
* Feature scaling using `StandardScaler`

### 3. Feature Engineering

Examples:

* `TotalBath` = combined full and half bathrooms
* Correlation-based feature selection

### 4. Model Training

Models used:

* Linear Regression (baseline model)
* XGBoost Regressor

Training strategy:

* Train-validation split using `train_test_split`
* Model fitting on training data
* Validation performance evaluation

### 5. Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## Results

The project compares baseline regression with gradient boosting methods to improve prediction accuracy.
Feature engineering and proper handling of missing values significantly improve model performance.

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Feature importance visualization
* Model deployment with Streamlit
* Pipeline automation using `sklearn.pipeline`
