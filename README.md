## AdventureWorks Sales Dashboard & Data Warehouse

### Project Overview

This project showcases a Star Schema Data Warehouse and an interactive Excel Sales Dashboard using AdventureWorks data. It consolidates sales, product, shipping, and territory data for actionable insights and strategic decision-making.

## Data Warehouse
### Fact Table

Fact_Order: SalesOrderID, SalesOrderDetailID, OrderQty, ProductID, LineTotal

### Dimension Tables

Dim_Territory: TerritoryID, Territory

Dim_ShipMethod: ShipMethodID, ShipMethod

Dim_Products: ProductID, Product, Color, SubCategory, Category

Dim_Date: Day Name, Year, Quarter, Month

Star Schema design ensures fast querying and optimal aggregation.

### Dashboard Overview

### KPIs

Total Sales: $2.93B

Orders: 31,465

Total Tax: $251.8M

Customers: 19,119

Territories: 10

### Charts

Sales per Category & Year

Sales per Territory

Top 10 Products

Best-Selling Categories per Territory

Orders per Category

Customers per Territory

Monthly Sales Trends

Filters / Slicers: Year, SubCategory, ShipMethod, Color

### Tools

Excel: Pivot Tables, Power Pivot, Charts, Slicers, Formulas

Data Modeling: Star Schema

### Purpose

Monitor sales performance

Identify trends & top products

Support data-driven decisions

### Usage

Open the Dashboard sheet, use slicers to explore data interactively, and analyze sales trends and KPIs.
