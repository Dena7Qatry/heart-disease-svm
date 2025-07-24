# Heart Disease Classification using SVM

This project uses Support Vector Machine (SVM) to classify patients into two categories based on clinical features:
- `0`: No heart disease
- `1`: Presence of heart disease

## 📘 Project Overview

This notebook was developed as part of the **Intro to AI** course at BSBI. It walks through data cleaning, model building, hyperparameter tuning using GridSearchCV, and evaluation on a held-out test set.

## 🔍 Key Findings

- **Data Cleaning:**
  - No missing values were found.
  - Outliers in 'chol' and 'oldpeak' were clipped using winsorization (5th–95th percentile).
  
- **Model Optimization:**
  - Best SVM parameters from GridSearchCV:
    ```
    {'C': 1, 'gamma': 0.001, 'kernel': 'linear'}
    ```
  - Cross-validation accuracy: **0.839**

- **Final Model Evaluation on Test Set:**
  - Accuracy: **0.8524**
  - Precision: **0.96**
  - Recall: **0.75**
  - F1 Score: **0.8421**
  - AUC-ROC: **0.8577**

## 🚀 Next Steps

- Further hyperparameter tuning
- Try other algorithms (Random Forest, XGBoost, etc.)
- Feature engineering & PCA

## 📁 Files

- `heart_disease_svm_notebook.ipynb`: Full analysis and model
- `README.md`: Project description and results

## 🎓 Course

BSBI – Introduction to Artificial Intelligence
