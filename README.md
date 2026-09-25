# 📊 Data Science Internship — Project 1

## E-Commerce Data Cleaning, Analysis & Feature Engineering

**Internship Organization:** DecodeLabs

### 📌 Project Overview

This project was completed as part of my **Data Science Internship at DecodeLabs**.

The project focuses on transforming raw e-commerce data into a clean, validated, and machine-learning-ready dataset through data cleaning, statistical imputation, outlier treatment, exploratory analysis, and feature engineering.

### 🎯 Objectives

- Clean and validate the raw dataset
- Handle missing values using statistical methods
- Detect and neutralize outliers using the IQR method
- Perform exploratory data analysis (EDA)
- Engineer new features from existing data
- Prepare the dataset for machine learning applications

### 🧹 Data Cleaning & Validation

The dataset was systematically checked for:

- Missing values
- Duplicate records
- Invalid numerical values
- Date consistency
- Categorical consistency
- Total price calculation consistency

### 🤖 Machine Learning Data Preparation

- Numeric missing values were handled using **median statistical imputation**.
- Missing `CouponCode` values were labeled as `No Coupon`.
- Outliers were detected using the **Interquartile Range (IQR)** method.
- Detected `TotalPrice` outliers were neutralized using IQR-based capping.
- **8 `TotalPrice` outliers** were neutralized.

### ⚙️ Feature Engineering

Four new features were created:

- `HasCoupon`
- `IsDigitalPayment`
- `OrderMonth`
- `CartUtilization`

### 📊 Exploratory Data Analysis

The analysis examined:

- Overall order value
- Product performance
- Order status
- Payment methods
- Coupon usage
- Referral sources
- Monthly and yearly trends
- Customer-level order value
- Quantity-based order patterns

### 📈 Visualizations

The project includes visualizations for:

- Monthly revenue trends
- Product revenue
- Payment method revenue
- Order status revenue
- Referral source revenue
- Coupon code revenue

### 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Microsoft Excel

### 📁 Project Files

- `Project_1_Data_Science.ipynb` — Complete analysis notebook
- `Dataset_for_Data_Analytics.xlsx` — Source dataset
- `output.png` — Project output/visualization

### ✅ Final Dataset

After cleaning and feature engineering:

- **Records:** 1,200
- **Columns:** 18
- **Missing values:** 0
- **Duplicate rows:** 0
- **Engineered features:** 4

### 📝 Conclusion

The project demonstrates a complete data preparation workflow, from raw e-commerce data cleaning and validation to exploratory analysis and machine-learning-oriented feature engineering.

### ⚠️ Limitations

- The dataset covers January 2023 to June 2025, so 2025 represents a partial year.
- `TotalPrice` represents recorded order value and should not automatically be interpreted as realized revenue.
- Observed relationships in the dataset represent associations and do not establish causation.

---

**Data Science Internship — Project 1**  
**DecodeLabs**
