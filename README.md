# Insurance Fraud Detection

## Project Overview
This project applies machine learning techniques to identify potentially fraudulent insurance claims.

The goal is to compare different classification models and evaluate their ability to distinguish fraudulent from non-fraudulent claims.

## Dataset
The dataset contains approximately 1,000 insurance claim records, including information related to policyholders, incidents, vehicles, and claim amounts.

## Feature Engineering
Feature engineering was performed to improve model performance and interpretability, including:

- Date-related features
- Vehicle age
- Claim amount levels
- Total claim level
- Policy-related variables
- Capital gains and losses
- Umbrella limit
- Policy CSL

## Models
The following classification models were implemented and compared:

- Logistic Regression
- Neural Network
- XGBoost

## Model Evaluation
Model performance was evaluated using:

- ROC Curve
- AUC
- Confusion Matrix

## Results
Among the evaluated models, XGBoost achieved the best overall performance.

- XGBoost Test AUC: approximately **0.80**

The results suggest that machine learning methods can help identify high-risk insurance claims and support fraud risk assessment.

## Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- Matplotlib

## Project Workflow

Data Cleaning  
↓  
Exploratory Data Analysis  
↓  
Feature Engineering  
↓  
Model Training  
↓  
Model Evaluation  
↓  
Fraud Risk Prediction

## report

[View Project Presentation (Google Drive)](https://drive.google.com/drive/folders/1e2gyoXksmHRmHXMLxsI5RoBslCYfXxAh?dmr=1&ec=wgc-drive-hero-goto)
