# Credit Risk Analysis
August 2, 2025
A simple Excel tool that calculates a **Credit Reliability Score** based on a user's key financial indicators, such as age, income, and debt-to-income (DTI) ratio

## Overview

This tool helps assess an individual's credit reliability using a custom scoring formula. It's useful for:
- Educational purposes
- Personal finance exploration
- Early-stage prototyping of underwriting models

## Inputs

The user must enter the following data into the respective columns:

| Input Field     | Description                                   |
|-----------------|-----------------------------------------------|
| **Credit Score**| FICO score (300–850)                          |
| **Age**         | Age in years (numeric)                        |
| **Income**      | Annual income in USD                         |
| **DTI Ratio**   | Debt-to-Income ratio as a decimal (e.g., 0.35)|

---

## Output

The tool returns a **Credit Reliability Score** (out of 100) based on weighted inputs.

Scoring logic (can be adjusted):
- Credit Score: 50% weight
- Income: 25% weight
- DTI: 20% weight (inverse relationship)
- Age: 5% weight

The formula is implemented directly in Excel using built-in functions.
