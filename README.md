💡 Insurance Cost Prediction (Regression Project)
--Objective

The aim of this project is to predict individual medical insurance costs based on personal and lifestyle attributes using machine learning regression models.

--Dataset Information

Attributes:

age → Age of the individual

sex → Gender (male/female)

bmi → Body Mass Index (kg/m²)

children → Number of dependents

smoker → Smoking status (yes/no)

region → Residential area (northeast, northwest, southeast, southwest)

charges → Target variable (medical insurance cost)

--Approach

Data Cleaning & Preprocessing (encoding, scaling, outlier handling)

Exploratory Data Analysis (EDA): correlation heatmap, distributions, categorical analysis

Regression Models:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

XGBoost Regressor

Model Evaluation: MAE, MSE, RMSE, R²

--Results

Ensemble models (Random Forest, Gradient Boosting, XGBoost) gave better accuracy compared to simple regression methods.

Feature importance showed smoking status, BMI, and age as key drivers of insurance charges.
