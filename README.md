# 📊 E-Commerce Data Analysis

## Data Science Internship — Project 1

**Internship Organization:** DecodeLabs
**Tools:** Python, Pandas, Matplotlib, Jupyter Notebook, Microsoft Excel, GitHub

---

## 📌 Project Overview

This project was completed as part of my **Data Science Internship at DecodeLabs**.

The project focuses on analyzing an e-commerce orders dataset using Python and Pandas. A structured data analysis workflow was followed, including data inspection, data cleaning, validation, exploratory data analysis (EDA), and visualization.

The main goal is to transform raw e-commerce data into meaningful insights while maintaining data quality and interpreting results carefully.

---

## 🎯 Project Objectives

* Understand the structure and characteristics of the dataset
* Perform data inspection and preprocessing
* Identify and handle missing values
* Check for duplicate records
* Detect and evaluate potential outliers
* Validate numerical, categorical, and date-related data
* Verify order price calculations
* Analyze products, customers, payment methods, order statuses, coupons, and referral sources
* Examine monthly and yearly order-value trends
* Create meaningful data visualizations
* Summarize key findings and limitations

---

## 🧹 Data Cleaning & Validation

The dataset was systematically checked and validated before performing the analysis.

The following checks were performed:

* Missing values
* Duplicate records
* Categorical consistency
* Numerical validity
* Potential outliers
* Date validation
* Price calculation consistency

Missing coupon codes were replaced with **"No Coupon"** to preserve the information that no coupon was recorded for those orders.

The final dataset contains **1,200 records with no remaining missing values or duplicate rows**.

---

## 📊 Exploratory Data Analysis

The analysis covered:

* Overall order volume and recorded order value
* Product-wise performance
* Order status distribution
* Payment method usage
* Coupon code usage
* Referral source performance
* Monthly and yearly trends
* Customer-level activity
* Quantity-wise order value
* Average Order Value (AOV)
* Category-level comparisons

---

## 🔎 Key Findings

* **Total Orders:** 1,200
* **Total Recorded Order Value:** 1,264,761.96
* **Average Order Value:** 1,053.97
* **Highest Recorded Order Value by Product:** Chair — 195,620.11
* **Highest Average Order Value by Product:** Laptop — 1,110.56
* **Highest Recorded Order Value by Payment Method:** Credit Card — 263,847.63
* **Highest Recorded Order Value by Referral Source:** Instagram — 275,285.45
* **Highest Recorded Order Value by Coupon:** FREESHIP — 335,036.99
* **Highest Recorded Order-Value Month:** June 2024 — 68,068.54

These findings describe patterns and associations in the dataset and should not be interpreted as evidence of causal relationships.

---

## 📈 Visualizations

The project includes visualizations for:

* Monthly order-value trends
* Product-wise recorded order value
* Payment method analysis
* Order status analysis
* Referral source analysis
* Coupon code analysis

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **Matplotlib**
* **Jupyter Notebook**
* **Microsoft Excel**
* **GitHub**

---

## 📁 Project Structure

```text
Data-Science-Project-1/
│
├── Dataset_for_Data_Analytics.xlsx
├── Project_1_Data_Science.ipynb
├── output.png
└── README.md
```

---

## 🔄 Data Analysis Workflow

```text
Raw Dataset
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Data Validation
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Key Findings
     ↓
Conclusion & Limitations
```

---

## 📝 Conclusion

This project demonstrates a complete data analysis workflow using an e-commerce dataset.

The analysis covers data quality checks, exploratory analysis, business-related comparisons, and visualizations. The project demonstrates practical skills in **Python, Pandas, data cleaning, exploratory data analysis, visualization, and interpretation**.

---

## ⚠️ Limitations

* The dataset covers January 2023 to June 2025, so **2025 represents only a partial year**.
* `TotalPrice` represents recorded order value and should not automatically be interpreted as realized revenue because the dataset contains cancelled, returned, and pending orders.
* Observed relationships between categories and order value represent **associations rather than causal effects**.
* The dataset does not provide enough information to determine the reasons behind changes in order value or customer behavior.

---

## 👩‍💻 Project Status

**Completed — Data Science Internship Project 1**

**Organization:** DecodeLabs
