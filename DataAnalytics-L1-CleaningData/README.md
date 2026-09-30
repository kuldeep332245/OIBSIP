# Task: Cleaning Data
**Track:** Data Analytics (Level 1, Task 3) — Oasis Infobyte SIP
**Intern:** Kuldeep Singh

## Objective
Take a deliberately messy dataset and systematically transform it into a clean, analysis-ready
dataset, documenting every decision.

## Files
- `Data_Cleaning.ipynb` — full notebook: data quality report, duplicate removal, categorical
  standardisation, mixed date-format parsing, IQR outlier detection, missing-value imputation,
  dtype correction, and a before/after summary table.
- `messy_employee_data.csv` — the raw, deliberately messy dataset (nulls, duplicates,
  inconsistent gender labels, 3 different date formats, invalid outlier salaries).
- `cleaned_employee_data.csv` — the final cleaned output.

## Tech Stack
Python, pandas, numpy, Jupyter Notebook

## Cleaning Decisions (summary)
- Exact duplicate rows dropped.
- Gender labels (`Male`, `male`, `M`, `MALE`, ...) standardised to 2 canonical values.
- Join dates parsed across 3 mixed formats (`YYYY-MM-DD`, `DD/MM/YYYY`, `DD-Mon-YYYY`).
- Salary outliers (negative / absurdly large) detected via IQR, nulled, then median-imputed.
- Age/Salary → median imputation; Department → mode imputation; rows with missing JoinDate dropped.

## How to Run
Open `Data_Cleaning.ipynb` in Jupyter Notebook / JupyterLab / VS Code and run all cells top to bottom.
