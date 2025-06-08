# Modeling Determinants of Antenatal Care Visits in Kenya using Poisson Regression

## Project Overview

This project explores the determinants of the *number of antenatal care (ANC) visits* among women in Kenya, using data from the *2022 Kenya Demographic and Health Survey (KDHS)*. 

The number of ANC visits is an important public health indicator linked to maternal and neonatal outcomes. Understanding the factors that influence ANC utilization can help inform health policy and interventions to improve maternal healthcare.

---

## Dataset

- Source: *2022 Kenya Demographic and Health Survey (KDHS)*
- Focused on: Women aged *15-49* who had a live birth within the *last 5 years*.
- Data Type: *Count data* — Number of ANC visits (dependent variable).

---

## Methodology

### Tools Used

- *Python* in *Jupyter Notebook*
- Libraries: pandas, numpy, statsmodels, matplotlib, seaborn, scipy

### Workflow

1. *Data Cleaning & Preparation*
    - Selected relevant variables from a dataset of 900+ columns.
    - Handled missing values and recoded categorical variables.
    - Focused on key independent variables:
        - Age group
        - Education level
        - Marital status
        - Wealth index
        - Place of residence
        - Time to nearest health facility
        - Place of delivery
        - Literacy level
        - Health decision-making autonomy
        - Parity
        - Self-reported health status

2. *Exploratory Data Analysis*
    - Frequency distributions
    - Visualizations (barplots, heatmaps, swarmplots)
    - Summary statistics

3. *Diagnostic Tests*
    - Overdispersion test
    - Multicollinearity check (correlation matrix)
    - Normality test
    - Autocorrelation check (Durbin-Watson statistic)
    - Zero-inflation check

4. *Modeling*
    - Fitted a *Poisson regression model* to model count data.
    - Interpreted model coefficients.
    - Presented results and visualizations.

---

## Key Findings

- Factors such as *education level, **marital status, and **place of delivery* were significant predictors of ANC visit counts.
- The Poisson model allowed for effective modeling of count data despite minor overdispersion.

---

## Why Python?

- Python was chosen for its *robust statistical libraries, flexibility in data manipulation, and ability to handle **large datasets efficiently*.
- The use of *Jupyter Notebook* allowed for seamless integration of code, visualizations, and interpretation.

---

## Disclaimer

This project was conducted using *secondary data* from the KDHS. The data was cleaned and analyzed for educational and academic purposes only. No sensitive individual data is shared.

---

## Author

*ANGEL LINAH ATUNGIRE*  
Statistician | Data Analyst 

---
