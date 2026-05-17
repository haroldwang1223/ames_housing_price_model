# Ames Housing Price Model

## Overview
This project analyzes housing sale prices in Ames, Iowa using multiple linear regression. The goal is to understand which housing characteristics are most associated with sale price and to evaluate the model's predictive performance on a held-out test set.

## Methods
- Data cleaning and feature preparation
- Train/test split
- Multiple linear regression
- Box-Cox transformations
- Multicollinearity checks using VIF
- Model comparison using AIC, BIC, and adjusted R-squared
- Influence diagnostics using Cook's distance, DFFITS, and DFBETAS
- Out-of-sample model evaluation using RMSE

## Key Result
The final model achieved a test RMSE of approximately $31,500, suggesting reasonable predictive performance while remaining interpretable.

## Tools
R, RMarkdown, ggplot2, dplyr, MASS, car

## Repository Structure
- `analysis/`: RMarkdown analysis file
- `data/`: cleaned dataset used for modeling
- `reports/`: final project report

## Notes
This is a cleaned portfolio version of a university project. The repository is organized to show the analysis workflow, modeling approach, and final report.
