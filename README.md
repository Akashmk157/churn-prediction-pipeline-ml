# 🔍 Customer Churn Prediction – Telecom Industry

A machine learning project to predict customer churn and uncover key behavioral patterns that drive customer retention. This case study is inspired by real-world telecom data.

---

## 🎯 Project Goal

To build a predictive model that identifies customers likely to churn, enabling telecom providers to take proactive steps in improving customer loyalty and reducing attrition.

---

## Project Structure

```text
1. Business Understanding
2. Data Understanding
3. Data Preprocessing
4. Model Development
5. Evaluation & Interpretation
6. Insights & Recommendations
```
---

## Dataset Summary
The dataset includes customer demographics, service subscriptions, billing information, and churn status.

Key Features:
- Demographics: Gender, SeniorCitizen, Partner, Dependents
- Services: InternetService, OnlineSecurity, TechSupport, StreamingTV, etc.
- Billing: Contract Type, Payment Method, MonthlyCharges, TotalCharges
- Target: Churn (Yes/No)

---

## Models Trained
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost (Best Performer)

---

## Evaluation Metrics
1. Accuracy
2. Precision
3. Recall
4. F1 Score
5. ROC AUC
--- 

## Model Explainability
Used SHAP (SHapley Additive exPlanations) to interpret model predictions.

### Top Churn Drivers:
- Contract Type
- Tenure
- Payment Method

## Key Insights
1) Customers on month-to-month contracts and using electronic checks are more likely to churn.
2) Longer tenure and automatic payments are associated with higher retention.
3) These insights can inform targeted retention strategies.

---

## Tech Stack
- Python (Pandas, NumPy, Scikit-learn, XGBoost, SHAP)
- Jupyter Notebooks
- Matplotlib / Seaborn for visualization
