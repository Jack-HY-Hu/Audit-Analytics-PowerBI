<h1 align="center">
  <b>Audit Analytics Solution for AP Review Procedures</b>
</h1>

<p align="center">
  <img src="https://custom-icon-badges.demolab.com/badge/Power%20BI-F1C912?logo=power-bi&logoColor=fff">
</p>

1. Project Overview
2. Business Problem
3. Dashboard Features
4. Data Model
5. Files Included
6. Prerequisite Knowledge


# 1. Project Overview
This project is an end-to-end audit analytics dashboard built in Power BI using Accounts Payable and transaction-level invoice data.
The dashboard was designed to visualise Purchase to Pay transactions and hence to aid audit procedures commonly performed, including:
- Cut-off testing
- Aging analysis
- Unusual items review
- High-value transaction analysis
- Drill-through transaction inspection

The objective of the project was to demonstrate how I use Power BI to enhance audit efficiency and financial analysis through interactive data visualisation.

# 2. Business Problem
During external audits, auditors often manually inspect transactions around year-end, overdue payables, unusual balances, and high-risk invoices. This process is typically spreadsheet-driven and time-consuming.

This dashboard transforms these audit procedures into an interactive analytics solution that allows users to:
- dynamically adjust cut-off periods,
- change materiality thresholds,
- investigate transactions,
- and drill into invoice-level details.

By including the interactive elements, I have made it flexible to be catered to each specific client with different materiality levels.


# 3. Dashboard Features

1. Dynamic Cut-Off Testing

Interactive Features:
- Cut-off days selector
- Threshold slicer

Users can:
- Adjust cut-off window (X days before/after year-end) and select the desired threshold,
- Analyse transaction volumes around YE,
- Identify high-value transactions above threshold (highlighted automatically) near YE.
- Analyse transaction trend
- Analyse transaction amounts by vendor via the scatter chart
- Drill-through to Transaction Details directly


[sreenshot]


2. Accounts Payable Aging Analysis

The dashboard includes:
- aging bucket analysis,
- vendor-level aging review,
- overdue invoice tracking.

Users are able to drill-through to all the accounts payable to any supplier and to the summary of all the invoices in a certain age bucket.


[sreenshot]

<p align="center"><samp>
Below are the step-by-step walkthrough of how I built this Power BI report for AP Cut-off and AP Analysis (Ageing Analysis, Category Analysis) with further drill-through to transaction details possible
</samp></p>

# 4. Data Model

The project integrates:
- Accounts Payable listing
- Transaction listing
- Date dimension table

Relationships were established using:
- Invoice IDs
- Vendor names
- Date dimensions

[sreenshot]

# 5. Files Included
| File                                         | Description              |
| -------------------------------------------- | ------------------------ |
| Audit Analytics Solution for AP Review.pbit  | Power BI dashboard       |
| Modified_ dummy_AP_Listing_v2.csv            | Accounts Payable dataset |
| Modified_ dummy_Transaction_Listing_v2.csv   | Transaction dataset      |
| `README.md`                                  | Project documentation    |


P.S.
Example data presented in the project is fictional for illustration

# 6. Prerequisite Knowledge

Power BI
- Interactive dashboards
- Drill-down & drill-through
- Dynamic slicers
- Conditional formatting
- KPI cards
- DAX
- Measures
- Calculated columns
- Dynamic filtering
- Visualisation

Data Modelling
- Star schema
- Relationship modelling
- Date table creation

Finance Knowledge
- Cut-off testing
- Aging analysis
- AP review procedures
- Working capital analysis



