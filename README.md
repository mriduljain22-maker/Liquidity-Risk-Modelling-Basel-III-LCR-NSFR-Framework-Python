# Liquidity Risk Modelling – Basel III LCR & NSFR (Python)

## Overview
This project builds a Liquidity Risk Analytics model in Python to evaluate bank liquidity using key Basel III regulatory metrics such as Liquidity Coverage Ratio (LCR) and Net Stable Funding Ratio (NSFR).

The model simulates a simplified bank balance sheet with assets and liabilities, calculates regulatory liquidity ratios, and evaluates liquidity resilience under stress scenarios.

## Objectives
- Model bank liquidity risk using Basel III metrics
- Calculate High Quality Liquid Assets (HQLA) with regulatory haircuts
- Estimate 30-day net cash outflows
- Perform liquidity gap analysis across maturity buckets
- Conduct liquidity stress testing scenarios

## Key Features

### High Quality Liquid Assets (HQLA)
Calculates HQLA by applying regulatory haircuts to different asset classes such as government securities, corporate bonds, equities, and cash reserves.

### Liquidity Coverage Ratio (LCR)
Measures short-term liquidity strength.

LCR = HQLA / Net Cash Outflows (30 days)

### Net Stable Funding Ratio (NSFR)
Evaluates long-term funding stability.

NSFR = Available Stable Funding / Required Stable Funding

### Liquidity Gap Analysis
Buckets assets and liabilities into maturity periods to identify funding mismatches.

Example buckets:
- 0–7 days
- 7–30 days
- 1–3 months
- 3–12 months

### Liquidity Stress Testing
Simulates stress scenarios by increasing asset haircuts and funding outflows to evaluate deterioration in liquidity metrics such as LCR.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib

## Applications
This project demonstrates practical liquidity risk analytics used by banks and financial institutions for:
- Basel III regulatory compliance
- Liquidity stress testing
- Bank treasury risk monitoring
- Balance sheet risk analysis

## Author
Mridul Jain, FRM  
Risk Analytics | Market Risk | Quantitative Finance  

LinkedIn:  
http://www.linkedin.com/in/mriduljainfrm
