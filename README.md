# 📊 Customer Churn Analysis & Prediction

## 📌 Project Overview

This project focuses on analyzing customer churn behavior in a telecom company and building a machine learning model to predict churn.

It covers the complete data workflow:
👉 Data Cleaning → EDA → Dashboarding → Prediction

The goal is to identify key factors driving churn and help businesses improve customer retention strategies.

---

## 🛠 Tools & Technologies

- 🐍 Python (Pandas, NumPy, Matplotlib, Seaborn)
- 📊 Power BI (Interactive Dashboard)
- 🤖 Machine Learning (Scikit-learn)
- 📁 CSV Dataset

---

## 🧹 Data Processing (Python)

- Cleaned and handled missing values  
- Converted categorical features into numeric format  
- Performed Exploratory Data Analysis (EDA)  
- Identified patterns and trends affecting churn  

---

## 📊 Dashboard Features (Power BI)

- 📌 Total Customers, Churned Customers, Churn Rate  
- 📊 Churn by Contract Type  
- 💳 Churn by Payment Method  
- 🌐 Churn by Internet Service  
- 💰 Monthly Charges vs Churn  
- ⏳ Tenure vs Churn  
- 📉 Churn Rate by Tenure Group  
- 🎛 Interactive filters for dynamic analysis  

---

## 🤖 Machine Learning Model

### 🎯 Objective

Predict customer churn:

- **0 → No Churn**  
- **1 → Churn**

### ⚙️ Model Used

- Logistic Regression  

---

## 📈 Model Performance

### 🔢 Confusion Matrix

```
[[915 118]
 [181 193]]
```

### 📊 Classification Report

| Class        | Precision | Recall | F1-Score |
|--------------|----------|--------|----------|
| 0 (No Churn) | 0.83     | 0.89   | 0.86     |
| 1 (Churn)    | 0.62     | 0.52   | 0.56     |

### 🎯 Accuracy

👉 **79%**

---

## 🔍 Key Insights

- 📌 Month-to-month contracts have the highest churn (~42%)  
- 💳 Electronic check users churn the most (~45%)  
- 🌐 Fiber optic users show higher churn (~42%)  
- 🆕 New customers (0–6 months) are at highest risk  
- 💰 Higher monthly charges increase churn probability  

---

## 💡 Business Recommendations

- Offer incentives for long-term contracts  
- Improve onboarding experience for new customers  
- Provide discounts for high-value customers  
- Enhance service quality for fiber optic users  
- Use predictive model to target high-risk customers  

---

## 📷 Dashboard Preview

<img width="1332" height="754" alt="Dashboard" src="https://github.com/user-attachments/assets/4e21a615-9794-430c-b8bb-50a1f0cc7af8" />


---

## 🤖 Model Output

<img width="1564" height="811" alt="model_output" src="https://github.com/user-attachments/assets/10d8c2d1-efc8-4c27-9a88-419cac2db191" />



---

## 📂 Project Structure

```
Customer-Churn-Analysis/
│
├── Churn_Dashboard.pbix
├── churn_data.csv
├── customer_churn_end_to_end.ipynb
├── dashboard.png
├── model_output.png
└── README.md
```

---

## 🚀 Author

**Rupesh Mahto**  
📍 India
