SQL Retail Sales Analysis (Project P1)
Executive Summary

Retail transaction data was analyzed using SQL to answer key business questions around sales performance, customer behavior, product categories, and order timing.
The project focuses on data cleaning, aggregation, and analytical querying to generate actionable retail insights from raw transactional data.

The output queries help stakeholders understand:

Which categories drive the most revenue

Who the top customers are

When orders are most frequent

Which months perform best each year

Business Questions Solved

Using SQL queries, the analysis answers:

Sales on specific dates

Category performance & total revenue

High-value transactions

Customer demographics by category

Top 5 customers by total spend

Unique customers per category

Transactions by gender & category

Best selling month per year (window functions)

Order distribution by time-of-day shifts

Methodology

Created database and retail_sales table

Cleaned data by removing NULL records in critical fields

Performed exploratory checks (counts, distinct categories, customers)

Wrote analytical SQL queries using:

Aggregations

Date & time functions

Window functions

CTEs

CASE logic for shift bucketing

Key SQL Skills Demonstrated

GROUP BY & aggregates (SUM, AVG, COUNT)

DISTINCT & customer segmentation

Window functions (RANK with PARTITION BY)

Date functions (EXTRACT, TO_CHAR)

Time-based bucketing with CASE

CTEs for structured analysis

Business-oriented query design

Results & Insights Enabled

The query set enables teams to quickly measure:

Revenue by product category

Customer concentration among top buyers

Seasonal best-performing months

Gender-category transaction mix

Order patterns by shift (Morning / Afternoon / Evening)

This supports faster reporting and reduces repeated ad-hoc analysis work.
