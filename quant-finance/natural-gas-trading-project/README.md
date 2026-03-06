# Natural Gas Trading & Storage Quant Project

This project simulates a workflow of a quantitative researcher supporting a commodity trading desk.

The project includes four tasks covering pricing, forecasting, and risk modeling.

---

# Task Overview

## Task 1 — Natural Gas Price Modeling

Built a seasonal regression model to estimate historical and future natural gas prices.

Key techniques:

- Time index feature engineering
- Seasonal sine/cosine features
- Linear regression forecasting

---

## Task 2 — Storage Contract Pricing

Developed a prototype model to evaluate the value of a natural gas storage contract.

Model considers:

- Injection dates
- Withdrawal dates
- Storage capacity
- Injection/withdrawal rate
- Storage costs

---

## Task 3 — Credit Risk Modeling

Built a predictive model estimating borrower probability of default (PD).

Used borrower features including:

- Income
- Loan balance
- Financial metrics

Output:

- Probability of default
- Expected loss estimation

---

## Task 4 — FICO Score Bucketing

Implemented a quantization method mapping continuous credit scores into categorical risk buckets.

Methods explored:

- Mean squared error optimization
- Log-likelihood optimization
