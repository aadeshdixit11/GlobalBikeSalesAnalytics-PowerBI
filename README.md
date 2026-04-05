# Global Bike Sales Analytics – Power BI Dashboard

## Project Overview
This project provides a structured Power BI solution for analyzing sales data of a motor retail company operating across multiple countries.  
The dataset includes bikes, components, accessories, and clothing. The project demonstrates complete workflows including ETL, data modeling, DAX measures, and interactive reporting.

---

## Data Preparation & Modeling
- **ETL:** Conducted in Power Query for data cleaning and transformation.
- **Date Table:** Custom date table created for time intelligence.
- **Data Model:** Star schema design with relationships across:
  - Customers Table
  - Products, Categories, Subcategories
  - Final Sales Fact Table
  - Returns
  - Territories
  - Measure Table (centralized KPIs)
- **Custom Columns & Measures:**  
  Examples include:
  - %growthsales, %return, %oftotalYear, %sales  
  - Rolling averages (3‑month rolling average)  
  - Adjusted Sales, Average Margin, Average Selling Price  
  - Cumulative Sales, High Ticket Order Count  
  - Previous Month/Year Sales, Sales MTD, Yearly Totals  

---

## Reports
### 1. Sales Overview Dashboard
- KPIs: Total Sales, Orders, Return %, Sales Quantity
- Visuals:
  - Sales by Category and Income Level  
  - Sales by Country (map visualization)  
  - Trend analysis (Sum of Sales vs Adjusted Sales)  
  - Product performance table (sales, orders, returns)  
  - Goal tracking (monthly sales and orders vs targets)

### 2. Product Sales Drill‑Through Dashboard
- Product‑level insights:
  - Product price and cost  
  - Customer demographics (gender, marital status, parent status)  
  - Sales distribution by country and year  
  - Customer details table with individual contributions  
- Visuals:
  - Pie charts for sales by marital status and parent status  
  - Area chart for sales by year and country  

---

## Features
- Interactive filters (Year, Quarter, Category, Gender, Region, Email).
- Drill‑through functionality for product‑specific analysis.
- Centralized Measure Table for modular KPI management.
- Structured documentation for reproducibility.

---

## Tech Stack
- Power BI (Data Modeling, DAX, Visualization)
- Power Query (ETL)
- SQL/Pandas (optional preprocessing)

---

## Repository Contains
- GlobalBikesSalesReport.pbix
- SalesOverviewReportImage.png
- ProductSalesDrillThroughReport.png
- README.md  

---

## Key Learnings
- Designing dashboards with clear analytical storytelling.
- Building modular ETL pipelines in Power Query.
- Implementing drill‑through for product‑level analysis.
- Creating advanced DAX measures for KPIs and rolling trends.

---

## Author
**Aadesh Dixit**
**Data Analyst**
