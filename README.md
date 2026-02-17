# 🩺 Breast Cancer Detection using Ensemble Machine Learning

## 📌 Overview

This project presents an end-to-end machine learning pipeline for early breast cancer detection using the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. The objective is to build a robust, reliable, and interpretable classification system capable of distinguishing between malignant and benign tumors using ensemble learning techniques.

The system integrates data preprocessing, exploratory data analysis (EDA), model training, hyperparameter optimization, cross-validation, and deployment through a Flask-based web application.

This project bridges academic research with real-world AI application in healthcare diagnostics.

---

## 🎯 Problem Statement

Breast cancer remains one of the leading causes of mortality among women worldwide. Early detection significantly improves survival rates. Manual diagnosis can be time-consuming and subject to human error.

The goal of this project is to develop a machine learning-based decision support system that assists in accurate and early tumor classification using structured medical data.

---

## 📊 Dataset

- **Dataset Name:** Wisconsin Diagnostic Breast Cancer (WDBC)
- **Total Samples:** 569
- **Features:** 30 numerical features derived from digitized images of breast mass
- **Target Classes:** 
  - Malignant (M)
  - Benign (B)

The dataset contains computed features such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

---

## 🧠 Machine Learning Approach

### 1️⃣ Data Preprocessing
- Removal of unnecessary columns
- Label encoding of target variable
- Feature scaling using StandardScaler
- Train-test split
- Handling class distribution

### 2️⃣ Exploratory Data Analysis (EDA)
- Correlation heatmap
- Feature distribution analysis
- Class imbalance visualization
- Outlier inspection

### 3️⃣ Models Implemented

- ✅ AdaBoost Classifier  
- ✅ XGBoost Classifier  
- ✅ Baseline comparison models  

### 4️⃣ Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Cross-validation (K-Fold)

---

## 📈 Results

The ensemble boosting techniques demonstrated strong classification performance:

- XGBoost achieved high predictive accuracy with strong generalization.
- AdaBoost showed competitive performance with stable recall.
- Cross-validation confirmed model robustness.

Feature importance analysis revealed the most influential medical parameters contributing to tumor classification.

---

## 🌐 Web Application Deployment

A Flask-based web interface was developed to enable real-time prediction.

### Features:
- User input form for medical parameters
- Backend model integration
- Real-time classification output
- Clean and responsive UI

This demonstrates the transition from model development to practical deployment.

---

## 🏗️ Project Structure
# Breast-Cancer-using-Machine-Lerning-
