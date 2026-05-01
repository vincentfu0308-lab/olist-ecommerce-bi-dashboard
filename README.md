# Olist E-Commerce Sales & Delivery Dashboard (MySQL + SQL + Power BI)

## Project Overview
This project is a SQL-first BI analytics project built on the Olist e-commerce dataset.  
It focuses on sales performance, delivery operations, and payment behavior by building a MySQL analytics workflow and a Power BI dashboard.

## Tools Used
- MySQL
- SQL
- Power BI
- MySQL Workbench

## Project Structure
- `sql/` – database schema, aggregations, views, and analysis queries
- `powerbi/` – Power BI dashboard file (.pbix)
- `screenshots/` – dashboard preview images

## Data Pipeline
1. Created MySQL database and tables for customers, orders, items, payments, products, and sellers
2. Imported CSV data into MySQL
3. Built aggregated tables and reporting views:
   - monthly_kpi
   - state_delivery_kpi
   - category_kpi
   - payment_kpi
4. Built a Power BI dashboard for KPI tracking and visual analysis

## Dashboard Highlights
- Monthly GMV trend
- Monthly order volume trend
- Late delivery rate by state
- Average delivery days by state
- Top categories by GMV
- Payment method distribution
- KPI cards: total GMV, total orders, average order value

## Key Insights
- Monthly GMV and order volume showed clear growth trends
- Delivery delays varied significantly across states
- Revenue was concentrated in a subset of product categories
- Payment method usage patterns differed across order segments
