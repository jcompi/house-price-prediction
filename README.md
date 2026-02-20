![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Regression](https://img.shields.io/badge/Type-Regression-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# House Price Prediction

## Overview
This project focuses on predicting house prices using regression models and regularization techniques.

The objective was to compare traditional Linear Regression with Ridge and Lasso models to evaluate the impact of regularization on performance and feature selection.

## Dataset
Kaggle - House Prices: Advanced Regression Techniques  
1460 samples with 81 original features.

## Data Processing
- Log transformation applied to target variable (SalePrice)
- Missing values handled using domain-based imputation
- One-hot encoding for categorical variables
- Feature scaling using StandardScaler

## Models Implemented
- Linear Regression
- Ridge Regression
- Lasso Regression

## Results
Linear Regression:
- R² ≈ 0.76

Ridge Regression:
- R² ≈ 0.78

Lasso Regression:
- R² ≈ 0.84
- Reduced features from 248 to 172

## Key Insights
Regularization significantly improved model performance and reduced overfitting.  
Lasso helped perform automatic feature selection while increasing predictive accuracy.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
