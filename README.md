# Customer Lifetime Value Prediction using Probabilistic Models (BG/NBD & Gamma-Gamma)
## Executive Summary

In this project, using real retail transaction data from the UK market, customers with the highest profitability potential over the next 6 months were identified. The main objective was to shift the approach from historical analysis(RFM) to predictive analysis(CLV).

---
## Key Actions

**Data Cleaning:** Cleaning retail transaction data, removing returns, and normalizing data for the UK market.

**RFM Analysis:** Transforming purchase logs into behavioral matrices (Recency, Frequency, Monetary).

**Modeling:**

- Predicting churn rate and repeat purchase probability using the **BG/NBD** model.

- Predicting the average basket value using the **Gamma-Gamma** model.

**Business Impact:** Identifying the top 10 customers expected to generate the highest revenue and accurately calculating CLV while incorporating the discount rate (Time Value of Money).

**Technologies:** Python, Pandas, Lifetimes, Matplotlib, Seaborn.
