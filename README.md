# 💳 Fraud Detection System using Machine Learning

## 🔍 Overview
This project focuses on detecting fraudulent financial transactions using Machine Learning techniques. It uses classification models and anomaly detection to identify suspicious transactions in highly imbalanced datasets.

---

## 🚀 Features
- Multiple ML Models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
- Anomaly Detection using Isolation Forest
- Feature Engineering and Data Preprocessing
- Handling Imbalanced Data using SMOTE
- Real-time Fraud Detection (Streamlit App)
- Data Visualization and Model Evaluation

---

## 📊 Dataset
- Credit Card Fraud Detection Dataset
- Contains anonymized features (V1–V28), Amount, and Class
- Highly imbalanced dataset

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Streamlit
- Matplotlib, Seaborn

---

## 🧠 Machine Learning Models
| Model               | Description |
|--------------------|------------|
| Logistic Regression | Baseline classification model |
| Decision Tree       | Rule-based classification |
| Random Forest       | Ensemble model (best performance) |
| XGBoost             | Advanced boosting algorithm |

---

## 🚨 Anomaly Detection
- Isolation Forest is used to detect unusual patterns in transactions
- Helps identify fraud cases without labeled data

---

## ⚖️ Handling Imbalanced Data
- SMOTE (Synthetic Minority Oversampling Technique)
- Balances fraud and non-fraud transactions

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall (Most Important for Fraud Detection)
- F1-score
- ROC-AUC Score

---

## ⚡ Real-Time Prediction
The project includes a Streamlit web app where users can:
- Input transaction details
- Get instant prediction (Fraud / Legit)

---

## 🏗️ Scalability
The system is designed to scale using:
- Distributed processing frameworks (Apache Spark)
- Real-time streaming tools (Kafka)

---

## 📂 Project Structure
