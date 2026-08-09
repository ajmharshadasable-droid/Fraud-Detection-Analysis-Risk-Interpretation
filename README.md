# Fraud Detection Analysis & Risk Interpretation

## 📌 Project Overview

Fraudulent transactions are difficult to identify because financial datasets contain a very large number of legitimate transactions and comparatively fewer fraudulent transactions.

This project focuses on analyzing credit card transaction data, identifying fraud patterns, handling imbalanced data, building machine learning models, and interpreting transaction risk for financial risk teams.

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA) on credit card transactions
* Identify important indicators of fraudulent transactions
* Handle highly imbalanced transaction data
* Build classification models for fraud detection
* Apply anomaly detection techniques
* Evaluate and compare model performance
* Assign risk levels based on fraud probability
* Provide insights useful for financial risk analysis

## 📊 Dataset

Dataset: Credit Card Fraud Detection Dataset
The dataset is not included in this repository due to its large file size. It can be downloaded from Kaggle.

The dataset contains **284,807 transactions** with 31 columns, including transaction time, anonymized features (V1–V28), transaction amount, and the target class.

### Target Variable

* `Class = 0` → Legitimate Transaction
* `Class = 1` → Fraudulent Transaction

The dataset is highly imbalanced, with **284,315 legitimate transactions and 492 fraudulent transactions**.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🔍 Project Workflow

1. Problem Understanding
2. Data Collection
3. Data Preprocessing
4. Exploratory Data Analysis
5. Handling Imbalanced Data
6. Model Building
7. Model Evaluation
8. Risk Interpretation
9. Anomaly Detection
10. Final Analysis

## 📈 Exploratory Data Analysis

The project performs analysis of:

* Fraud vs legitimate transactions
* Transaction amount distribution
* Transaction time patterns
* Feature relationships
* Fraud indicators
* Outliers and extreme transaction values

Transaction amount was considered as one of the factors for fraud risk analysis because the analysis showed differences between legitimate and fraudulent transactions and the presence of extreme values.

## ⚖️ Handling Imbalanced Data

Since fraudulent transactions represent a very small portion of the dataset, class imbalance is handled using **SMOTE (Synthetic Minority Oversampling Technique)** to create a more balanced training dataset.

## 🤖 Machine Learning Models

### 1. Logistic Regression

Logistic Regression is used as a classification model to predict whether a transaction is legitimate or fraudulent.

### 2. Random Forest

Random Forest is used as another classification approach for detecting fraudulent transactions. The project compares its performance with Logistic Regression.

### 3. Isolation Forest

Isolation Forest is used for **anomaly detection** to identify unusual transactions that may indicate fraudulent activity.

## 📊 Model Evaluation

The classification models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC

The project includes a model comparison using Precision, Recall and F1-Score.

### ROC-AUC Analysis

ROC-AUC is used to measure how effectively Logistic Regression and Random Forest distinguish fraudulent transactions from legitimate transactions.

## 🔐 Risk Interpretation

The project converts predicted fraud probabilities into three risk categories:

* **Low Risk:** Fraud probability below 0.30
* **Medium Risk:** Fraud probability from 0.30 to 0.70
* **High Risk:** Fraud probability above 0.70

High-risk transactions can be prioritized for further investigation by a risk team.

## 🌲 Anomaly Detection

Isolation Forest identifies unusual transactions as potential anomalies. These detected anomalies are compared with actual fraud transactions to understand their usefulness in fraud analysis.

## 📌 Feature Importance

Random Forest feature importance is used to identify the features that contribute most to fraud prediction. The project visualizes the **Top 10 Important Features**.

## 📷 Project Screenshots

Add screenshots of:

* Dataset / Data Preview
* Fraud vs Legitimate Distribution
* EDA Graphs
* SMOTE / Balanced Data
* Logistic Regression Confusion Matrix
* Random Forest Confusion Matrix
* Model Comparison Graph
* ROC Curve
* Feature Importance
* Risk Level Analysis
* Isolation Forest Results
* Project Workflow

## ✅ Outcome

This project demonstrates the use of data science and machine learning techniques for financial fraud detection and risk analysis.

The final analysis provides:

* Fraud detection models
* Model performance comparison
* Fraud probability-based risk levels
* Important fraud-related features
* Anomaly detection results
* Actionable insights for financial risk teams

## 👩‍💻 Author

**Harshada Sable**

B.E. Information Technology

## 📚 Project Type

**Major Project – Fraud Detection Analysis & Risk Interpretation**

### Key Skills Demonstrated

`Python` `Pandas` `EDA` `Machine Learning` `Classification` `SMOTE` `Random Forest` `Logistic Regression` `Anomaly Detection` `Isolation Forest` `Data Visualization` `Risk Analysis`
