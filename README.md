# 🩺 Diabetes Prediction using XGBoost  
*Kaggle Playground Series 2025 – Tabular Data*

## 📌 Overview
This project was developed as part of the **Kaggle Playground Series 2025** competition.  
The objective is to **predict the probability that a patient will be diagnosed with diabetes** using synthetically generated healthcare tabular data.

The project focuses on building an **end-to-end machine learning pipeline** with emphasis on data preprocessing, feature engineering, model optimization, and performance evaluation.

---

## 🎯 Problem Statement
Given a set of patient health-related features, predict the **probability of diabetes diagnosis**.

- **Task Type:** Binary Classification  
- **Target Variable:** `diagnosed_diabetes`  
- **Evaluation Metric:** ROC–AUC  

---

## 🧠 Approach

### 1. Data Understanding & EDA
- Analyzed feature distributions and correlations  
- Identified missing values and data patterns  
- Explored relationships between features and the target variable  

### 2. Data Preprocessing
- Handled missing values  
- Encoded features where required  
- Prepared clean datasets for modeling  

### 3. Feature Engineering
- Selected relevant features for model training  
- Improved model performance through iterative feature refinement  

### 4. Model Development
- Implemented **XGBoost (Gradient Boosting)** for binary classification  
- Tuned hyperparameters including:
  - Learning rate
  - Max depth
  - Number of estimators
  - Subsample ratio  

### 5. Model Evaluation
- Evaluated performance using **ROC–AUC**
- Compared multiple configurations to optimize results  

---

## 📊 Results

| Metric | Score |
|------|------|
| ROC–AUC (Submission) | **0.69441** |
| Best Leaderboard Score | 0.70807 |

The model achieved a competitive ROC–AUC score, demonstrating strong performance close to the top leaderboard results.

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries & Tools:**  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - XGBoost  

---
