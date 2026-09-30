# Task: Customer Segmentation Analysis
**Track:** Data Analytics (Level 1, Task 2) — Oasis Infobyte SIP
**Intern:** Kuldeep Singh

## Objective
Apply clustering to segment an e-commerce company's customers into distinct groups based on
purchasing behaviour, enabling targeted marketing strategies.

## Files
- `Customer_Segmentation.ipynb` — full notebook: RFM feature engineering, standardisation,
  elbow method, K-Means clustering (K=4), cluster visualisation, profiling, and marketing
  recommendations per segment.
- `ecommerce_transactions.csv` — dataset used (synthetically generated with 4 built-in customer
  archetypes so clustering recovers realistic, interpretable segments; the same workflow applies
  directly to a real dataset like the UCI "Online Retail" dataset).

## Tech Stack
Python, pandas, scikit-learn (KMeans, StandardScaler), matplotlib, seaborn, Jupyter Notebook

## Segments Found
- **Champions/Loyal** — frequent, recent, high spend
- **Occasional Shoppers** — moderate frequency/spend
- **One-Time Buyers** — single order, never returned
- **At-Risk/Lapsed** — used to buy, haven't ordered in months

## How to Run
Open `Customer_Segmentation.ipynb` in Jupyter Notebook / JupyterLab / VS Code and run all cells top to bottom.
