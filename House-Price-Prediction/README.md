# 🏠 House Price Prediction using Machine Learning 

## 📌 Overview

This project implements an end-to-end machine learning regression pipeline to predict house prices using the Ames Housing dataset.
It demonstrates the complete ML workflow, from data preprocessing and feature engineering to model training and evaluation.
The model predicts house prices (`SalePrice`) based on multiple structural and neighborhood-level features.

## 🎯 Objectives

* Perform exploratory data analysis (EDA)
* Handle missing values and skewed data
* Apply feature engineering
* Train regression models
* Evaluate performance using standard metrics
* Generate predictions for unseen data

## 📊 Dataset

House Prices — Advanced Regression Techniques (Kaggle)

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

Features include: Property size and living area, Number of rooms, Year built, Garage and basement details, Neighborhood information

Target Variable: SalePrice

## 🛠 Tech Stack

**Language**
* Python

**Libraries**
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

**Environment**
* Jupyter Notebook

## ⚙️ Workflow

* Load training and test datasets
* Perform exploratory data analysis (EDA)
* Apply log transformation to target variable
* Handle missing values
* Perform feature engineering
* Apply One-Hot Encoding to categorical variables
* Split dataset into train and validation sets
* Scale numerical features using StandardScaler
* Train Linear Regression and XGBoost Regressor
* Evaluate models using RMSE, MAE, and R²
* Generate predictions on test data

## 🤖 Models Used

#### * Linear Regression
Baseline regression model used for comparison.

#### * XGBoost Regressor
Gradient boosting model capable of capturing complex feature relationships and improving prediction accuracy.

## 📈 Results

The XGBoost model outperformed Linear Regression, achieving lower prediction error and better generalization.

Evaluation Metrics
* RMSE
* MAE
* R² Score

## 🚀 Future Improvements

* Hyperparameter tuning
* Cross-validation pipeline
* Ensemble learning methods
* Model deployment with Streamlit
* Feature importance visualization
* Automated feature selection
