# Project Overview — Loan Default Risk Analysis

## Purpose

Explore a loan dataset containing borrower demographics, financial attributes, loan characteristics, and a default indicator. The report is organized into three pages to support overview, profile analysis, and financial-risk exploration.

## Business Questions Explored

- How does loan amount vary by loan purpose and applicant group?
- How do income and loan characteristics vary across employment and age categories?
- How are credit-score groups represented across applicant and loan attributes?
- How do the report's default-related and loan-amount metrics vary by year?
- How do selected financial indicators compare across borrower categories?

These are questions explored by the dashboard, not claims of causal relationships or predictive performance.

## Tools and Responsibilities

| Tool | Use in this project |
|---|---|
| SQL Server | Database and table setup; source data access |
| SSMS | Connect to SQL Server and access/inspect tables |
| Power BI Desktop | Import data, build report model and visuals |
| Power Query Editor | Further data cleaning, formatting and transformation |
| DAX | Measures and calculations used in the report |

## Report Pages

1. **Loan Default and Overview** — overview of loan amount by purpose, average income by employment type, average loan amount by age group, and default rate by year.
2. **Applicant Demographics and Financial Profile** — credit-score groupings, average loan amount across age/marital categories, loan amount by credit-score group, mortgage/dependent comparisons, and education/employment breakdowns.
3. **Financial Risk Metrics** — year-over-year loan amount and default-related change, year-to-date loan amount, and applicant/credit-score comparisons.

## Dataset Snapshot

- Rows: 255,347
- Columns: 19
- Default indicator: `Default`
- Date field: `Loan Date (DD/MM/YYYY)`

The date field's name and sample values appear inconsistent. Values such as `10/15/2018` suggest month/day/year formatting. Confirm the Power Query locale and resulting data type before documenting date transformation details or drawing date-based conclusions.

## Important Scope Note

SQL Server and SSMS were used to create/access the database tables and inspect the data. The described cleaning, formatting, and transformation work was performed in Power Query Editor. Do not describe this as SQL-based data cleaning unless actual SQL cleaning queries are available and verified.
