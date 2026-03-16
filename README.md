# Predicting Fast-Growing Firms

**Course:** Data Analysis 3: Prediction and Introduction to Machine Learning  
**Authors:** Alina Imanakhunova, Sabira Onbayeva  
**Date:** February 2025

---

## Project Overview

This project develops predictive models to identify fast-growing firms using Bisnode panel data (2010-2015). We implement three classification algorithms with cost-sensitive threshold optimization to minimize expected economic loss.

**Methodology**

Fast growth is defined as firms belonging to the top 20% of sales growth over a two-year horizon (2012–2014).

Models Used:

1) Logistic Regression
2) Random Forest
3) Gradient Boosting 

Models are evaluated using:

- ROC-AUC
- Expected business loss based on asymmetric misclassification costs

**Main Results**

Gradient Boosting achieved the best overall performance and lowest expected business loss. The model prioritizes detecting fast-growing firms while balancing false alerts.  
Sector-specific analysis was also conducted separately for manufacturing and services industries.

---

## Reproducibility

To reproduce results:

- Clone the repository
- Install required Python packages: run `environment.yml` and activate environment
- Run notebooks in order:
    - `fast_growth_firm_prep.ipynb`
    - `predicting_fast_growth_firm.ipynb`
