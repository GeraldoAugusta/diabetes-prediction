### Machine Learning Portfolio Project  
**Author:** Geraldo Augusta
**Email:** geraldonyoman14@gmail.com  
**LinkedIn:** https://linkedin.com/in/geraldoaugusta  
**GitHub:** https://github.com/geraldoaugusta  

# Diabetes Prediction – Machine Learning Classification

## Overview
This project aims to predict whether a patient has diabetes based on medical measurements using machine learning classification models.  
It demonstrates a complete workflow from exploratory data analysis (EDA), preprocessing, modeling, to evaluation and visualization.

## Dataset
- Source: [Diabetes Data Set – Kaggle](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)
- Features:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- Target: `Outcome` (0 = No Diabetes, 1 = Diabetes)

## Preprocessing
- Handle missing or zero values in features where appropriate (e.g., BMI, Glucose, BloodPressure)  
- Standardize features for models like Logistic Regression  
- Train-test split (80:20)

## Modeling
- Logistic Regression (baseline)  
- Random Forest Classifier (main model)  
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC

## Evaluation & Visualization
- Confusion Matrix  
- ROC Curve  
- Feature Importance (Random Forest)

## Insights
- Random Forest usually outperforms Logistic Regression for non-linear patterns.  
- Features like **Glucose** and **BMI** are typically the most important predictors.  
- This project demonstrates a full classification workflow suitable for a Data Science portfolio.
