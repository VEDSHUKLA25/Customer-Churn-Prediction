# Customer Churn Prediction 🚀

![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.26-orange?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Overview
This project predicts whether a customer will leave a company (churn) based on account and service usage data. It helps businesses identify potential churners and take proactive steps to retain them.

## Dataset
The dataset is from [Kaggle – Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn). It contains:
- Customer demographics (`gender`, `SeniorCitizen`, `Partner`, `Dependents`)
- Account information (`tenure`, `Contract`, `PaymentMethod`)
- Service usage (`PhoneService`, `InternetService`, `OnlineSecurity`, etc.)
- Charges (`MonthlyCharges`, `TotalCharges`)
- Target variable: `Churn` (Yes/No)

## Tools & Libraries
- Python: `pandas`, `numpy`
- Machine Learning: `scikit-learn` (Random Forest)
- Imbalanced Data Handling: `imbalanced-learn` (SMOTE)
- Visualization: `matplotlib`, `seaborn`

## Project Workflow
1. Load and explore the dataset
2. Data cleaning and preprocessing
3. Encode categorical variables
4. Split data into training and testing sets
5. Handle class imbalance using SMOTE
6. Train a Random Forest classifier
7. Evaluate model performance (accuracy, precision, recall, ROC-AUC)
8. Visualize feature importance

## Results
- Achieved ROC-AUC Score: **0.8227**
- Top features influencing churn identified
- Confusion matrix and ROC-AUC used for model evaluation

## Future Improvements
- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Deploy the model as a web app or dashboard for real-time predictions
- Experiment with other algorithms like XGBoost or Gradient Boosting for comparison
