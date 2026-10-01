# 💳 Credit Card Fraud Detection – Exploratory Data Analysis (EDA)

<p align="center">

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=28&duration=3000&pause=1000&color=00C2FF&center=true&vCenter=true&width=900&lines=Credit+Card+Fraud+Detection;Exploratory+Data+Analysis+(EDA);Python+%7C+Pandas+%7C+NumPy+%7C+Matplotlib+%7C+Seaborn;Data+Cleaning+%7C+Visualization+%7C+Business+Insights" />

</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge\&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-013243?style=for-the-badge\&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge\&logo=jupyter)

</p>

---

# 📌 Project Overview

Financial fraud is one of the biggest challenges in today's digital economy. Even a tiny percentage of fraudulent transactions can lead to millions of dollars in losses.

This project performs a **complete Exploratory Data Analysis (EDA)** on the famous **Credit Card Fraud Detection Dataset**, uncovering hidden patterns, identifying anomalies, understanding transaction behavior, and preparing the dataset for future Machine Learning models.

The analysis focuses on understanding fraud patterns rather than building predictive models, providing a strong foundation for fraud detection systems.

---

# 🎯 Project Objectives

✔ Understand the dataset structure

✔ Perform data cleaning

✔ Detect missing values & duplicates

✔ Explore transaction distributions

✔ Analyze fraud vs genuine transactions

✔ Detect outliers

✔ Perform correlation analysis

✔ Generate business insights

✔ Prepare data for Machine Learning

---

# 📊 Dataset Information

| Feature              | Value   |
| -------------------- | ------- |
| Total Transactions   | 284,807 |
| Fraud Transactions   | 492     |
| Genuine Transactions | 284,315 |
| Features             | 31      |
| Numerical Features   | 30      |
| Target Variable      | Class   |
| Fraud Percentage     | 0.172%  |

---

# 🛠 Technologies Used

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 🎨 Seaborn
* 📓 Jupyter Notebook

---

# 📂 Project Workflow

```text
Dataset
   │
   ▼
Data Inspection
   │
   ▼
Data Cleaning
   │
   ▼
Missing Value Analysis
   │
   ▼
Duplicate Removal
   │
   ▼
Statistical Summary
   │
   ▼
Univariate Analysis
   │
   ▼
Class Distribution
   │
   ▼
Transaction Analysis
   │
   ▼
Correlation Analysis
   │
   ▼
Business Insights
```

---

# 🔍 Exploratory Data Analysis

## 📌 Data Cleaning

* No Missing Values
* Correct Data Types
* Duplicate Transactions Removed
* Dataset Ready for Analysis

---

## 📈 Statistical Analysis

The statistical summary provides insights into:

* Mean
* Median
* Standard Deviation
* Minimum
* Maximum
* Quartiles

---

## 💰 Transaction Amount Analysis

Key observations:

* Most transactions involve small amounts.
* Distribution is highly right-skewed.
* Several extreme transaction values exist.
* Large transactions are rare but important.

---

## ⏰ Transaction Time Analysis

The **Time** feature was converted into **Hours** to understand transaction behavior throughout the day.

Insights include:

* Continuous transaction flow
* Fraud appears throughout the day
* Certain hours show relatively higher fraud frequency

---

## 🚨 Fraud Distribution

One of the biggest findings is the severe class imbalance.

| Transaction |   Count |
| ----------- | ------: |
| Genuine     | 284,315 |
| Fraud       |     492 |

Fraud transactions account for only **0.172%** of the dataset.

This makes fraud detection a **highly imbalanced classification problem**.

---

## 📉 Correlation Analysis

A correlation heatmap was generated to understand relationships among numerical features.

Key findings:

* Low multicollinearity
* PCA variables are mostly independent
* Several variables show meaningful relationships

---

## 📦 Outlier Analysis

Outliers were detected using boxplots.

Instead of removing them,

✅ They were preserved because fraudulent transactions often appear as unusual observations.

---

# 📊 Key Insights

✔ Dataset contains **no missing values**

✔ Duplicate records were removed

✔ Fraud transactions are extremely rare

✔ Transaction amount is heavily skewed

✔ Time patterns may help identify fraud

✔ PCA features contain useful predictive information

✔ Dataset is suitable for Machine Learning after preprocessing

---

# 📁 Project Structure

```text
Credit-Card-Fraud-EDA/

│── Dataset/
│      creditcard.csv
│
│── Notebook/
│      Credit_Card_Fraud_EDA.ipynb
│
│── Images/
│      charts/
│      plots/
│
│── Report/
│      EDA_Report.pdf
│
│── README.md
```

---

# 🚀 Future Improvements

* Feature Engineering
* SMOTE Oversampling
* Machine Learning Models
* Hyperparameter Tuning
* Deep Learning
* Real-Time Fraud Detection API
* Interactive Dashboard
* Model Deployment

---

# 📚 References

**Dataset**

Credit Card Fraud Detection Dataset (Machine Learning Group, Université Libre de Bruxelles)

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

**Research Paper**

Dal Pozzolo, A., Caelen, O., Johnson, R. A., & Bontempi, G. (2015).

Calibrating Probability with Undersampling for Unbalanced Classification.

IEEE Symposium Series on Computational Intelligence (SSCI)

---

# ⭐ If you like this project

Give this repository a ⭐ on GitHub and feel free to fork it.

---

<p align="center">

### 👨‍💻 Developed by Shraddha bisht

**AI • Machine Learning • Data Science**

*"Turning Data into Meaningful Insights."*

</p>
