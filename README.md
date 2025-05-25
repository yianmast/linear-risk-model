# 🧠 AI for Medical Prognosis – Week 1: Linear Risk Model for Diabetic Retinopathy

This project is the first assignment from the **AI for Medical Prognosis** course on Coursera, part of the AI for Medicine Specialization by deeplearning.ai. In this lab, we built and evaluated a linear risk model using logistic regression to predict diabetic retinopathy.

## 📊 Objective

Develop a model to assess the risk of diabetic retinopathy using patient data, including:
- Age
- Systolic and Diastolic Blood Pressure
- Cholesterol

## 🧪 Tasks Performed

- Data Preprocessing
  - Log transformation
  - Standardization (mean-zero, unit-variance)
- Model Building
  - Logistic Regression with sklearn
- Evaluation
  - C-index (Concordance index) to measure model discrimination
- Feature Engineering
  - Interaction terms between variables
- Model Interpretation
  - Analysis of coefficients and impact of interactions

## 📈 Key Metrics

- **C-index without interactions**: 0.8182  
- **C-index with interactions**: 0.8281

## 🛠 Technologies Used

- Python
- pandas, numpy, matplotlib
- scikit-learn
- scipy
