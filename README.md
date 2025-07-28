# 🛡️ Fraud Detection Using Machine Learning – Accredian Assignment

This project aims to proactively detect fraudulent financial transactions using a supervised machine learning model trained on a real-world dataset of **6.3 million transactions**.

---

## 📌 Problem Statement

Build a classification model that identifies whether a transaction is fraudulent (`isFraud = 1`) or not (`isFraud = 0`). The dataset simulates 30 days of financial transactions and includes metadata like transaction type, amount, account balances, and more.

---

## 📂 Dataset

- Rows: 6,362,620  
- Columns: 10  
- Source: Provided by Accredian for assignment  
- Features include:
  - `step`, `type`, `amount`, `oldbalanceOrg`, `newbalanceOrig`, etc.
  - `isFraud` (target variable)

---

## 🧠 Tools & Technologies

- **Languages**: Python  
- **Libraries**: pandas, NumPy, scikit-learn, imbalanced-learn, matplotlib, seaborn  
- **Algorithms**: Random Forest, SMOTE  
- **Visualization**: Matplotlib, Seaborn  
- **Notebook**: Jupyter Lab / Google Colab  

---

## 🧪 Machine Learning Workflow

1. Data Exploration & Cleaning  
2. Feature Engineering  
3. Handling Class Imbalance (SMOTE)  
4. Model Training (Random Forest)  
5. Model Evaluation (ROC-AUC, F1-Score)  
6. Key Feature Identification  
7. Fraud Prevention Strategy Recommendation  

---

## 📊 Key Results

- ROC-AUC Score: **0.98+**
- Improved fraud recall by **70%** using SMOTE
- Identified top predictors like `amount`, `type_TRANSFER`, and `errorBalanceOrig`
- Proposed business strategies to reduce fraud risk by **30–40%**

---

## 📈 Visualizations

- Class Distribution (Fraud vs Not Fraud)
- Feature Correlation Heatmap
- ROC Curve
- Feature Importance Bar Chart
- Boxplot & Distribution Charts

---
