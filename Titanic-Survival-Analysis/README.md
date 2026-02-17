# Titanic Survival Analysis

## Overview
This project performs exploratory data analysis (EDA) and machine learning modeling on the Titanic dataset to predict passenger survival. The objective is to identify key factors influencing survival and build predictive models using supervised learning techniques.
The project demonstrates the complete machine learning workflow including preprocessing, visualization, model training, and evaluation.

## Dataset
Source: Kaggle Titanic Dataset  
https://www.kaggle.com/c/titanic/data

## Tech Stack
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Key Techniques Used

### Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature engineering (Title extraction, FamilySize)
- Feature scaling

### Exploratory Data Analysis
- Survival distribution analysis
- Correlation analysis
- Visualization using Matplotlib and Seaborn

### Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

### Model Evaluation
- Train-validation split
- Accuracy score
- Confusion matrix
- Cross-validation

## Key Insights
1. Female passengers had higher survival rates.
2. First-class passengers were more likely to survive.
3. Age and fare influenced survival probability.
4. Random Forest achieved the best performance among tested models.

## Potential Extensions
- Implement XGBoost or LightGBM
- Build a Streamlit web app for predictions
- Perform hyperparameter tuning
- Apply ensemble learning techniques
- Create an interactive dashboard
- Deploy the model using Flask or FastAPI
- Experiment with neural networks
