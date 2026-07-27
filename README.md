# 📊 Dynamic Sales Performance Dashboard | Power BI & Excel

## Project Overview

This project demonstrates the development of an interactive sales performance dashboard using **Power BI** and **Microsoft Excel** to analyze fictional company sales data. The objective was to transform raw transactional data into meaningful business insights, enabling users to monitor performance, identify trends, and support data-driven decision making.

---

## Business Problem

Business stakeholders needed an interactive reporting solution to:

- Monitor sales performance across multiple dimensions
- Compare current and prior year results
- Identify underperforming regions and products
- Evaluate customer profitability
- Track key performance indicators (KPIs) in real time

---

## Tools & Technologies

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX (Data Analysis Expressions)
- Star Schema Data Modeling

---

## Data Preparation

The project began by importing and preparing three Excel datasets containing:

- Sales Transactions
- Customer Account Information
- Product Hierarchy

Data preparation included:

- Cleaning and standardizing data
- Reviewing data types
- Removing duplicates
- Renaming tables and columns
- Creating a custom Date table
- Building calculated columns for time intelligence

---

## Data Modeling

A star schema data model was created by establishing relationships between fact and dimension tables, providing a scalable foundation for reporting and analytical calculations.

---

## DAX Measures Developed

Key business metrics were created using DAX, including:

- Total Sales
- Quantity Sold
- Cost of Goods Sold (COGS)
- Gross Profit
- Gross Profit %
- Year-to-Date (YTD)
- Prior Year-to-Date (PYTD)
- Year-over-Year (YoY) Growth
- Dynamic Metric Selection

Dynamic measures allow users to switch between Sales, Quantity Sold, and Gross Profit using slicers without rebuilding visuals.

---

## Dashboard Features

- Interactive KPI Cards
- Dynamic Metric Selector
- Year Filter
- Dynamic Titles
- Conditional Formatting
- Drill-Down Functionality
- Responsive Visual Interactions

---

## Dashboard Visualizations

### Executive KPIs
Displays:

- Current YTD Performance
- Prior Year Performance
- YoY Growth
- Gross Profit %

---

### Treemap

Highlights the lowest-performing countries by comparing Year-to-Date versus Prior Year performance.

---

### Waterfall Chart

Analyzes monthly performance changes with drill-down capability into:

- Country
- Product Type
- Product

---

### Line & Stacked Column Chart

Compares current and previous year performance across product categories over time.

---

### Customer Profitability Scatter Plot

Segments customer accounts based on:

- Gross Profit %
- YTD Sales

This visualization helps identify high-value customers and potential growth opportunities.

---

## Key Skills Demonstrated

- Data Cleaning
- Data Transformation
- Power Query
- Data Modeling
- Star Schema Design
- DAX
- Time Intelligence
- KPI Development
- Interactive Dashboard Design
- Business Intelligence
- Data Visualization
- Performance Analysis
- Analytical Problem Solving

---

## Project Outcomes

The completed dashboard enables decision-makers to:

- Monitor business performance in real time
- Compare current and previous year results
- Identify declining markets
- Analyze sales trends
- Evaluate customer profitability
- Support data-driven business decisions

---

## Repository Contents

```
📁 PowerBI-Sales-Dashboard
│
├── Performance Report Dashboard Project_Daniel Cortese.pbix
├── Plant_DTS.xlsx
├── README.md
└── images
    ├── dashboard-overview.png
    ├── kpi-dashboard.png
    ├── waterfall-analysis.png
    ├── treemap.png
    └── scatter-analysis.png
```

---

## Dashboard Preview

Example:

<img width="1286" height="727" alt="Performance Dashboard 1  Sales" src="https://github.com/user-attachments/assets/f70c13cc-387c-4e11-9925-c34c770dfaec" />

<img width="1295" height="727" alt="Performance Dashboard 2  Quantity" src="https://github.com/user-attachments/assets/93f57bb7-4035-427e-84d9-e1c22b4c4f78" />

<img width="1297" height="727" alt="Performance Dashboard 3  Gross Profit" src="https://github.com/user-attachments/assets/05b0334d-133a-4cbe-a087-45febca8965c" />

---

## Author

**Daniel Cortese**

Aspiring Business Analyst | SQL | Power BI | Excel | Data Analytics
