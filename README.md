# Customer Churn Analysis

## Overview
End-to-end customer churn prediction using Python, SQL and Power BI on Telco dataset (7043 customers).

## Key Insights
- Overall churn rate: **26.6%**
- Month-to-month contracts have **42% churn rate** vs 3% for two-year contracts
- Churned customers have avg tenure of **18 months** vs 38 months for retained
- High monthly charges (>$70) customers are at highest risk

## Retention Strategies
1. Offer discounted annual plans to new month-to-month customers in first 3 months
2. Loyalty rewards for high-paying customers
3. Bundle OnlineSecurity & TechSupport for at-risk segments

## Model Performance
| Model | Accuracy | AUC |
|---|---|---|
| Logistic Regression | 79.5% | 0.835 |
| Random Forest | 78.3% | 0.811 |
| XGBoost | 76.5% | 0.804 |

## Tech Stack
Python • Pandas • Scikit-learn • XGBoost • Matplotlib • Seaborn • Power BI