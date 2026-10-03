# Financial Transaction Analysis

## Overview

This portfolio project demonstrates how financial transaction data can be cleaned, validated, reconciled, analyzed, and presented for business reporting.

The project uses a **synthetic dataset** created specifically for portfolio purposes. It does not contain confidential company or client information.

## Business Questions

The analysis answers questions such as:

- How much was invoiced during the analysis period?
- How much has been collected?
- What is the outstanding balance?
- What is the overall collection rate?
- Which clients have the highest outstanding balances?
- Which transactions contain reconciliation discrepancies?
- Are there duplicate transaction references?
- How do invoiced, paid, and outstanding amounts change month by month?

## Tools

- Microsoft Excel
- Excel Pivot-style analysis and formulas
- Conditional formatting
- Excel charts
- CSV data

## Dataset

The dataset contains 120 synthetic financial transactions from January to June 2026.

Key fields include:

- `Transaction_ID`
- `Transaction_Date`
- `Client`
- `Service_Type`
- `Payment_Method`
- `Invoice_Amount`
- `Amount_Paid`
- `Outstanding_Balance`
- `Status`
- `Bank_Amount`
- `Reconciliation_Status`
- `Duplicate_Flag`
- `Variance`

## Analysis Process

1. Prepared and structured the transaction dataset.
2. Calculated outstanding balances.
3. Compared recorded payments with bank amounts.
4. Flagged reconciliation discrepancies.
5. Identified duplicate transaction references.
6. Summarized performance by month and client.
7. Created management-focused charts.
8. Documented findings and exceptions.

## Key Controls Demonstrated

### Reconciliation

`Variance = Amount_Paid - Bank_Amount`

Transactions with non-zero variance are flagged for investigation.

### Outstanding Balance

`Outstanding_Balance = Invoice_Amount - Amount_Paid`

### Collection Rate

`Collection Rate = Total Amount Paid / Total Invoice Amount`

## Portfolio Value

This project demonstrates practical skills relevant to:

- Data Analyst
- Business Intelligence Analyst
- Financial Data Analyst
- Finance Operations Analyst
- AI/Data Annotation and Evaluation roles

## Repository Structure

```text
financial-transaction-analysis/
│
├── data/
│   └── financial_transactions.csv
│
├── excel/
│   └── Financial_Transaction_Analysis.xlsx
│
├── charts/
│   ├── monthly_invoice_vs_paid.png
│   ├── outstanding_balance_trend.png
│   └── client_outstanding_balances.png
│
├── README.md
└── .gitignore
```

## Disclaimer

This project uses synthetic data for portfolio demonstration. No real client, employer, transaction, bank, or confidential financial information is included.


## Visualizations

### Monthly Invoice Amount vs Amount Paid

![Monthly Invoice Amount vs Amount Paid](charts/monthly_invoice_vs_paid.png)

### Outstanding Balance Trend

![Outstanding Balance Trend](charts/outstanding_balance_trend.png)

### Outstanding Balance by Client

![Outstanding Balance by Client](charts/client_outstanding_balances.png)
