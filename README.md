# Credit Risk Prediction

Predicting whether a credit card client will default on their next payment 
using machine learning classification models.

## Dataset
UCI Default of Credit Card Clients 
Source: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients
Observations — 30,000
Features - 23 
Target Variable: Default payment (1 = default, 0 = no default)

## Models
- Logistic Regression
- Random Forest (base + hyperparameter tuned via GridSearchCV)

## Results
Best model: Tuned Random Forest — F1: 0.54, ROC-AUC: 0.77

## Tools
Python, scikit-learn, pandas, NumPy, matplotlib, seaborn, Google Colab

## How to Run
- Open the notebook in Google Colab
- Load the dataset using the provided UCI link
- Run all cells sequentially
