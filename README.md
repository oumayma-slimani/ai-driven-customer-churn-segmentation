# AI-Driven Customer Churn Prediction & Segmentation

Predictive analytics project to identify customers at risk of churn, segment user behavior, and translate machine learning insights into actionable business strategies.

---

## Executive Summary
Customer churn directly impacts revenue and long-term growth.  
In this project, I built a churn prediction model to estimate customer churn risk and used these predictions to create actionable customer segments.

A logistic regression model was used to generate churn probabilities for each customer. These risk scores, combined with behavioral and value-based features, enabled the identification of five distinct customer segments with significantly different churn patterns.

The results allow the business to prioritize retention efforts, focus on high-risk segments early in the customer lifecycle, and optimize retention spend.

---

## Business Problem
Customer churn leads to lost revenue and increased acquisition costs.  
The objectives of this project were to:

- Predict which customers are most likely to churn  
- Identify key behavioral drivers of churn  
- Design targeted, segment-specific retention strategies  

---

## Data & Tools
- **Data:** Customer subscription and billing data  
- **Python:** pandas, NumPy, scikit-learn  
- **Modeling:** Logistic Regression  
- **Segmentation:** KMeans clustering  

---

## Methodology

### Phase 1 — Exploratory Data Analysis (EDA)
- Analyzed churn distribution and key behavioral drivers
- Identified early-life customers and high-cost plans as higher churn risk

### Phase 2 — Predictive Modeling
- Built a logistic regression model to estimate churn probability
- Generated customer-level churn scores (`churn_proba`)
- Defined a business-adjustable churn threshold

### Phase 3 — Customer Segmentation
- Clustered customers using tenure, spend, and churn risk
- Identified five actionable customer segments
- Developed retention strategies tailored to each segment

---

## Key Insights
- Early-life customers exhibit the highest churn risk
- Senior customers show polarized churn behavior depending on tenure and plan cost
- Long-tenure customers are generally stable but still require monitoring when monthly charges are high
- Segment-based strategies enable more effective retention than one-size-fits-all approaches

---

## Business Recommendations
Based on churn risk and customer segmentation, the following actions are recommended:

- **Prioritize early-life high-risk customers** with proactive retention efforts during the first 30–60 days.
- **Design targeted retention strategies by segment** instead of applying uniform offers across the customer base.
- **Provide specialized support and simplified plans for senior high-risk segments** to reduce early churn.
- **Protect and upsell loyal high-value customers** through loyalty incentives and bundled offers.
- **Use churn probability scores to guide retention spend**, focusing resources where churn risk and customer value are highest.

---

## Repository Structure
churn-ai-segmentation/
├── notebooks/
│ ├── 01_eda_kpis.ipynb
│ ├── 02_modeling.ipynb
│ └── 03_segmentation.ipynb
├── data/
│ ├── raw/
│ │ └── telco.csv
│ └── processed/
│ ├── scored_customers.csv
│ └── phase3_segmented_customers.csv
└── README.md

---

## Results
The final output includes customer-level churn probabilities and segment labels that support data-driven retention decisions and targeted business actions.



