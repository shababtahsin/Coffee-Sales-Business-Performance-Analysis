# Coffee Sales Business Performance Analysis

## Project Overview

This project analyses coffee sales performance using Microsoft Excel to identify key business trends across revenue, products, customers, countries, and time periods.

The analysis combines order, customer, and product information into a consolidated analytical dataset using Excel lookup functions and calculated fields. PivotTables, PivotCharts, slicers, and an interactive dashboard were then used to transform transactional data into business insights.

The project demonstrates an end-to-end Excel analysis workflow, including:

- Data integration
- Data transformation
- Business metric calculation
- Sales trend analysis
- Customer analysis
- Product performance analysis
- Geographic analysis
- Interactive dashboard development

---

## Business Objective

The objective of this project was to transform raw coffee order data into an interactive business performance dashboard that allows stakeholders to quickly evaluate:

- How sales are changing over time
- Which coffee products generate the most revenue
- Which countries contribute the most sales
- Who the highest-value customers are
- How different coffee types and package sizes perform
- How customer loyalty status influences the dataset
- Where potential sales opportunities exist

---

## Dataset

The workbook contains interconnected data relating to:

### Orders

Transactional coffee order information including:

- Order ID
- Order date
- Customer ID
- Product ID
- Quantity

### Customers

Customer-level information including:

- Customer name
- Email
- Phone number
- Address
- Country
- Loyalty card status

### Products

Product information including:

- Coffee type
- Roast type
- Package size
- Unit price
- Profit information

These datasets were combined to create a consolidated order-level analytical table.

---

## Data Preparation

The raw datasets were enriched using Excel lookup and reference functions.

### XLOOKUP

`XLOOKUP` was used to retrieve customer information from the customer dataset and connect it to individual orders.

Examples include retrieving:

- Customer name
- Email address
- Country
- Loyalty card status

### INDEX and MATCH

`INDEX` and `MATCH` were used to retrieve product information based on Product ID.

This allowed product attributes such as coffee type, roast type, size, and pricing information to be incorporated into the order dataset.

### Calculated Sales

Sales revenue was calculated using:

```text
Sales = Quantity × Unit Price
```

This created the primary financial metric used throughout the analysis.

---

## Analysis Performed

### Sales Trend Analysis

Sales were analysed over time to identify changes in revenue performance.

The analysis allows users to examine sales across different periods and understand whether particular coffee types or product categories perform differently over time.

### Sales by Country

Revenue was aggregated geographically to determine which markets contribute the highest level of sales.

This provides management with a simple view of geographic concentration and market performance.

### Top Customer Analysis

Customers were ranked according to total sales contribution.

This helps identify high-value customers who may represent opportunities for:

- Customer retention
- Loyalty initiatives
- Targeted marketing
- Relationship management

### Product Performance

Coffee products were analysed across several dimensions, including:

- Coffee type
- Roast type
- Package size
- Sales value

This enables comparison of product demand and revenue contribution.

---

## Interactive Excel Dashboard

An interactive Excel dashboard was developed to provide stakeholders with a consolidated view of sales performance.

The dashboard includes:

- Sales over time
- Sales by country
- Top customers
- Coffee type filtering
- Roast type filtering
- Package size filtering
- Loyalty card filtering
- Timeline-based filtering

Interactive slicers allow users to dynamically change the dashboard and investigate specific segments of the business.

---

## Dashboard Preview

Add your dashboard screenshot to the `images` folder and use:

```markdown
![Coffee Sales Dashboard](images/coffee-sales-dashboard.png)
```

---

## Tools & Techniques

| Area | Tools / Techniques |
|---|---|
| Data Analysis | Microsoft Excel |
| Data Integration | XLOOKUP |
| Advanced Lookup | INDEX + MATCH |
| Data Transformation | Excel formulas |
| Aggregation | PivotTables |
| Visualisation | PivotCharts |
| Interactivity | Slicers and Timeline |
| KPI Analysis | Sales Revenue |
| Customer Analysis | Top Customer Ranking |
| Geographic Analysis | Sales by Country |
| Product Analysis | Coffee Type, Roast Type and Size |

---

## Key Business Questions

1. How are coffee sales changing over time?
2. Which coffee products generate the most revenue?
3. Which countries represent the strongest markets?
4. Who are the highest-value customers?
5. How does sales performance differ between coffee types?
6. How does roast type affect product sales?
7. Which package sizes contribute most strongly to revenue?
8. How can stakeholders dynamically investigate different customer and product segments?

---

## Business Value

The completed dashboard converts transactional order data into a management-friendly analytical tool.

Instead of reviewing individual transactions, stakeholders can use the dashboard to quickly identify:

- Revenue trends
- High-performing markets
- Valuable customers
- Product performance differences
- Customer segments
- Potential areas requiring further investigation

This supports faster and more structured sales-performance decision-making.

---

## Skills Demonstrated

This project demonstrates practical experience in:

- Business requirements interpretation
- Data preparation
- Dataset integration
- Lookup functions
- Excel data modelling
- Revenue calculations
- PivotTable analysis
- Dashboard design
- Interactive filtering
- Sales analysis
- Customer segmentation
- Product performance analysis
- Geographic analysis
- Translating data into business insights

---

## Repository Structure

```text
Coffee-Sales-Business-Performance-Analysis/
│
├── coffeeOrdersData Project Shabab.xlsx
│
├── images/
│   └── coffee-sales-dashboard.png
│
└── README.md
```

---

## Project File

The main Excel workbook contains the complete analysis, including:

- Raw datasets
- Integrated order data
- Calculated fields
- PivotTables
- PivotCharts
- Interactive dashboard

---

## Author

**Shah Tahsin**

Business Analyst | Data Analyst

GitHub: [shababtahsin](https://github.com/shababtahsin)
