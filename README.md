# Health-and-fitness-prediction

# 🏥 Predictive Health Classification Using Fitness Data

## 📌 Project Overview
This project develops a **predictive health classification system** using real-world health and fitness tracking data collected from wearable devices and activity logs.  

The dataset contains information from **3,000 participants**, including demographic characteristics, daily activity patterns, and physiological health indicators. The objective is to classify individuals into health conditions such as *healthy*, *high blood pressure*, *diabetes*, and *asthma*, supporting **early risk detection and preventive healthcare decisions**.

---

## 📊 Dataset Description

- Observations: 3,000 participants  
- Data Source: Wearable device tracking & activity logs  
- Problem Type: Multiclass Classification  

### Key Features
- Demographics (age, gender, height, weight)
- Activity patterns and intensity levels
- Body Mass Index (BMI)
- Heart rate
- Blood pressure
- Sleep duration
- Stress level
- Hydration level
- Smoking status
- Activity type

### Target Variable
- Health Status (`Healthy`, `High Blood Pressure`, `Diabetes`, `Asthma`, etc.)

---

## 🔎 Project Workflow

### 1️⃣ Data Preprocessing
- Data type conversion
- Missing value handling
- Feature engineering:
  - BMI calculation
- Train–test splitting

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution of health conditions
- Effects of weight, height, and gender on health outcomes
- Correlation heatmaps
- Cramér’s V association analysis
- FAMD (Factor Analysis for Mixed Data)
- Multivariate outlier detection

---

### 3️⃣ Machine Learning Models
The following classification algorithms were implemented and compared:

- Logistic Regression
- Ridge Classifier
- Linear Discriminant Analysis (LDA)
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

---

## 📈 Model Evaluation

Evaluation metrics:
- Accuracy
- Sensitivity (Recall)
- F1-score

| Model | Training Accuracy | Test Accuracy | Observation |
|------|------------------|--------------|-------------|
| Random Forest | Very High | Lower | Overfitting |
| SVM | Very High | Lower | Overfitting |
| XGBoost | High | Moderate | Slight overfitting |
| Logistic Regression | **0.713** | **0.712** | Best generalization |

---

## ⭐ Key Findings
- Tree-based and SVM models achieved high training accuracy but showed **overfitting**.
- Logistic Regression provided the best balance between bias and variance.
- Interpretable linear models can outperform complex models when generalization is prioritized.
- Activity intensity, BMI, weight, and lifestyle behaviors strongly influence health outcomes.

---

## 🛠️ Technologies Used
- Python
- tidyverse
- caret
- FactoMineR (FAMD)
- randomForest
- xgboost
- e1071 (SVM)
- ggplot2

---

---

## 🚀 Results & Impact
The project demonstrates how wearable-device and lifestyle data can be leveraged for **personalized health monitoring**, early disease risk identification, and decision support in preventive healthcare systems.

---
