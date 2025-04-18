# Diagnose-Diabetes
# 🩺 Diagnose Diabetes Using Machine Learning

This project uses machine learning techniques to diagnose diabetes in female patients based on medical data from the Pima Indians Diabetes Dataset. The goal is to build a predictive model that can accurately classify whether a person is diabetic (`1`) or not (`0`).

---

## 📂 Dataset Overview

- **Source**: Pima Indians Diabetes Dataset
- **Records**: 768 female patients (21 years and older)
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- **Target**:
  - `Outcome` (0 = No diabetes, 1 = Diabetes)

---

## 🎯 Problem Statement

Build a binary classification model that predicts diabetes based on various medical features. Challenges include:
- Class imbalance
- Missing or unrealistic values (e.g., Glucose = 0)
- Need for data cleaning and feature scaling

---

## 🚀 Approach

1. **Data Loading & Exploration**
   - Check for missing values and class distribution
   - Visualize data using seaborn and matplotlib

2. **Data Preprocessing**
   - Handle zero/invalid values
   - Scale features using `StandardScaler`
   - Split data into training and testing sets

3. **Modeling**
   - Trained a `RandomForestClassifier` on the cleaned, scaled dataset
   - Evaluated using accuracy, confusion matrix, precision, recall, and F1-score

4. **Visualization**
   - Outcome distribution plot
   - Correlation heatmap
   - Pairplots for Glucose, BMI, and Age

---

## 📈 Results

- **Model**: Random Forest Classifier
- **Evaluation Metrics**:
  - High accuracy on test data
  - Balanced precision and recall
  - Insights from feature importance and correlations

---

## 🧪 Sample Output

