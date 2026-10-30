# Cost-Sensitive Machine Learning for Patient No-Show Prediction

## Overview
This repository contains the Jupyter Notebook developed for the research project *A Cost-Sensitive Machine Learning Decision Framework for Predicting Patient No-Shows in South African Healthcare*.

The study evaluates machine learning models for predicting patient appointment non-attendance and explores how prediction probabilities can inform cost-sensitive intervention decisions.

## Methodology
The notebook covers:
- Data preprocessing and exploratory data analysis.
- Machine learning models: Logistic Regression, Random Forest and XGBoost.
- Class imbalance handling using baseline modelling, SMOTE and Random Undersampling.
- Model evaluation using precision, recall, F1-score and ROC-AUC.
- Cost-sensitive decision analysis using simulated intervention costs and effectiveness assumptions.

## Dataset
The study uses the publicly available **Medical Appointment No Shows** dataset from Kaggle. The dataset represents appointments in Brazil; therefore, the findings should not be interpreted as direct evidence of performance in South African healthcare settings.

**Kaggle Dataset Link:** https://www.kaggle.com/datasets/joniarroba/noshowappointments

## Reproducibility
The notebook can be opened in Google Colab or run in a compatible Jupyter environment. Required Python libraries and any setup instructions are documented in the notebook.

## Disclaimer
The cost-sensitive analysis uses simulated scenarios and assumed cost parameters. The estimated costs and potential savings do not represent validated real-world outcomes.
