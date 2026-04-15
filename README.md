# customer-churn-prediction-ml
Machine learning project to predict customer churn using classification models, with full data preprocessing, evaluation, and business insights.

 ## 🚀 Project Highlights
- Built end-to-end machine learning pipeline
- Performed data cleaning and feature engineering
- Compared multiple models (Logistic Regression & Random Forest)
- Evaluated using precision, recall, F1-score, and confusion matrix
- Generated business insights from model predictions

  # 📊 CUSTOMER CHURN PREDICTION PROJECT

## 📌 TABLE OF CONTENTS

* [Project Overview](#project-overview)
* [Problem Statement](#problem-statement)
* [Dataset Description](#dataset-description)
* [Technologies Used](#technologies-used)
* [Project Workflow](#project-workflow)
* [Data Preprocessing](#data-preprocessing)
* [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
* [Model Building](#model-building)
* [Model Evaluation](#model-evaluation)
* [Key Insights](#key-insights)
* [Conclusion](#conclusion)
* [Future Improvements](#future-improvements)

---

## 📌 PROJECT OVERVIEW

This project focuses on predicting customer churn using machine learning techniques. Customer churn refers to customers who stop using a company's service.

The goal is to build a model that can identify customers likely to leave, enabling businesses to take proactive retention measures.

---

## 🎯 PROBLEM STATEMENT

Businesses lose revenue when customers leave. Identifying customers at risk of churn helps companies:

* Improve customer retention
* Reduce revenue loss
* Make data-driven decisions

This project aims to predict whether a customer will churn or not based on their behavior and characteristics.

---

## 📂 DATASET DESCRIPTION

The dataset contains customer-related information such as:

* Demographics (e.g., gender, age)
* Account details
* Service usage
* Billing information

### Target Variable:

* **Churn**

  * 0 → Customer stays
  * 1 → Customer leaves

---

## 🛠️ TECHNOLOGIES USED

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 🔄 PROJECT WORKFLOW

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Insights & Interpretation

---

## 🧹 DATA PREPROCESSING

* Handled missing values
* Converted categorical variables into numerical format:

  * Binary columns → Label Encoding (Yes/No → 1/0)
  * Multi-category columns → One-Hot Encoding
* Removed unnecessary columns
* Split data into training and testing sets

---

## 🔍 EXPLORATORY DATA ANALYSIS (EDA)

Key steps:

* Checked data distribution
* Analyzed class imbalance
* Explored relationships between features and churn

Insights from EDA helped guide feature selection and model building.

---

## 🤖 MODEL BUILDING

Two models were used:

### 1. Logistic Regression

* Baseline model
* Easy to interpret

### 2. Random Forest Classifier

* Improved performance
* Captures complex patterns in data

---

## 📊 MODEL EVALUATION

### Metrics Used:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### Final Model Performance:

* **Accuracy:** 86%
* **Churn Recall:** 68%

### Confusion Matrix Interpretation:

* Correctly predicted non-churn: 2403
* Correctly predicted churn: 756
* Missed churn cases: 599
* False alarms: 242

---

## 💡 KEY INSIGHTS

* The model performs well overall but struggles to detect all churn cases
* A significant number of customers who churn are not identified
* High precision indicates reliable predictions when churn is detected
* Improving recall is critical for business impact

---

## ✅ CONCLUSION

The model successfully predicts customer churn with good accuracy. However, improving recall for churn cases is necessary to better identify at-risk customers.

This project demonstrates the full machine learning pipeline from data preprocessing to model evaluation and interpretation.

---

## 🚀 FUTURE IMPROVEMENTS

* Improve recall using:

  * Class weighting
  * Threshold tuning
* Try advanced models (XGBoost, LightGBM)
* Perform hyperparameter tuning
* Deploy model as a web application
* Integrate with business dashboards (Power BI)

---

⭐ If you found this project useful, feel free to star the repository!
