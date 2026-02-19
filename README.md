# 📊 COVID-19 Lockdown Event Study – Indian Markets

## Overview

This project analyzes the impact of India’s COVID-19 lockdown announcement (24 March 2020) on selected Indian equities using an event study methodology.

The objective was to isolate stock-specific abnormal returns after controlling for overall market movement.

---

## What I Did

- Collected and cleaned historical equity data using `yfinance`
- Computed daily log returns and rolling volatility
- Estimated expected returns using OLS (Market Model)
- Calculated abnormal returns and Cumulative Abnormal Returns (CAR)
- Performed statistical significance testing (t-tests)
- Visualized sectoral differences in market reaction

---

## Key Insights

- Banking stocks exhibited sustained negative abnormal returns.
- IT stocks demonstrated faster stabilization post-lockdown.
- Reliance showed strong positive cumulative abnormal performance.
- Volatility spiked sharply around the announcement date.

---

## Tools & Techniques

**Python | pandas | numpy | statsmodels | scipy | matplotlib**

Concepts applied:
- Event Study Framework
- OLS Regression
- Market Model (CAPM-style)
- Hypothesis Testing
- Time-Series Analysis

---

## Why This Project Matters

This analysis demonstrates the ability to:
- Build end-to-end data pipelines
- Apply econometric modeling
- Interpret financial time-series data
- Extract statistically meaningful insights from real-world events
