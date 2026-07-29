# 🫀 Heart Disease & Diabetes Risk Prediction

An end-to-end Machine Learning capstone project analyzing the **Framingham Heart Study** dataset to predict disease risk, clean clinical data, handle class imbalance, and evaluate feature importance for early clinical insights.

---

## 📌 Project Overview
This repository contains a full data science pipeline built in Python. The objective is to identify key physiological, demographic, and lifestyle factors contributing to health risks using binary classification models (Standard and Balanced Logistic Regression).

Key highlights of the workflow:
* **Exploratory Data Analysis (EDA):** Inspecting dimensions, data types, missing value distributions, and summary statistics.
* **Data Cleaning & Imputation:** Imputing missing numerical attributes with **Median** values and categorical attributes with **Mode** values to avoid data loss.
* **Feature Preparation & Scaling:** Stratified train-test splitting (80/20) and standardized feature scaling using `StandardScaler` fitted strictly on training data.
* **Handling Class Imbalance:** Comparing standard logistic regression with class-weighted (`class_weight='balanced'`) logistic regression to improve recall for positive cases.
* **Visual Model Evaluation:** Custom teal-gray styled confusion matrices and coefficient importance plots for clear decision-making.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Environment:** Google Colab / Jupyter Notebook
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (`StandardScaler`, `train_test_split`, `LogisticRegression`, `confusion_matrix`, `classification_report`)
* **Data Visualization:** `matplotlib`, `seaborn`

---

## 📂 Repository Structure
```text
├── Project4_Skillfied.ipynb   # Main Google Colab notebook with full pipeline
├── framingham.csv             # Dataset file
└── README.md                  # Project documentation

