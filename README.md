# 📈 Retail Sales Time Series Forecasting

> **Note:** The source code comments and the detailed analytical report within the `.Rmd` file are written in Czech, as this was a university semester project.

👉 **[View the Interactive HTML Report here](https://htmlpreview.github.io/?https://github.com/Shehabaddin-Alnahari/retail-time-series-analysis/blob/main/%C4%8Casov%C3%A9_%C5%99ady_semestr%C3%A1ln%C3%AD_pr%C3%A1ce.html)**

## 🎯 Project Overview
Comprehensive time-series analysis and forecasting of Czech retail sales data using R. The project systematically compares deterministic models, stochastic Box-Jenkins methodology (SARIMA), and dynamic regression models with external regressors to find the optimal forecasting approach.

## ⚙️ Methodology
* **Data Extraction:** Automated retrieval of open government datasets using the `czso` API.
* **Spectral Analysis & Decomposition:** Identifying hidden seasonal cycles and trends using moving averages and periodograms.
* **SARIMA Modeling:** Removing autocorrelation and stabilizing the random component.
* **Dynamic Regression:** Incorporating food retail sales as an external regressor based on cross-correlation function (CCF) results, achieving strict white-noise residuals.

## 🛠️ Technologies & Packages
* **R** (`forecast`, `tidyverse`, `TSA`, `czso`)