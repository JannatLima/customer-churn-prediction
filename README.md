# Customer Churn Prediction Using Machine Learning

## Project Overview

This project focuses on predicting customer churn in the telecommunications industry using machine learning techniques. The objective is to identify customers who are likely to discontinue their services and understand the factors associated with customer churn.

## Dataset

- **Dataset:** IBM Telco Customer Churn
- **Total records:** 7,043
- **Target variable:** Churn (Yes/No)
- **Input features:** 19

## Project Workflow

1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature encoding and scaling
5. Train-test splitting
6. Machine learning model development
7. Model evaluation and comparison
8. Feature importance analysis
9. Model explainability using SHAP

## Machine Learning Models

- Logistic Regression
- Random Forest
- XGBoost

## Model Performance

| Metric | Logistic Regression | Random Forest | XGBoost |
|---|---:|---:|---:|
| Accuracy | 80.55% | 78.28% | 80.55% |
| Precision | 65.72% | 61.89% | 67.24% |
| Recall | 55.88% | 47.33% | 52.14% |
| F1-score | 60.40% | 53.64% | 58.73% |
| ROC-AUC | 84.21% | 82.32% | 84.52% |

## Model Explainability

SHAP (SHapley Additive exPlanations) was used to understand the contribution of individual features to the XGBoost model's predictions.

The most influential features based on mean absolute SHAP values include:

- Contract type (Month-to-month)
- Tenure
- Monthly charges
- Online security
- Total charges
- Tech support
- Internet service
- Payment method

## Key Findings

- Month-to-month contracts have a considerably higher churn rate than longer-term contracts.
- Electronic check users have a relatively high churn rate.
- Fiber optic customers show a higher churn rate than DSL customers in this dataset.
- Logistic Regression achieved the highest recall and F1-score among the evaluated models.
- XGBoost achieved the highest ROC-AUC score.

## Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- SHAP

## Limitations and Future Work

The project uses a single public dataset and evaluates three machine learning models. Future work may include hyperparameter optimization, cross-validation, decision-threshold tuning, and external validation using additional datasets.

## Author

**Jannatul Ferdous Lima**

- GitHub: https://github.com/JannatLima
- LinkedIn: https://www.linkedin.com/in/jannatlima-cs/
