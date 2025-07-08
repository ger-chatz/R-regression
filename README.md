# Simple Linear Regression in R

## Overview

This is a basic linear regression example in **R**, using real hematological data from 20 patients. The goal is to predict **hemoglobin levels (HB)** based on variables like **hematocrit (HT)**, **MCH**, and **MCV**.

Developed as part of coursework in the MSc in Applied Statistics (AUEB).

---

## What It Shows

- How to fit simple and multiple linear regression models using `lm()`
- Interpretation of coefficients and p-values
- Use of **Adjusted R²** and **AIC** for model comparison
- Application of:
  - The linear model form: `Y = β₀ + β₁X₁ + ... + βₚXₚ + ε`
  - Model selection via `step()`
  - Confidence intervals and residual diagnostics

---

## Key Output

Final model:
```r
lm(HB ~ HT + MCH + MCV)
Adjusted R² = 0.727

