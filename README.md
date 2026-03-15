# Retail Sales & Product Performance Analysis (Power BI)

## Project Overview

This project analyzes an online retail transaction dataset to understand **sales performance, product demand, customer behavior, and return patterns**. The goal is to transform raw transactional data into actionable business insights using **Power BI**.

The dashboard focuses on answering key business questions such as:

* How is revenue performing over time?
* Which countries generate the most revenue?
* Which products sell the most?
* Which products generate the least revenue?
* Which products have the highest return rates?
* How many customers and orders drive the business?

The analysis is divided into two dashboard pages:

* **Sales Performance**
* **Product Performance**

---

# Dataset

The dataset contains transactional retail data with the following fields:

| Column      | Description                |
| ----------- | -------------------------- |
| Invoice     | Unique transaction ID      |
| StockCode   | Product identifier         |
| Description | Product name               |
| Quantity    | Number of units purchased  |
| InvoiceDate | Date of transaction        |
| Price       | Unit price                 |
| Customer ID | Unique customer identifier |
| Country     | Customer country           |

Each row represents **one product within an invoice**, meaning a single invoice can contain multiple rows if multiple products were purchased.

## 1. Sales Performance

This page provides a high-level overview of business performance.

Key insights:

* Total revenue generated
* Total quantity sold
* Number of orders and customers
* Average order value
* Revenue distribution by country
* Monthly sales trends
* Revenue growth over time

Visualizations:

* KPI Cards
* Revenue by Country
* Monthly Sales Chart
* Revenue Over Time (Trend Analysis)

---

## 2. Product Performance

This page focuses on understanding product demand and return behavior.

Key insights:

* Top selling products by quantity
* Revenue contribution by product
* Products generating the lowest revenue
* Products with the highest return rates
* Total return quantity

Visualizations:

* Top Products by Quantity
* Product Revenue Distribution
* Lowest Revenue Products
* Top Products by Return Rate

---

# Key Business Insights

Some insights derived from the analysis include:

* A small group of products generates a significant portion of total revenue.
* Certain products show **high return rates**, indicating potential quality or customer expectation issues.
* Revenue is heavily concentrated in specific countries.
* Sales exhibit seasonal peaks across certain months.

These insights can help businesses improve **inventory planning, product quality, and marketing strategies**.

---

# Tools Used

* **Power BI** – Data modeling, DAX calculations, and dashboard creation
* **Excel / Power Query** – Data cleaning and preparation
* **DAX (Data Analysis Expressions)** – KPI and metric calculations

Abhay
Aspiring Data Analyst
