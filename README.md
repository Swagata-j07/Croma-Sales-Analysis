# SQL Project: Finance and Supply Chain Analytics

## 

This project leverages SQL to track finance and supply chain performance for Croma India. It helps analyze sales trends, check forecast accuracy, and spot key patterns in customer purchases and product sales.

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Database Schema](#database-schema)
- [Queries and Stored Procedures](#queries-and-stored-procedures)
- [Sales Reports](#sales-reports)
- [Top Customers, Products, Markets](#top-customers-products-markets)
- [Supply Chain Analytics](#supply-chain-analytics)

## 🔑 Key Features:

- Identification of **top-performing customers, products**, and **markets**.
- Assessment of **supply chain efficiency** and **forecasting accuracy**.
- Calculation of **gross sales**, **net sales**, and **deductions**.
- Product-wise **sales reports** for multiple fiscal years and quarters.

## 🗂️ Database Schema

This project works with the following tables in the database:

| **Table Name**                     | **Description**                              |
|-------------------------------------|----------------------------------------------|
| `fact_sales_monthly`               | Monthly sales data for all products.        |
| `dim_product`                      | Product details including ID and name.      |
| `fact_gross_price`                 | Product pricing data.                       |
| `dim_customer`                     | Customer-related data.                      |
| `fact_pre_invoice_deductions`      | Pre-invoice deductions for products.        |
| `fact_post_invoice_deductions`     | Post-invoice deductions for products.       |
| `fact_act_est`                     | Forecasted vs. actual sales data.           |
| `dim_date`                         | Date-related data, including day, month, year, etc. |
| `fact_manufacturing_cost`          | Data related to manufacturing costs.        |
| `fact_forecast_monthly`            | Monthly sales forecast data.                |
| `fact_freight_cost`                | Data related to freight and shipping costs. |










