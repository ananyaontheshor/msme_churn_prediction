# MSME Customer Churn Prediction
**Predicting whether a B2B logistics customer will reorder the following month**

## Context
During my internship at Tata nexarc, I built cohort dashboards on customer transaction 
data and observed significant variation in MSME retention patterns. This project 
investigates which operational signals best predict whether an MSME will place 
another order the following month.

## Dataset
9,500+ anonymised B2B logistics shipment records from Tata nexarc internship.  
All PII removed before analysis.

## Key Findings
- First-order customers churn at 73.5% — dominant predictor
- Non-key accounts churn at 52.7% vs 29.3% for key accounts
- SLA non-compliance raises churn from 36.6% to 43.0%
- GATI and Delhivery significantly outperform V-XPRESS on retention

## Model
Logistic regression classifier — 67% accuracy, 66% recall on churned customers.  
Outputs segmented into Low / Medium / High risk tiers for operational use.

## Tools
Python, pandas, sklearn, matplotlib, seaborn, Power BI