# Predicting-10-Year-Coronary-Heart-Disease-CHD-Risk
This repository contains the full analysis, code, and report of a project, where I build and evaluate several supervised learning models to predict the 10-year risk of Coronary Heart Disease (CHD). The project follows methodologies from An Introduction to Statistical Learning (ISLP, 2023) and uses real clinical data from the Framingham Heart Study.

---

## 🚀 Overview
- Data preprocessing and cleaning  
- Handling class imbalance (SMOTE + class weights)  
- Models used: Logistic Regression, SVM, Random Forest, XGBoost, LightGBM  
- Evaluation metrics: Accuracy, ROC-AUC, Recall, F1-score  
- Feature importance analysis and interpretability

---

## 📊 Key Findings
- **Logistic Regression** achieved the highest recall, making it the most clinically reliable model.  
- Tree-based models showed high accuracy but low recall due to class imbalance.  
- Most influential predictors: **Age**, **SysBP**, **BMI**, **Glucose**, **Prevalent Hypertension**, **CigsPerDay**, **Total Cholesterol**.

---

## 📚 Dataset
Framingham Heart Study  
🔗 https://www.framinghamheartstudy.org/

---

## 📖 References
- James, Witten, Hastie & Tibshirani (2023), *An Introduction to Statistical Learning*  
- Python Software Foundation (2024)

---

