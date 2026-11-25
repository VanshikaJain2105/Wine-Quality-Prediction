# 🍷 Wine Quality Prediction

**Day 5/100 - 100 Days of Machine Learning Projects**

A machine learning classification project that predicts whether a wine is of high quality (rating ≥ 7) based on its 11 physicochemical properties.

## 📌 Project Overview

This project explores dimensionality reduction using Principal Component Analysis (PCA), class imbalance handling and hyperparameter tuning to improve classification performance.

## 🛠️ Technologies Used

- Python
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn

## 📊 Project Workflow

- Data cleaning and exploratory data analysis (EDA)
- Correlation analysis and feature importance
- Feature scaling using StandardScaler
- Principal Component Analysis (PCA)
- Stratified K-Fold cross-validation
- Comparison of 24 model configurations
- Hyperparameter tuning using GridSearchCV
- Model evaluation

## 🤖 Models Implemented

- Logistic Regression
- Linear Support Vector Machine
- RBF Support Vector Machine
- Random Forest Classifier

## 🏆 Results

**Best Model:** RBF SVM with PCA retaining 95% variance and balanced class weights.

| Metric | Score |
|---|---:|
| Accuracy | 80.88% |
| Balanced Accuracy | 76.41% |
| Precision | 38.81% |
| Recall | 70.27% |
| F1 Score | 0.500 |

## 💡 Key Learnings

- PCA and explained variance
- Handling imbalanced datasets using class weights
- Preventing data leakage using pipelines
- Model optimisation through hyperparameter tuning
- Understanding why higher accuracy does not always mean better performance

## 🚀 Getting Started

Download the notebook and `winequality.csv` dataset, open the notebook in Google Colab or Jupyter Notebook, and run the cells sequentially.

---

**Part of my 100 Days 100 ML projects Series**

Learning machine learning, one project at a time 🚀
