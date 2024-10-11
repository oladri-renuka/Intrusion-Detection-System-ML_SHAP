# Intrusion Detection System using Machine Learning and SHAP (XAI)

## Task Overview
This project implements an Intrusion Detection System (IDS) using machine learning and intrepreting the model with explainable AI (SHAP). The primary goal is to classify network traffic into normal and attack.

## Data Preprocessing Steps
1. **Data Loading**: The dataset is loaded from CSV files.
2. **Column Renaming**: Columns in both training and test datasets are renamed for better readability.
3.**Data Inspection**: Basic statistics and data types are inspected to understand the dataset's structure.
4.**Handling Missing Values**: Checked for missing values across all columns.
## Model training and evaluation
## Logistic Regression
  - **Training Accuracy:** 96.75%  
  - **Test Accuracy:** 96.54%  
  - **Training Precision:** 96.88%  
  - **Test Precision:** 96.52%  
  - **Training Recall:** 96.10%  
  - **Test Recall:** 96.08%  

## K-Nearest Neighbors (KNN)
  - **Training Accuracy:** 99.45%  
  - **Test Accuracy:** 99.23%  
  - **Training Precision:** 99.50%  
  - **Test Precision:** 99.21%  
  - **Training Recall:** 99.31%  
  - **Test Recall:** 99.14%  

## Naive Bayes
  - **Training Accuracy:** 91.80%  
  - **Test Accuracy:** 91.61%  
- **Training Precision:** 92.63%  
  - **Test Precision:** 92.53%  
  - **Training Recall:** 89.48%  
  - **Test Recall:** 89.30%  

## Decision Tree
  - **Training Accuracy:** 99.99%  
  - **Test Accuracy:** 99.87%  
  - **Training Precision:** 100.00%  
  - **Test Precision:** 99.86%  
  - **Training Recall:** 99.99%  
  - **Test Recall:** 99.85%  

## Random Forest
  - **Training Accuracy:** 99.99%  
  - **Test Accuracy:** 99.89%  
  - **Training Precision:** 100.00%  
  - **Test Precision:** 99.97%  
  - **Training Recall:** 99.99%  
  - **Test Recall:** 99.80%  

## AdaBoost
  - **Training Accuracy:** 99.22%  
  - **Test Accuracy:** 99.17%  
  - **Training Precision:** 99.27%  
  - **Test Precision:** 99.17%  
  - **Training Recall:** 99.04%  
  - **Test Recall:** 99.05%  

## Gradient Boost
  - **Training Accuracy:** 99.59%  
  - **Test Accuracy:** 99.51%  
  - **Training Precision:** 99.59%  
  - **Test Precision:** 99.58%  
  - **Training Recall:** 99.53%  
  - **Test Recall:** 99.37%  

## XGBoost
  - **Training Accuracy:** 99.99%  
  - **Test Accuracy:** 99.91%  
  - **Training Precision:** 99.98%  
  - **Test Precision:** 99.93%  
  - **Training Recall:** 99.99%  
  - **Test Recall:** 99.87%  

## MLP Classifier
  - **Training Accuracy:** 98.69%  
  - **Test Accuracy:** 98.53%  
  - **Training Precision:** 97.61%  
  - **Test Precision:** 97.39%  
  - **Training Recall:** 99.61%  
  - **Test Recall:** 99.53%  
## Explainable AI:
Included SHAP for the XGBoost model as it performed best on the dataset.
