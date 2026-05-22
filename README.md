# Customer & Sales Analysis Dashboard

## Overview

Developed an interactive Power BI dashboard to analyze customer behavior, sales performance, regional sales trends, and deal size insights using Power BI, Power Query, and DAX

---

## Tools & Technologies Used

* Power BI
* Power Query
* DAX (Data Analysis Expressions)
* CSV Dataset

---

## Dashboard Features

* KPI Cards for:

  * Total Sales
  * Total Customers
  * Total Orders
* Sales by Product Line Analysis
* Country-wise Sales Analysis
* Yearly Sales Trend Analysis
* Deal Size Distribution Analysis
* Interactive Year Slicer
* Cross-filtering Dashboard Functionality

---

## DAX Measures Used

```DAX
Total Sales = SUM(sales_data_sample[SALES])

Avg Order Value = AVERAGE(sales_data_sample[SALES])

Total Orders = COUNTROWS(sales_data_sample)
```

---

## Key Insights

* USA generated the highest sales revenue.
* Classic Cars contributed the highest product sales.
* Medium deal size generated major revenue.
* Sales peaked during 2004.
* Interactive filtering enabled dynamic business analysis.

---

## Project Outcome

This project helped in understanding:

* Data Cleaning & Transformation
* Data Visualization
* Business Intelligence Reporting
* Interactive Dashboard Design
* DAX Calculations
* Cross-filtering in Power BI

---

## Files Included

* Customer_Sales_Analysis.pbix
* sales_data_sample.csv
* README.md

---

## Dashboard Preview

Interactive Customer & Sales Analysis Dashboard created using Power BI.
