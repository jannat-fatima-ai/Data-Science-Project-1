# 📊 Data Science Project 1 — E-Commerce Data Analysis

## 📌 Project Overview

This project is part of my **Data Science Internship**, where I performed a complete exploratory analysis of an e-commerce orders dataset using Python.

The objective of this project was to transform raw e-commerce data into meaningful insights by performing **data inspection, cleaning, validation, exploratory data analysis, aggregation, and visualization**.

Throughout the project, I focused on maintaining data quality and carefully interpreting the results rather than making assumptions from the data.

---

## 🎯 Project Objectives

The main objectives of this project were to:

* Understand and inspect the structure of the dataset
* Identify and handle missing values
* Check for duplicate records
* Detect and evaluate potential outliers
* Validate numerical values
* Verify price calculations
* Validate dates and categorical variables
* Analyze sales and revenue patterns
* Compare products, payment methods, coupons, and referral sources
* Identify important trends through data visualization

---

## 🧹 Data Cleaning & Validation

Before performing the analysis, the dataset was systematically checked for data-quality issues.

### Checks Performed

* ✅ Missing value analysis
* ✅ Duplicate row detection
* ✅ Outlier detection
* ✅ Numerical value validation
* ✅ Categorical consistency checks
* ✅ Date validation
* ✅ Price calculation verification
* ✅ Data type inspection

The `CouponCode` column contained missing values. These were handled by treating missing coupon entries as **"No Coupon"**, allowing the coupon analysis to retain all records.

Potential outliers in `TotalPrice` were inspected and retained because they were considered valid observations rather than automatically removing them.

---

## 📊 Exploratory Data Analysis

The analysis covers multiple dimensions of the e-commerce dataset.

### Revenue & Sales Analysis

* Total orders
* Total revenue
* Average Order Value
* Product-wise revenue
* Product-wise order volume
* Product-wise average order value
* Monthly revenue trends
* Customer-level revenue analysis
* Quantity-wise revenue analysis

### Business Dimension Analysis

* Payment method analysis
* Order status analysis
* Coupon code analysis
* Referral source analysis

These comparisons were used to understand how different categories are represented within the dataset and how their associated revenue differs.

---

## 📈 Key Findings

Based on the analyzed dataset:

* **1,200 orders** were analyzed.
* Total recorded order value was approximately **1.26 million**.
* Average Order Value was approximately **1,053.97**.
* **Chair** generated the highest total recorded revenue among products.
* **Laptop** had the highest average order value.
* **Credit Card** had the highest associated revenue among payment methods.
* **Instagram** had the highest associated revenue among referral sources.
* **FREESHIP** had the highest associated revenue among coupon categories.
* **June 2024** recorded the highest monthly revenue in the dataset.

These findings describe patterns in the available data and should not be interpreted as proof of causation.

---

## 📊 Visualizations

Matplotlib was used to create visualizations for:

* Monthly Revenue Trend
* Product Revenue
* Payment Method Revenue
* Order Status Revenue
* Referral Source Revenue
* Coupon Code Revenue

The visualizations make it easier to compare categories and identify revenue patterns.

---

## 🛠️ Technologies & Tools

* **Python**
* **Pandas**
* **Matplotlib**
* **Jupyter Notebook**
* **Microsoft Excel**
* **GitHub**

---

## 📂 Project Structure

```text
Data-Science-Project-1/
│
├── Dataset_for_Data_Analytics.xlsx
├── Project_1_Data_Science.ipynb
├── output.png
└── README.md
```

---

## 🔍 Project Workflow

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
Revenue & Category Analysis
     ↓
Data Visualization
     ↓
Key Findings
```

---

## 💡 Skills Demonstrated

This project demonstrates practical experience with:

* Data preprocessing
* Data cleaning
* Data validation
* Exploratory Data Analysis (EDA)
* Pandas DataFrame operations
* GroupBy and aggregation
* Revenue analysis
* Trend analysis
* Data visualization
* Analytical interpretation
* Jupyter Notebook workflow
* GitHub project organization

---

## 📎 Project Files

**Dataset:** `Dataset_for_Data_Analytics.xlsx`
**Analysis Notebook:** `Project_1_Data_Science.ipynb`
**Output:** `output.png`

---

## 👩‍💻 About This Project

I completed this project as part of my Data Science Internship with a focus on developing a strong understanding of the complete data-analysis workflow — from **raw data inspection and cleaning to analysis, visualization, and interpretation**.

This project reflects my approach of working systematically with data, validating results, and documenting the analytical process clearly.

---

### ⭐ Project Status

**Completed — Data Analysis & Visualization**
