# Smoking-prediction
Description
This project focuses on predicting if a person smokes or not based on various health factors. Using a dataset comprising medical records and lifestyle information, we aim to predict outcomes such as smoking status, potential for heart disease, or diabetes risk. The goal is to provide insights that can assist healthcare professionals in identifying at-risk individuals and improving patient care through preventative measures.

Dataset
The dataset includes anonymized patient records with features such as age, weight, blood pressure, cholesterol levels, and lifestyle factors like physical activity and smoking status. Preprocessing steps involved cleaning missing values, encoding categorical variables, and normalizing numerical features for consistent model input.

Features and Engineering
We applied several feature engineering techniques to enhance model performance:

Feature Selection: Used methods like correlation to identify and retain the most informative features.
Feature Creation: Developed new features, such as Body Mass Index (BMI) from height and weight data, to provide additional insights into patient health.
Normalization and Scaling: Applied standard scaling to numerical features to reduce model sensitivity to feature magnitude.
Models and Algorithms
We experimented with various machine learning models, including:

Logistic Regression as a baseline for comparison.
Random Forest and Gradient Boosting Machines for their ability to handle nonlinear relationships and feature interactions.
The final model selection was based on a combination of performance metrics and interpretability.
Hyperparameter Tuning and Validation
Hyperparameter optimization was conducted using grid search and cross-validation techniques to find the optimal settings for each model. Model performance was evaluated using metrics such as accuracy, precision, recall, and the area under the ROC curve (AUC).
