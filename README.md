# Feature Engineering on Employee Dataset

## Overview
This project focuses on applying Feature Engineering techniques on a real-world employee dataset (1000+ records) to prepare data for Machine Learning.

---

## Objectives
- Handle missing values using sklearn Imputer
- Apply encoding techniques (Label Encoding, One Hot Encoding, Target Encoding)
- Perform time-based feature engineering
- Apply feature scaling (Min-Max, Standardization, Robust Scaling)
- Handle skewed data using log transformation

---

## Dataset
- 1000+ employee records
- Includes features like Age, Gender, Department, Experience, City, Salary

---

## Feature Engineering Steps

### 1. Handling Missing Values
- Used `SimpleImputer` to fill missing Age values

### 2. Encoding
- Label Encoding for binary data
- One Hot Encoding for categorical features
- Target Encoding (concept)

### 3. Time-Based Features
- Extracted Year, Month, and Years_at_Company from Joining Date

### 4. Feature Scaling
- Min-Max Scaling
- Standardization
- Robust Scaling

### 5. Skewness Handling
- Applied log transformation on Salary

---

## Key Insights
- Experience and Years_at_Company are strong indicators of salary
- Scaling improves model performance
- Log transformation reduces skewness

---

## Conclusion
The dataset is now clean, structured, and ready for Feature Selection and Machine Learning.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
