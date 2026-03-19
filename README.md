# Revenue Leakage & Underpayment Analysis (Healthcare)

## Objective
To identify revenue loss due to underpayments by insurance companies and highlight opportunities for recovery and contract optimization.

---

## Dataset Overview
- Claim ID
- CPT Code
- Payer
- Expected Amount
- Paid Amount
- Contract Rate
- Payment Date

---

## Business Problems Solved
- Identified underpaid claims
- Highlighted CPT codes with highest revenue leakage
- Evaluated payer-wise underpayment trends

---

## Approach
- Calculated underpayment:
  
  Underpayment = Expected Amount - Paid Amount

- Analyzed:
  - Underpayment %
  - CPT-wise revenue loss
  - Payer-wise leakage

---

## Tools Used
- SQL (MySQL)
- Power BI
- Excel

---

## Key Insights
- 12% overall revenue loss due to underpayments
- Top 10 CPT codes contributed to 55% of leakage
- Certain payers consistently underpaid beyond contract rates

---

## Dashboard Features
- Total Revenue Leakage KPI
- CPT-wise Loss Analysis
- Payer-wise Underpayment
- Monthly Leakage Trend

---

## Business Impact
- Enabled identification of recoverable revenue
- Supported contract renegotiation strategy
- Improved financial transparency

---

## Repository Structure
- /data → Sample dataset
- /sql → SQL queries
- /dashboard → Power BI file (.pbix)
- /images → Dashboard screenshots

---

## Author
Rahul Vishwakarma
