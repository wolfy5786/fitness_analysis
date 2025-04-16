# 🏃‍♀️ Fitness Data Analysis & Activity Classification

This project leverages a large-scale physiological monitoring dataset to analyze user activity patterns, handle missing data, and build a predictive model to classify physical activity types. It showcases the power of exploratory analysis and dimensionality reduction in a real-world health and fitness dataset.

---

## 📁 Project Overview

**Objective**: Analyze high-resolution fitness tracking data to uncover behavioral trends, handle data gaps, and accurately classify activity types using machine learning.

---

## 🔍 Key Features

- **Dataset**: PM Data dataset  
  - 2+ million measurements  
  - 2,440 recorded activity sessions  
  - Data collected from 16 individuals over **5 months**
  
- **Exploratory Data Analysis (EDA)**:
  - Uncovered user-specific activity patterns and trends across time
  - Analyzed sensor data including heart rate, acceleration, temperature, and movement metrics

- **Missing Data Handling**:
  - Applied **Linear Regression Imputation** to fill **12% missing values** in numerical features
  - Evaluated imputation reliability through error analysis

- **Activity Classification**:
  - Used **K-Nearest Neighbors (KNN)** to classify physical activity types (e.g., walking, running, cycling)
  - Enhanced model performance using **Principal Component Analysis (PCA)** for dimensionality reduction
  - Achieved **85.6% classification accuracy**

---

## 🧰 Tech Stack

- **Languages**: Python
- **Libraries**:  
  `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `statsmodels`

---

## 📊 Workflow Summary

1. **Data Cleaning**: Filtered outliers, normalized metrics, and handled missing values with regression
2. **EDA**: Visualized individual and group activity patterns over time
3. **Dimensionality Reduction**: Applied PCA to reduce high-dimensional sensor data
4. **Modeling**: Trained and validated a **KNN classifier** for activity type prediction
5. **Evaluation**: Assessed model with accuracy, confusion matrix, and cross-validation

---
