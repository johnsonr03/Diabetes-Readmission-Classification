# Diabetes Readmission Prediction

### Overview
This project aimed to predict 30 day readmission among patients with diabetes using Logistic Regression, Random Forest, and XGBoost models. Data preprocessing encompassed treating missing values, feature engineering, and one-hot encoding categorical features. Models were evaluated under three scenarios: with StandardScaler, with StandardScaler + SMOTE for class imbalance, and with hyperparameter tuning using RandomizedSearchCV. This prediction is critical for healthcare providers to intervene proactively, improve patient care, reduce hospital readmission rates, and achieve better health outcomes.

The project implements and compares three primary architectures:
Logistic Regression
Random Forest
XGBoost

### Objectives
Comprehensive Preprocessing: Handle missing values, perform feature engineering, and apply one-hot encoding.
Exploratory Data Analysis: Gain insights into patient demographics and clinical factors.
Model Benchmarking: Evaluate performance across three distinct models.
Optimisation: Improve model metrics through hyperparameter tuning.

### Notebook Structure
Data Loading
Data Analysis & Cleaning
Exploratory Data Analysis
Model Training & Testing: Evaluation is split into three core scenarios:
Scenario 1: Baseline models using StandardScaler.
Scenario 2: Addressing class imbalance using StandardScaler + SMOTE.
Scenario 3: Performance optimisation using RandomizedSearchCV.
Result Comparison: Final evaluation of metrics.

### Dataset Information
The dataset used in this project represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks.
Source: Clore, J., Cios, K., DeShazo, J., & Strack, B. (2014). Diabetes 130-US Hospitals for Years 1999-2008 [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5230J
