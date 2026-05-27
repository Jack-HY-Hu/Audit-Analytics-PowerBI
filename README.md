<h1 align="center">
  <b>Audit Analytics Power BI</b>
</h1>

<p align="center">
  <img src="https://custom-icon-badges.demolab.com/badge/Power%20BI-F1C912?logo=power-bi&logoColor=fff">
</p>

1. Project Overview
2. Business Problem
3. Dashboard Features
4. Audit Procedures Covered
5. Technical Skills Demonstrated
6. Data Model
7. Dashboard Screenshots
8. DAX & Power BI Features
9. Key Insights
10. How to Use
11. Future Improvements

# Project Overview
This project is an end-to-end audit analytics dashboard built in Power BI using Accounts Payable and transaction-level invoice data.
The dashboard was designed to visualise Purchase to Pay transactions and hence to aid audit procedures commonly performed, including:
- Cut-off testing
- Aging analysis
- Unusual items review
- High-value transaction analysis
- Drill-through transaction inspection

The objective of the project was to demonstrate how I use Power BI to enhance audit efficiency and financial analysis through interactive data visualisation.

# Business Problem
During external audits, auditors often manually inspect transactions around year-end, overdue payables, unusual balances, and high-risk invoices. This process is typically spreadsheet-driven and time-consuming.

This dashboard transforms these audit procedures into an interactive analytics solution that allows users to:
- dynamically adjust cut-off periods,
- change materiality thresholds,
- investigate transactions,
- and drill into invoice-level details.

By including the interactive elements, I have made it flexible to be catered to each specific client with different materiality levels.


# Dashboard Features

1. Dynamic Cut-Off Testing
Users can:
adjust cut-off window (X days before/after year-end),
analyse transaction volumes around YE,
identify high-value transactions near YE.

Features:
Dynamic cut-off slicer
Transaction trend analysis
Drill-down by Year → Month → Day
High-value transaction highlighting
Transaction drill-through page

[sreenshot]


2. Accounts Payable Aging Analysis

The dashboard includes:
aging bucket analysis,
vendor-level aging review,
overdue invoice tracking.

Aging Buckets:
0–30 days; 31–60 days; 61–90 days; 91–120 days; 120+ days

[sreenshot]


3. Unusual Items Review

The dashboard identifies:
debit balance AP accounts,
unusual balances,
vendors requiring investigation.

[sreenshot]

<p align="center"><samp>
Below are the step-by-step walkthrough of how I built this Power BI report for AP Cut-off and AP Analysis (Ageing Analysis, Category Analysis) with further drill-through to transaction details possible
</samp></p>


# Other Dashboard Screenshots


# Files Included
| File                         | Description              |
| ---------------------------- | ------------------------ |
| `.pbix`                      | Power BI dashboard       |
| `AP_modified.xlsx`           | Accounts Payable dataset |
| `Transactions_modified.xlsx` | Transaction dataset      |
| `README.md`                  | Project documentation    |


P.S.
Example data presented in the project is fictional for illustration

Step 1:
Transform Data
- Change Type of certain columns

Step 2:
