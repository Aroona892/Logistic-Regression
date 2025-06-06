# 🔍 Logistic Regression for Bank Churn Prediction

This project implements logistic regression to predict **customer churn** from a banking dataset. It includes both a **scikit-learn** model and a **manual logistic regression** with NumPy.

---

## 🧠 Key Features

- 📥 Loads `Bank Customer Churn Prediction.csv`
- 🧹 Preprocesses data:
  - One-hot encodes categorical features
  - Scales numeric features with `StandardScaler`
- 🔁 Trains logistic regression using:
  - ✅ `sklearn.linear_model.LogisticRegression`
  - ✍️ Manual NumPy implementation (sigmoid, cost)
- 📊 Splits dataset into train/test (70/30)

---

## 🛠 Tech Stack

- Python  
- NumPy  
- Pandas  
- scikit-learn  
- Jupyter Notebook

---

## 🚀 How to Run

1. Install required packages:
```bash
pip install pandas numpy scikit-learn
