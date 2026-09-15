# SQL Sales Exploratory Data Analysis

An exploratory data analysis (EDA) project built with **PostgreSQL**. The analysis examines customers, products, and sales to produce business-ready metrics and identify sales, product, and customer patterns.

## Objectives

- Explore the database structure and available columns.
- Understand customers by country and gender.
- Examine product categories, subcategories, and costs.
- Measure sales performance through revenue, quantity, pricing, orders, products, and customers.
- Identify top and lowest-performing products and high-value customers.

## Dataset tables

| Table | Purpose |
| --- | --- |
| `customers` | Customer details such as name, country, gender, and birthdate. |
| `products` | Product details including category, subcategory, product name, and cost. |
| `sales` | Transaction-level sales data with order date, quantity, price, and sales amount. |

## Analysis included

1. **Database exploration** — retrieves metadata from `information_schema`.
2. **Dimension exploration** — lists customer countries and product hierarchies.
3. **Date exploration** — finds the sales date range and youngest/oldest customers.
4. **Measure exploration** — calculates total sales, quantity sold, average price, order count, product count, and customer count.
5. **Magnitude exploration** — analyzes customers, products, costs, revenue, and quantity by key dimensions.
6. **Ranking analysis** — finds top and bottom products, top customers by revenue, and customers with the fewest orders.

## Tools

- PostgreSQL
- pgAdmin 4

## How to run

1. Create or connect to a PostgreSQL database containing `customers`, `products`, and `sales`.
2. Open `sales_eda_postgresql.sql` in pgAdmin Query Tool.
3. Run queries section by section.

> The SQL file is an analysis script; it assumes the three dataset tables already exist and contain data.

## Author

Yash Jaiswal — Aspiring Data Analyst
