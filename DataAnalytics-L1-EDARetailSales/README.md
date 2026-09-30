# Task: EDA on Retail Sales Data
**Track:** Data Analytics (Level 1, Task 1) — Oasis Infobyte SIP
**Intern:** Kuldeep Singh

## Objective
Perform exploratory data analysis on a retail sales dataset to uncover patterns, customer
behaviour trends, and actionable business insights.

## Files
- `EDA_Retail_Sales.ipynb` — full notebook: data inspection, descriptive stats, time-series
  trends, demographics, product analysis, correlation heatmap, region×category heatmap, and
  business recommendations.
- `retail_sales_data.csv` — dataset used (synthetically generated with realistic seasonal and
  category patterns, since live Kaggle download wasn't available; the same steps apply directly
  to a real dataset like Kaggle's "Superstore Sales").

## Tech Stack
Python, pandas, matplotlib, seaborn, Jupyter Notebook

## Key Insights
1. Revenue spikes sharply in Q4 (festive season) and dips in February — plan inventory/marketing timing accordingly.
2. Electronics drives high revenue per order (premium/upsell focus); Grocery drives high order volume (loyalty/basket-size focus).
3. Category demand varies meaningfully by region — assortment should be localised, not one-size-fits-all.

## How to Run
Open `EDA_Retail_Sales.ipynb` in Jupyter Notebook / JupyterLab / VS Code and run all cells top to bottom.
