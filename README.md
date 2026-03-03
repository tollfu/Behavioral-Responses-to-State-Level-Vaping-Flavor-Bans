# Behavioral-Responses-to-State-Level-Vaping-Flavor-Bans



## Overview
---

This project evaluates the causal impact of state-level e-cigarette flavor bans on vaping and related substance use behaviors among individuals under 30 using BRFSS data (2016–2023).

The analysis replicates and extends prior literature by incorporating newly available years of data, introducing mental health heterogeneity, and implementing multiple robustness checks.

---

## Research Question
---

Do state-level ENDS flavor bans reduce vaping, and do they generate unintended spillover effects to other substances across different mental health subgroups?

---

## Data
---

- Behavioral Risk Factor Surveillance System (BRFSS), 2016–2023  
- Covid Deaths by State/Month
- Unemployment Rate by State/Month 
- Combustible Cigarette Tax by State/Month

---

## Methodology
---

The empirical strategy includes:

- Two-way fixed effects Difference-in-Differences (state and year FE)  
- Logit and Linear Probability Models (OLS/WLS)  
- Event-study specification for dynamic treatment effects  
- Post-double-selection Lasso for covariate robustness  
- Clustered standard errors at the state level  

Subgroup heterogeneity is analyzed using mental health categories based on reported poor mental health days in a month (0 - 31).

---

## Key Findings
---

- Flavor bans are associated with a statistically significant reduction in current vaping.  
- The reduction is largest among individuals reporting good mental health and diminishes among those with frequent mental distress.  
- Evidence suggests spillover increases in combustible cigarette and chewing tobacco use.  
- No statistically significant spillovers are detected for binge drinking or marijuana use.  
- Core DiD results are robust across OLS, logit, and Lasso specifications.  

---

## Limitations
---

- BRFSS does not distinguish flavored vs. unflavored ENDS products.  
- Limited time variation affects event-study precision.  
- Youth-specific survey data (YRBS) unavailable at the state level.  

---

## Repository Contents
---

- `Research Paper-To What ENDS-Shaoyi Yu.pdf` — Full paper with tables and figures
- Data cleaning process embedded in python script `data cleaning.ipynb`  
- Tables/Figures/Regression results/Subgroup analyses embedded in python script `regression run.ipynb`

