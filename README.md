# churn-prediction

## 📌 Overview
This project focuses on predicting customer churn in a telecommunications company using machine learning techniques.

The goal is not only to predict which customers are likely to leave, but also to understand the key factors driving churn.

---

## 🧠 Problem
Customer churn is a critical business problem. Identifying customers at risk allows companies to take proactive actions and improve retention.

---

## 📂 Dataset
The dataset consists of multiple sources:
- Customer information
- Product data
- Usage data
- Financial data

The target variable was engineered by comparing customers between December and January.

---

## ⚙️ Methodology

### 1. Data Preparation
- Merging multiple datasets
- Handling missing values using business logic
- Feature engineering (e.g., customer tenure)

### 2. Modeling
- Logistic Regression (baseline)
- Random Forest
- Decision Tree

### 3. Model Improvement
- Handling class imbalance using SMOTE
- Cross-validation for model comparison

---

## 📊 Results

| Model               | Recall |
|--------------------|--------|
| Logistic Regression | 0.93   |
| Decision Tree       | 0.96   |
| Random Forest       | 0.98   |

👉 Random Forest achieved the best performance.

---

## 📈 Key Insights
- Customers with unpaid bills are more likely to churn
- Lack of discounts increases churn probability
- Premium users (e.g., football TV package) are more sensitive to price

---

## 🚀 Business Impact
The model can be used to:
- Identify high-risk customers
- Support retention campaigns
- Optimize marketing strategies

---

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## 📬 Author
Marc Pérez Lleixà
