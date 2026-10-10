<img width="1005" height="565" alt="Dash overview" src="https://github.com/user-attachments/assets/c23d8e1d-7286-4533-9ca9-0db6b257d672" />
# 📊 Sales Performance Dashboard (Power BI)

An interactive Power BI dashboard that gives a clear overview of sales performance across years, products, channels, regions, and sales representatives.

## Key Metrics
- Total Sales
- Cost & COGS
- Profit
- Profit Margin

## Visuals
- **Total Sales by Year** (donut chart)
- **Total Sales by Category** (bar chart)
- **Sales vs. Cost vs. Profit per Quarter** (line chart)
- **Profit & Cost by Channel** (column chart)
- **Sales by Sales Rep Band** (column chart)
- **Detailed table** of orders by month, product, and order ID

## Filters (Slicers)
Region · Segment · Product · Sales Rep Age Range · Marital Status

## Data Model
Star-schema style model with a main `Sales All Years` fact table, linked to the dimension tables: `Product`, `Product - prices`, `Region`, `Segment`, `Channel`, and `SalesRep`.

## Tools
- Power BI Desktop
- DAX / Power Query

## How to Open
Download `Sales_-Green.pbix` and open it with Power BI Desktop.
