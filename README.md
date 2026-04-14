# Heart Failure Prediction using ANN

## Overview
This project predicts the likelihood of heart failure using clinical data and an Artificial Neural Network (ANN).

## Dataset
- Heart Failure Clinical Records Dataset
- Includes features such as age, blood pressure, serum creatinine, diabetes, etc.
- link: https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data

## Approach
- Exploratory Data Analysis (EDA) to understand feature relationships
- Feature engineering:
  - Creatinine ratio
  - Risk score based on health conditions
- Data preprocessing:
  - Feature scaling (StandardScaler)
  - Stratified train-test split

## Model
- Artificial Neural Network (ANN) built using TensorFlow/Keras
- Includes dense layers and evaluation on validation data

## Evaluation
- Confusion Matrix
- Classification Report
- Accuracy & Validation metrics

## Results
- Model successfully predicts heart failure risk based on clinical features
- Demonstrates importance of feature engineering in healthcare datasets

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn

## Key Learnings
- Feature engineering improves model performance
- Importance of scaling for neural networks
- Handling imbalanced datasets in classification problems

