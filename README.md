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
<img width="1310" height="735" alt="Screenshot 2026-03-26 223431" src="https://github.com/user-attachments/assets/f6de83ab-211c-4e76-8560-46080ce69ccd" />

<img width="1306" height="731" alt="Screenshot 2026-03-26 223444" src="https://github.com/user-attachments/assets/3c8f4a5f-8521-4257-b561-6648f0407b02" />


## Run It
```
pip install -r requirements.txt
python notebooks/Data_Cleaning and Feature_engineering.ipynb
python notebooks/Data_Modelling.ipynb
python notebooks/PowerBI Prep.ipynb
```


