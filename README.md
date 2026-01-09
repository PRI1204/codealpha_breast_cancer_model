# CodeAlpha Disease Prediction from Medical Data
---

# 🩺 Breast Cancer Data Analysis & Exploration

## 📌 Project Overview
This project focuses on predicting whether a breast tumor is cancerous or non-cancerous using diagnostic features. 
By accurately classifying tumors at an early stage, the project helps doctors make better treatment decisions and improves patient care.

## 🎯 Objective
To build accurate machine learning classification model that distinguishes between tumor types using medical test data  and evaluates performance through statistical metrics.

## 📂 Dataset Information
- **Dataset Name:** `Breast Cancer Dataset`
- **Source:** `scikit-learn Dataset`
- **Total Records:** 569
- **Total Features:** 30 numerical features + 1 target column
- **Target Variable:**
  - `0` → Malignant
  - `1` → Benign
- **Key Features:**
  - Mean Radius, Texture, and Perimeter
  - Area and Smoothness
  - Concavity and Concave points
  - Symmetry and Fractal Dimension

## Technologies Used
- Programming Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 🔄 Project Workflow
1. Data Collection
2. Data Exploration
3. Data Cleaning
4. Data Preprocessing
5. Feature Selection
6. Train-Test Split
7. Model Training (Logistic Regression & Random Forest Classifier).
8. Model Prediction
9. Model Evaluation
10. Result Analysis

## 🤖 Machine Learning Model
**Logistic Regression & Random Forest:**
Logistic Regression was used as a high-performing baseline for binary classification, while Random Forest was implemented to capture complex feature interactions.

## 📊 Model Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score
- ROC-AUC Curve

## 📈 Results
- Logistic Regression achieved the highest accuracy outperforming Random Forest, making it an exceptionally strong model for this dataset.
- ROC–AUC analysis for both models showed near-perfect classification performance.
- The confusion matrix provided clear insights, showing that Logistic Regression produced fewer misclassifications.
- Logistic Regression is the better choice for this specific dataset due to its higher accuracy and simplicity.

The dataset is also exported as a CSV file:
```text
breast_cancer.csv
