# Red Bull Sales & Marketing Analytics

An end-to-end portfolio project exploring sales, product, market, and
marketing campaign performance using **MySQL, SQL, Power BI, and DAX**.

> **Data note:** This project uses 10,000 synthetic transaction records
> covering January 2024 to October 2026. The dataset is created for
> portfolio and analytical practice; it is not actual Red Bull company
> data. Currency conversion rates are fixed project assumptions used to
> standardize values into USD.

## Project Objectives

-   Analyze sales revenue, units sold, gross profit, and profit after
    marketing.
-   Compare product and edition performance across countries and sales
    channels.
-   Evaluate campaign performance using marketing spend, conversions,
    and return on ad spend (ROAS).
-   Build an interactive Power BI dashboard for exploring performance by
    year, country, product, and sales channel.

## Tools Used

-   **MySQL / SQL** --- data validation, joins, aggregation, and
    analytical queries.
-   **Power BI** --- interactive dashboard and visual reporting.
-   **DAX** --- reusable measures and KPI calculations.
-   **CSV** --- source dataset.

## Repository Structure

``` text
Red-Bull-Sales-and-Marketing-Analytics/
├── Datasets/
│   └── red_bull_10k_sales_marketing_dataset_jan2024_oct2026.csv
├── Power BI/
│   ├── Red_Bull_Sales_Marketing_Analytics.pbix
│   └── Red_Bull_Sales_Marketing_Analytics.pdf
├── Project Documentation/
│   └── Red_Bull_Project_Documentation.docx
├── SQL/
│   └── Red_Bull_Sales_Marketing_Analytics.sql
└── README.md
```

File names may vary slightly depending on the uploaded versions.

## Project Workflow

1.  Loaded the transaction dataset into MySQL.
2.  Checked record counts, date coverage, duplicate transaction IDs,
    missing values, and invalid sales values.
3.  Created a currency-rate table and joined it to the sales data.
4.  Created a SQL view with USD-normalized revenue, product cost, gross
    profit, marketing spend, and profit after marketing.
5.  Wrote SQL queries to analyze products, countries, channels, customer
    segments, campaigns, and monthly/yearly trends.
6.  Connected Power BI to the SQL view and created DAX measures.
7.  Built a four-page interactive dashboard.

## Dashboard Pages

### 1. Executive Overview

-   Total Revenue
-   Gross Profit
-   Profit After Marketing
-   Units Sold
-   Marketing Spend
-   ROAS
-   Monthly revenue trend and revenue by product

### 2. Product Performance

-   Product sales and profitability KPIs
-   Top-selling products
-   Product performance across global markets

### 3. Market Performance

-   Country-level revenue, gross profit, profit margin, and units sold
-   Country performance comparison

### 4. Marketing Performance

-   Revenue versus marketing spend by campaign
-   ROAS by campaign
-   Campaign performance matrix, including impressions, clicks, and
    conversions

## Key Metrics

-   **Net Revenue:** Gross revenue after discounts.
-   **Gross Profit:** Net revenue minus product cost.
-   **Profit After Marketing:** Gross profit minus marketing spend.
-   **Profit Margin:** Gross profit divided by net revenue.
-   **ROAS (Return on Ad Spend):** Revenue divided by marketing spend.
-   **CTR (Click-Through Rate):** Clicks divided by impressions.
-   **Conversion Rate:** Conversions divided by clicks.

## Interactivity

The dashboard includes slicers for **Year, Country, Product, and Sales
Channel**, allowing users to explore different parts of the dataset.

## Important Limitations

-   The transactions and marketing metrics are synthetic, not real
    company records.
-   Currency rates are fixed assumptions for this project, not
    historical exchange rates.
-   The 2026 dataset covers January through October only, so 2026 totals
    should not be compared with full-year totals without accounting for
    the shorter period.
-   Results demonstrate analytical methods and should not be interpreted
    as official Red Bull business findings.

## Purpose

This project demonstrates an end-to-end analytics workflow, from
SQL-based data validation and analysis to currency normalization and an
interactive Power BI dashboard.
