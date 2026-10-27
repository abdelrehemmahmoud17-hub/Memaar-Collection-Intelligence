# Memaar-Collection-Intelligence
Real Estate Installment Collection &amp; Financial Risk Intelligence Dashboard built with Power BI, DAX, and data modeling.
# Memaar Al Morshedy | Collection Intelligence Dashboard

**Power BI | Real Estate Analytics | Financial Risk Intelligence**

## Project Overview

The Collection Intelligence Dashboard is a real estate financial analytics project designed to analyze installment collections, monitor collection performance, and support data-driven decision-making.

The project focuses on transforming installment payment records from multiple residential compounds into a structured analytical model and an interactive Power BI dashboard.

## Business Problem

Managing installment collections across multiple real estate compounds can be challenging when payment records are maintained in separate Excel files.

This creates several business challenges:

- Limited visibility into company-wide collection performance.
- Difficulty comparing collection progress across compounds.
- Challenges in distinguishing collected amounts from outstanding installments.
- Limited visibility into cash and bank-financed transactions.
- Time-consuming manual reporting and reconciliation.

## Project Objectives

- Consolidate installment collection data across multiple compounds.
- Monitor collection performance at company and project levels.
- Analyze issued installments and collected payments.
- Compare collection performance across residential compounds.
- Separate cash transactions from bank-financed transactions.
- Support financial monitoring and management decision-making.

## Tools & Technologies

- **Power BI Desktop:** Interactive dashboards and reporting.
- **Power Query (M):** Data cleaning, transformation, and preparation.
- **DAX:** Measures and analytical calculations.
- **Data Modeling:** Fact and dimension tables using a dimensional modeling approach.
- **Excel:** Source data preparation and validation.

## Data Model

The project uses a structured analytical model built around installment payments, contracts, units, customers, projects, banks, and dates.

Key model components include:

- `Fact_Installment_Pay` — installment and payment records.
- `Fact_Contract` — sales contract information.
- `Dim_Project` — residential compound information.
- `Dim_Unit` — unit details and engineering completion information.
- `Dim_Customer` — customer reference data.
- `Dim_Bank` — bank and financing classification.
- `Dim_Date` — date-based analysis.

The model is designed to support project-level comparisons, financial analysis, and time-based reporting.

## Key Performance Indicators (KPIs)

The dashboard is designed to monitor the following business metrics, subject to data validation and measure definitions:

- **Units Sold:** Number of sold real estate units.
- **Total Contract Value:** Total value of sales contracts.
- **Collection Rate:** Collected amount compared with the corresponding collectible or issued amount, according to the agreed business definition.
- **Collected Amount:** Total payments collected within the selected scope and period.
- **Outstanding Installments:** Amounts due but not yet collected, based on the applicable due-date rules.
- **Project Collection Performance:** Collection performance by residential compound.
- **Cash vs. Bank Financing:** Analysis of payment or financing categories.

> KPI values should be populated only after validating the underlying data, DAX measures, and reconciliation totals.

## Dashboard Design

The dashboard follows a black-and-gray visual identity designed to provide a professional financial reporting experience.

Planned analytical views include:

- Company-wide performance overview.
- Collection performance by compound.
- Installment issuance and collection analysis.
- Cash versus bank-financed transactions.
- Project-level financial monitoring.

## Business Insights & Recommendations

The dashboard is intended to help management:

1. Identify compounds with comparatively lower collection rates.
2. Prioritize follow-up on overdue installments.
3. Compare issued installments against collected payments.
4. Monitor differences between cash and bank-financed transactions.
5. Investigate discrepancies between source records and reported totals.
6. Use validated collection trends to improve collection planning.

Specific findings and recommendations should be added after validating the final dashboard results.

## Data Quality & Validation

The project emphasizes data reliability through:

- Checking missing and inconsistent values.
- Validating data types and payment classifications.
- Reconciling transformed data against source records.
- Reviewing installment issuance and collection totals.
- Verifying KPI calculations before publishing results.

## Project Scope

The source data covers multiple residential compounds, including One Kattameya, Zahra North Coast, Degla Landmark, Skyline Katameya, Degla Palms, Lake Front 6, Crystal Plaza Maadi, and Rihana.

The final reporting scope and completeness depend on successful data loading and validation of each source.

## Screenshots

Dashboard screenshots will be added here after preparing and validating the final report pages.

Suggested images:

- `images/home-dashboard.png`
- `images/collection-analysis.png`
- `images/project-performance.png`

## Disclaimer

This project is presented for portfolio and educational purposes. Any publicly shared screenshots or files must exclude confidential company information, customer personal data, and unauthorized financial records.

---

**Author:** Data Analyst Portfolio Project  
**Focus:** Power BI | Data Analytics | Financial Reporting | Business Intelligence
