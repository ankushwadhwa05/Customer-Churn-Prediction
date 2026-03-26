# Customer Churn Prediction & Retention Strategy
> Telecom churn analysis with business segmentation, revenue 
> risk quantification, and retention ROI modelling.

## Business Problem
A telecom company is losing 26.5% of its customers annually, 
representing $1.67M in revenue at risk. The goal: predict 
which customers will churn, segment them by value, and 
recommend where to spend the retention budget.

## Key Results
| Metric | Value |
|--------|-------|
| Best Model (XGBoost) ROC-AUC | 0.85+ |
| Annual Revenue at Risk Identified | $1.67M |
| High Value + High Risk Customers | [X] |
| Recommended Retention ROI | [Y]% |

## What Makes This Different
Most churn projects stop at model accuracy. This one goes further:
- Segments churners by CLTV into Low / Mid / High value tiers
- Calculates exact revenue at risk per segment
- Computes retention ROI — recommends where NOT to spend budget
- Delivers findings as a Power BI dashboard + consultant memo

## Stack
Python · scikit-learn · XGBoost · pandas · SQL · Power BI

## Dashboard Preview
[screenshot of your Power BI dashboard here]

## Run It
pip install -r requirements.txt
python src/01_eda_cleaning.py
python src/02_feature_engineering.py
python src/03_modeling.py
python src/04_powerbi_prep.py
```

**requirements.txt:**
```
pandas==2.0.3
numpy==1.24.3
scikit-learn==1.3.0
xgboost==1.7.6
matplotlib==3.7.2
seaborn==0.12.2
