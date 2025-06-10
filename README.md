# Task6_elevatelabs
# Sales Trend Analysis Using PostgreSQL

## Objective:
Analyze monthly revenue and order volume using SQL aggregation techniques.

## Dataset:
- **File:** online_sales.csv
- **Columns:**
  - `order_id`: Unique ID
  - `order_date`: Date of order
  - `amount`: Revenue amount
  - `product_id`: Product reference

## Tools:
- PostgreSQL

## Key SQL Features Used:
- `EXTRACT(YEAR/MONTH FROM order_date)`
- `SUM()` for total revenue
- `COUNT(DISTINCT order_id)` for order volume
- `GROUP BY`, `ORDER BY`, and `LIMIT`
- Date filtering with `WHERE ... BETWEEN`

## SQL Queries Covered:
1. View entire dataset
2. Extract month/year from date
3. Monthly revenue and volume
4. Revenue between July-Dec 2023
5. Daily revenue trend
6. Monthly Average Order Value (AOV)
7. Top 5 revenue months
8. Orders per product per month
9. Product-wise yearly revenue
10. Revenue summary by quarter

## Output:
- SQL script and result screenshots
- Clean CSV file for database ingestion
  
- 📦 Deliverables

✅ 1. SQL Script
File: SQL_script.sql
Includes all 10 analytical SQL queries with proper formatting and comments:
Highlights:
Monthly revenue and order volume using GROUP BY and EXTRACT
Revenue trends filtered by date
Daily and monthly trends
Top 5 months by revenue
Product-wise and quarterly summaries

✅ 2. Screenshots & Results
File: queries+results_screenshots.pdf
Contains visual confirmation of:
Table creation
Each query's execution
Results preview for validation
