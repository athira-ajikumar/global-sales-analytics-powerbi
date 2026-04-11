# Global Sales Analytics | Power BI

## Overview

This project presents a multi-page **Power BI sales analytics report** built from the **Global Superstore** dataset. The dashboard is designed to help users analyze sales performance, profitability, customer behavior, product contribution, shipping efficiency, and regional trends across a global business footprint.

The report combines high-level executive KPIs with detailed views for year-over-year performance, customer and product intelligence, and customer-level drill-through analysis. It is intended for portfolio presentation, business insight generation, and interactive reporting practice in Power BI.

## Dashboard Summary

The report highlights the following headline metrics:

| Metric | Value |
| --- | ---: |
| Total Sales | 12.63M |
| Total Profit | 1.47M |
| Total Orders | 25,035 |
| Total Profit Margin | 11.60% |
| Sales YoY | 47.3% |

## Dashboard Pages

### 1. Executive Sales Overview

This landing page provides a concise business summary with:

- KPI cards for sales, profit, profit margin, order volume, and year-over-year growth
- Monthly sales trend analysis
- Category-wise sales comparison
- Regional sales comparison
- Top customers by sales
- Top-selling products with rank and profit margin
- Interactive slicers for **Year**, **Category**, and **Region**

### 2. Sales Performance - All Years

This page focuses on long-term performance tracking and operational analysis:

- Total sales by market
- Monthly sales compared with sales by ship date
- Year-over-year sales performance by year
- Shipping mode performance, including net profit after shipping and shipping cost ratios
- Year filter for focused annual analysis

### 3. Customer & Product Intelligence

This section is designed to uncover deeper commercial patterns:

- Cumulative sales growth over time
- Top customers by total sales
- Order-level profit details
- Category contribution to overall sales
- Category filter for targeted product analysis

### 4. Customer Drill-Through View

The report includes a detailed customer analysis page demonstrated through **Alan Dominguez**, featuring:

- Customer total sales, profit, profit margin, and order count
- Average customer discount
- Monthly sales and profit trends
- Customer order details
- Sales distribution by category
- Top products purchased by the selected customer

This drill-through design makes it easier to move from executive reporting to account-level analysis.

## Key Business Insights

- **Technology** is the highest-performing category, contributing approximately **4.74M** in sales.
- **APAC** is the top market by sales, followed by **EU**, **US**, and **LATAM**.
- Sales peak toward the end of the year, with **November** and **December** showing the strongest monthly performance.
- Among the shipping modes shown in the report, **Standard Class** delivers the strongest net profit after shipping, while faster shipping methods reduce profitability.
- The dashboard supports both broad strategic review and targeted customer investigation through interactive filtering and drill-through analysis.

## Dataset Information

The report is based on the [`Global_Superstore.xlsx`](./Global_Superstore.xlsx) dataset.

### Dataset profile

- Source file contains **51,290 transaction records**
- Covers **25,035 distinct orders**
- Includes **1,590 customers**
- Spans **147 countries**
- Covers order activity from **2011-01-01** to **2014-12-31**
- Organized in a single worksheet with **24 fields**

### Core data fields

The dataset includes dimensions and measures related to:

- Order details: `Order ID`, `Order Date`, `Ship Date`, `Ship Mode`, `Order Priority`
- Customer details: `Customer ID`, `Customer Name`, `Segment`
- Geography: `City`, `State`, `Country`, `Postal Code`, `Market`, `Region`
- Product details: `Product ID`, `Category`, `Sub-Category`, `Product Name`
- Measures: `Sales`, `Quantity`, `Discount`, `Profit`, `Shipping Cost`

## Repository Contents

This project repository is intended to include the following core assets:

- [`Global_Superstore.xlsx`](./Global_Superstore.xlsx) - source dataset used to build the report
- [`GlobalSales.pdf`](./GlobalSales.pdf) - exported PDF version of the dashboard
- Power BI `.pbix` file - editable source report for further development and exploration

## Tools and Techniques Used

- **Power BI Desktop**
- **Data modeling**
- **DAX measures**
- **Interactive slicers and filters**
- **Drill-through navigation**
- **KPI cards**
- **Line, bar, donut, and matrix visuals**

## Business Questions Addressed

This dashboard helps answer questions such as:

- How are sales and profit trending across months and years?
- Which categories, products, customers, and markets contribute the most revenue?
- How does shipping mode affect profitability?
- Which customers require deeper account-level analysis?
- How is total sales distributed across categories and regions?

## How to Use

1. Clone or download the repository.
2. Open the Power BI `.pbix` file in **Power BI Desktop**.
3. Verify the data source path for [`Global_Superstore.xlsx`](./Global_Superstore.xlsx) if required.
4. Use the slicers to filter by year, category, and region.
5. Navigate across the report pages to analyze executive metrics, yearly performance, product trends, and customer-level details.

## Outcome

This project demonstrates the use of Power BI to turn a large transactional dataset into a structured analytical experience. It showcases dashboard design, metric storytelling, interactive exploration, and practical business insight generation using a globally distributed sales dataset.
