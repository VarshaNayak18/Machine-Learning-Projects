# Heart Disease Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-orange?logo=scikit-learn)

## Overview

AI in Healthcare: Building a Life-Saving Heart Disease Predictor

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

## Project Structure

```
04-heart-disease-prediction/
│── heart-disease-dataset.csv
│── heart-disease-prediction.ipynb
│── README.md
└── requirements.txt
```

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Core Concepts

1. Classification Fundamentals: Understanding the goal of predicting a discrete category.
2. Exploratory Data Analysis (EDA) for Classification: Analyzing features to find patterns that distinguish between classes.
3. Data Preprocessing: Preparing data for classification models using encoding and feature scaling.
4. Model Building: Training and comparing a simple baseline model (Logistic Regression) with an advanced ensemble model (Random Forest).
5. Model Evaluation: Mastering key classification metrics like Accuracy, Precision, Recall, F1-Score, and interpreting the Confusion Matrix.
6. Feature Importance: Identifying the most influential medical factors for predicting heart disease.

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

## How to Run

1. Clone the Repository

   git clone https://github.com/VarshaNayak18/Machine-Learning-Projects.git
   
   cd Machine-Learning-Projects/04-heart-disease-prediction

2. Install Dependencies

   pip install -r requirements.txt

3. Run the Notebook

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature selection
- Model deployment using Streamlit
- Adding pipeline-based preprocessing
- Comparing more classification models