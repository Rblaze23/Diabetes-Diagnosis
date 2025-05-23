# Diabetes-Diagnosis
Project Name: Diabetes Diagnosis Author: [Your Name] Date: [Insert Date] Description: This project predicts whether a patient has diabetes based on medical features using machine learning techniques.

1. Dataset
The dataset contains the following features:

Glucose Level

Blood Pressure

Insulin Level

Body Mass Index (BMI)

Age

Lifestyle: Activity level (Sedentary, Moderate, Active)

Diabetes Diagnosis: Target variable (1 = diabetic, 0 = non-diabetic)

2. Data Preprocessing
Handling Missing Values: Replace missing values with median for numerical features

Feature Scaling: Standardization using StandardScaler

Encoding Categorical Variables: Converting activity level to numerical representation

Balancing Classes: Using SMOTE to handle class imbalance

3. Model Training
The following models are tested:

Logistic Regression

Decision Tree Classifier

Random Forest

XGBoost

Neural Networks

4. Evaluation Metrics
Accuracy

Precision-Recall Curve

ROC AUC Score

F1 Score

5. Usage Guide
To run the prediction model, follow these steps:
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow xgboost lime shap
import pandas as pd
df = pd.read_excel('diabetes_diagnosis.xlsx')#you can bring your own data to test my work :) 
