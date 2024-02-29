# Online News Popularity Prediction

## Introduction

This project aims to predict online news popularity using the dataset from the UCI Machine Learning Repository. The dataset includes 39644 articles with 61 attributes, and the target is to predict the number of shares in binary classes.

## Exploratory Data Analysis (EDA)

Correlation analysis was performed to reduce multicollinearity, keeping features with significant relationships. The EDA revealed no strong correlation between features and the target variable.

## Methods

The dataset was preprocessed by dropping non-predictive features and applying stratified sampling. A function was developed to handle preprocessing, model fitting, and cross-validation using KFold, GridSearchCV, and various scaling techniques.

## Models Used

- Logistic Regression
- Random Forest
- KNN
- SVC
- XGBoost

The best-performing model, XGBoost, achieved an accuracy of 64.43% with standardized hyperparameters.

## Results

The models surpassed a 50% baseline score, with XGBoost having the highest accuracy and an analysis of feature importance conducted using multiple methods.

## Outlook

Future improvements include utilizing the full dataset and improving feature selection, potentially increasing accuracy beyond the current 70% ceiling.

## References

- UCI Machine Learning Repository
- Other related works on Kaggle and GitHub
