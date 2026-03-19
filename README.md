# 🧑‍💼 HR Attrition Analytics Dashboard with Explainable AI (SHAP)

## 📌 Project Overview
Employee attrition is a critical challenge for organizations, impacting productivity and costs.  
This project combines SQL, Python, Machine Learning, SHAP, and Power BI to analyze, predict, and visualize employee attrition.

The goal is to:
- Understand why employees leave  
- Predict which employees are likely to leave  
- Provide interactive dashboards for HR decision-making  

---

## 🎯 Objectives
- Analyze employee attrition patterns using SQL & Python  
- Build a machine learning model to predict attrition  
- Use SHAP (Explainable AI) to interpret model predictions  
- Create an interactive Power BI dashboard for insights  
- Identify high-risk employees and key drivers of attrition  

---

## ⚙️ End-to-End Workflow

### 🔹 1. Data Analysis using SQL
- Performed data exploration using SQL queries  
- Analyzed attrition by department, job role, salary band, and age group  
- Extracted insights for further analysis  

---

### 🔹 2. Data Preprocessing (Python)
- Handled missing values  
- Encoded categorical variables  
- Scaled numerical features  
- Prepared dataset for modeling  

---

### 🔹 3. Exploratory Data Analysis (EDA)
- Used Pandas, Matplotlib, and Seaborn  
- Analyzed:
  - Attrition vs Salary  
  - Attrition vs Job Role  
  - Attrition vs Overtime  
- Identified patterns and correlations  

---

### 🔹 4. Machine Learning Model
- Built classification model using Random Forest / XGBoost  
- Evaluated using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - ROC-AUC  

---

### 🔹 5. Explainable AI with SHAP
- Implemented SHAP (SHapley Additive Explanations)  
- Generated:
  - Global Feature Importance (Beeswarm Plot)  
  - Local Explanations (Force Plot)  

Insights:
- OverTime, MonthlyIncome, and JobRole are key drivers  
- Helps explain why employees are predicted to leave  

---

### 🔹 6. Power BI Dashboard
- Connected processed data to Power BI  
- Built interactive dashboard with:
  - KPI Cards (Total Employees, Attrition Rate, Attrition Count)  
  - Slicers (Department, Gender, Age Group)  
  - Charts:
    - Attrition by Department  
    - Attrition by Salary Band  
    - Attrition by Job Role  

- Designed dashboard for HR decision-making  

---

## 📊 Key Features
- End-to-end workflow (SQL → Python → ML → SHAP → Power BI)  
- Combines data analysis, machine learning, and visualization  
- Provides predictive and explainable insights  

---

## 🛠️ Tech Stack
- SQL  
- Python  
- Pandas / NumPy  
- Scikit-learn / XGBoost  
- SHAP  
- Matplotlib / Seaborn  
- Power BI  

---

## 📊 Dashboard Preview
![HR Dashboard](./https://github.com/Shivani9chinthala/Employee-Attrition-Analytics-SQL-PowerBI-Python-Shap/blob/main/Screenshot%202026-03-18%20194759.png)

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/hr-attrition-analytics.git
cd hr-attrition-analytics
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Run the notebook:
```bash
jupyter notebook
```

---

## 💡 Business Impact
- Helps HR teams identify high attrition risk employees  
- Supports data-driven HR decisions  
- Improves employee retention strategies  

---

## 🔗 Project Links
- GitHub Repository: https://github.com/Shivani9chinthala/Employee-Attrition-Analytics-SQL-PowerBI-Python-Shap  

---

## 👤 Author
Shivani Chinthala
