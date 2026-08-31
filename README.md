# Credit Card Fraud Detection & Risk Analysis

## Project Overview

This project is an Excel-based Credit Card Fraud Detection and Risk Analysis model designed to identify transaction patterns associated with fraudulent activity and classify transactions into Low, Medium, and High Risk categories.

## Objective

The objective of this project is to analyze historical transaction data, identify key fraud risk indicators, and convert those findings into a dynamic and interpretable risk scoring model.

## Key Risk Factors

The analysis focuses on:

- Transaction Amount
- Transaction Hour
- Foreign Transactions
- Location Mismatch
- Device Trust Score
- Transaction Velocity
- Merchant Category

## Risk Analysis

Fraud rates were calculated across different transaction segments and compared with baseline fraud rates.

Risk multipliers were then used to identify which transaction characteristics showed stronger relationships with fraud.

## Risk Scoring Model

Each transaction receives a risk score based on multiple fraud indicators.

### Risk Points

- 3 points = Strong risk signal
- 2 points = Moderate risk signal
- 1 point = Mild risk signal
- 0 points = No significant additional risk

### Risk Classification

| Risk Level | Score Range |
|---|---:|
| Low Risk | 0–5 |
| Medium Risk | 6–7 |
| High Risk | 8–19 |

The scoring rules are maintained separately in lookup tables, making the model dynamic and easier to update.

## Excel Functions Used

- XLOOKUP
- IFS
- IF
- COUNTIF
- COUNTIFS
- SUM
- SUMIFS
- AVERAGEIFS
- Excel Tables
- Structured References

## Key Findings

- Overall historical fraud rate was 1.51%.
- Device Trust was one of the strongest fraud indicators.
- Transactions above ₹1,000 showed higher fraud risk.
- 5–6 transactions within 24 hours showed a strong fraud signal.
- Foreign transactions and location mismatches were associated with higher fraud rates.
- Fraud risk varied across transaction hours and merchant categories.

## Dashboard

The Excel dashboard presents:

- Total Transactions
- Fraud Transactions
- Overall Fraud Rate
- Total Transaction Amount
- Fraud-rate analysis
- Risk-level analysis
- Key Fraud Risk Drivers
- Key Outcomes

## Tools

**Microsoft Excel | Data Analysis | Risk Scoring | Dashboarding**

## Final Outcome

Built a dynamic, rule-based fraud risk model that converts transaction characteristics into an interpretable risk score and classifies transactions into Low, Medium, and High Risk categories.
