# Kaggle Machine Learning Projects

This repository contains my machine learning projects from Kaggle competitions, focusing on prediction tasks using various algorithms and data analysis techniques.

## Projects Overview

### 1. House Price Prediction
**File:** `house-prices-attempt-2 (1).ipynb`

A regression model that predicts house prices based on various features such as location, size, amenities, and more. This project demonstrates techniques for:
- Data cleaning and preprocessing
- Feature engineering and selection
- Implementation of regression algorithms
- Model evaluation and hyperparameter tuning

- Results:
- Validation MAE: 15150.61
- Validation RMSLE: 0.122890

### 2. Spaceship Titanic Survival Prediction
**File:** `spaceship-titanic-xgboost-pipeline (1).ipynb`

A classification model that predicts passenger survival on the Spaceship Titanic. This project showcases:
- Advanced data preprocessing techniques
- XGBoost implementation in a machine learning pipeline
- Classification performance evaluation
- Feature importance analysis

- Results:
- Accuracy: 0.826 (82.6%)
- Precision/Recall:
  False class: 0.83/0.82
  True class: 0.82/0.83

 ### 3. Otto Group Product Classification (Multi-class Classification)
**File:** `stratk-fold-otto-classification.ipynb`  
**Competition:** [Otto Group Product Classification Challenge](https://www.kaggle.com/c/otto-group-product-classification-challenge)

A multi-class classification problem focused on predicting the correct product category.

#### 🛠 Techniques Used:

-XGBoost Classifier as the model
-Stratified K-Fold Cross-Validation to ensure balanced class splits
-Label Encoding for target classes
-Standard Scaler for feature normalization
-Log Loss as the evaluation metric


- Results:
- OOF Log Loss: `0.4676` 

## Getting Started

### Prerequisites
- Python 3.11+
- Jupyter Notebook
- Libraries: 
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - category_encoders

### Installation
```bash
pip install pandas numpy scikit-learn xgboost category_encoders
