# CodeAlpha_TASK_1_CreditScoringModel
# Credit Risk Prediction using Machine Learning

## Project Overview

This project predicts whether an individual is creditworthy using machine learning techniques based on financial data such as age, income, job details, account balance, and credit history.

The project was developed as part of the CodeAlpha Machine Learning Internship program.

---

## Objective

To classify customers into credit risk categories using machine learning models and compare different algorithms for performance.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Joblib

---

## Dataset

German Credit Dataset

Features include:

- Age
- Job
- Housing
- Saving Accounts
- Checking Account
- Credit Amount
- Duration
- Purpose

---

## Data Preprocessing

- Missing value handling
- Label encoding
- Feature scaling
- SMOTE class balancing
- Train-test split

---

## Models Implemented

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Tuned Random Forest using GridSearchCV

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## Final Results

Final Model: Tuned Random Forest

Accuracy: 72%

The model was selected after comparing multiple algorithms and optimizing hyperparameters.

---

## Future Improvements

- Deploy using Streamlit
- Add SHAP explainability
- Improve minority class prediction
