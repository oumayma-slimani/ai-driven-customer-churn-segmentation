# ai-driven-customer-churn-segmentation
Predictive analytics project to model customer churn, segment users, and translate ML insights into business actions.

# AI-Driven Customer Churn Prediction & Segmentation

## Executive Summary
This project analyzes customer churn behavior and designs targeted retention strategies using machine learning and customer segmentation.

A logistic regression model was built to estimate churn probability for each customer. These risk scores were combined with behavioral and value-based features to segment customers into actionable groups with distinct churn patterns.

The results enable the business to prioritize retention efforts and allocate resources more effectively.

---

## Business Problem
Customer churn negatively impacts revenue and long-term growth.  
The objective of this project is to:
- Predict which customers are most likely to churn
- Understand churn drivers
- Design segment-specific retention strategies

---

## Data & Tools
- **Data:** Customer subscription and billing data
- **Python:** pandas, NumPy, scikit-learn
- **Modeling:** Logistic Regression
- **Segmentation:** KMeans Clustering

---

## Methodology

### Phase 1 — Exploratory Data Analysis (EDA)
- Analyzed churn distribution and key behavioral drivers
- Identified early-life and high-cost customers as higher churn risk

### Phase 2 — Predictive Modeling
- Built a logistic regression model to estimate churn probability
- Generated customer-level churn scores (`churn_proba`)
- Created a business-adjustable churn threshold

### Phase 3 — Customer Segmentation
- Clustered customers using tenure, spend, and churn risk
- Identified five actionable customer segments
- Designed targeted retention strategies for each segment

---

## Key Insights
- Early-life customers show the highest churn risk
- Senior customers exhibit polarized churn behavior
- Long-tenure customers are generally stable but require monitoring
- Segment-based strategies outperform generic retention actions

---

## Repository Structure

