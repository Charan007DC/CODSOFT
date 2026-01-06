# CodSoft Machine Learning Internship

> **Internship Program** | December Batch B71  
> **Completed by**: Dhaksha Charan  
> **Duration**: 20 December 2025 – 20 January 2026  

This repository contains the complete implementation of **3 Machine Learning tasks** as part of the **CodSoft Internship Program**. All code is **100% original**, built from scratch for educational and demonstration purposes.

---

## ✅ Tasks Completed

| Task | Description | Algorithm Used |
|------|-------------|----------------|
| **1. Spam SMS Detection** | Classify SMS messages as **Spam** or **Ham** | Logistic Regression + TF-IDF |
| **2. Credit Card Fraud Detection** | Detect fraudulent transactions in imbalanced data | Random Forest + SMOTE |
| **3. Customer Churn Prediction** | Predict if a telecom customer will leave | XGBoost Classifier |

---

## 📂 Repository Structure
CODSOFT/
├── Task_1_Spam_SMS_Detection/
│ ├── spam_sms_detection.py
│ ├── model.pkl
│ ├── tfidf_vectorizer.pkl
│ └── confusion_matrix.png
│
├── Task_2_Credit_Card_Fraud_Detection/
│ ├── credit_card_fraud_detection.py
│ ├── model.pkl
│ ├── confusion_matrix_fraud.png
│ └── precision_recall_curve.png
│
├── Task_3_Customer_Churn_Prediction/
│ ├── customer_churn_prediction.py
│ ├── model.pkl
│ ├── confusion_matrix_churn.png
│ └── feature_importance.png
│
├── README.md
└── .gitignore

## 🚀 How to Run

1. **Download datasets** from Kaggle:
   - [SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
   - [Credit Card Fraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
   - [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
2. Place each `.csv` file in its respective task folder and **rename** as:
   - `spam.csv`
   - `creditcard.csv`
   - `churn.csv`
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
