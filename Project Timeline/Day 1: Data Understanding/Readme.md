# 📊 Bank Customer Churn Analysis

🚀 End-to-End Data Analytics Project (Python + Power BI)

---

## 📌 Project Overview
This project focuses on analysing customer data from a bank to understand the key factors that influence customer churn (when customers leave the bank).

The objective is to perform detailed exploratory data analysis (EDA) and generate actionable insights that can help the business improve customer retention.

---

## 📂 Dataset Information
The dataset contains information about **10,000 bank customers** with features such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Member Status
- Estimated Salary
- Churn (Exited)

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Data Visualization (Matplotlib, Seaborn)
- Power BI (for dashboard - upcoming)

---

## 🚀 Day 1: Data Understanding

### ✔ Tasks Performed
- Loaded dataset using Pandas
- Explored dataset structure (shape, columns, data types)
- Checked for missing values
- Analysed target variable (Exited)
- Created initial visualisation of churn distribution

---

## 📊 Key Observations
- The dataset contains **10,000 rows and 14 columns**
- No missing values were found
- Target variable **'Exited' is imbalanced**
- Majority of customers have not churned

---

## 📈 Sample Code

```python
import pandas as pd

# Load dataset
df = pd.read_csv("Churn_Modelling.csv")

# Basic understanding
print(df.shape)
print(df.columns)
print(df.dtypes)

# Missing values
print(df.isnull().sum())

# Target variable distribution
print(df['Exited'].value_counts())

#Learning Outcome
Understanding the dataset structure and identifying data quality issues is the first step in any data analysis project.

---
👤 Mohammad Ali  
📊 Aspiring Data Analyst  

🔹 Skilled in: SQL | Excel | Power BI | Python  
🔹 Currently building real-world data analytics projects  

📫 Open to opportunities and collaborations  
