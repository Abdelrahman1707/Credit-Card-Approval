# Credit Risk Prediction using Machine Learning

This project builds a machine learning model to classify credit card applicants as either 'good' or 'bad' clients based on their application and credit history data. The goal is to assist financial institutions in making informed credit approval decisions.

## 🔍 Overview

- **Data**: Merged from two CSV files — `application_record.csv` and `credit_record.csv` — using client `ID`.
- **Objective**: Predict creditworthiness without explicit labels, using **vintage analysis** to define target classes.
- **Problem**: Highly imbalanced data with a need for robust preprocessing and classification.

## 🛠️ Key Techniques

- Data cleaning, handling duplicates, and feature engineering
- Label encoding, feature scaling with `StandardScaler`
- Class imbalance handling using **SMOTE**
- Model training with **Random Forest Classifier**
- Performance evaluation using metrics like accuracy and F1-score

## 📁 Dataset Features

- **Application Record**: Demographics, income, employment, and housing info
- **Credit Record**: Historical monthly status of credit behavior (on-time, overdue, paid, etc.)

## ⚠️ Note

The dataset source is unknown and is used strictly for educational and research purposes.

---

> Related Topics: Credit Scoring, Risk Modeling, Imbalanced Classification, Binary Classification
