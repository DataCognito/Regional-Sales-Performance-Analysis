# Regional Sales Performance Analysis

### Excel | Power Query | Power BI | DAX

An end-to-end sales analysis project focused on cleaning raw sales data, correcting the data model, analysing business performance, and building an interactive Power BI dashboard.

## Business Problem

The original sales data contained an incorrect **many-to-many relationship** between the sales and manager/region data. This could lead to unreliable calculations and filtering.

The objective was to:

* Clean and prepare the raw data
* Correct the data model
* Analyse revenue and sales performance
* Understand discounting and returns
* Compare managers and regions
* Analyse shipping performance
* Build an interactive dashboard for business reporting

## Dataset

* **Domain:** E-commerce sales
* **Period:** 2023–2025
* **Orders:** 1,500
* **Source:** UCI
* **Data preparation:** Excel & Power Query
* **Analysis & visualization:** Power BI

## What I Worked On

### 1. Data Cleaning & Preparation

Using Excel and Power Query:

* Removed duplicate records
* Checked missing values
* Standardised product, region and manager names
* Filtered invalid/test records
* Prepared the data for analysis

### 2. Data Modelling

In Power BI:

* Restructured the incorrect many-to-many relationship
* Created fact and dimension tables
* Defined appropriate relationships and cardinality
* Prepared the model for reliable reporting

### 3. DAX & Business Metrics

Created calculated columns and measures for:

* Total Sales
* Net Revenue
* Total Quantity
* Total Discount
* Average Order Value
* Average Selling Price
* Average Shipping Time
* Return Rate
* Total Orders

### 4. Power BI Dashboard

The dashboard includes:

* Revenue analysis
* Manager performance
* Regional performance
* Product performance
* Discount analysis
* Return analysis
* Shipping-time analysis
* Interactive filters and slicers
* Drill-down
* Page navigation
* Cumulative trend analysis

## Dashboard Preview

### Regional Performance & Efficiency Audit
https://github.com/DataCognito/Regional-Sales-Performance-Analysis/blob/main/Screenshots/Dashboard%20page%201.png?raw=true

### Manager Accountability & Cost Audit
https://github.com/DataCognito/Regional-Sales-Performance-Analysis/blob/main/Screenshots/Dashboard%20page%202.png?raw=true

### Data Model
https://github.com/DataCognito/Regional-Sales-Performance-Analysis/blob/main/Screenshots/Data%20Model%20-%20Power%20BI.png?raw=true

## Key Findings

* The analysis covered **1,500 orders** with total net revenue of approximately **$4.38 million**.
* Average order value was approximately **$2.92K**.
* Shipping time averaged approximately **6.04 days**.
* The overall return rate was approximately **25%** based on the project dataset.
* Tablet, Laptop, Printer, Monitor and Chair were among the highest-revenue products.
* Higher discounting was observed for some managers and required further review.
* Revenue showed a noticeable decline between May and October in the analysed period.
* Several high-revenue regions also showed higher return rates, highlighting an area for further operational investigation.

## Business Value

The final dashboard provides a single view of:

**Revenue → Discounts → Returns → Shipping → Manager Performance → Regional Performance**

This makes it easier to identify performance differences, monitor operational issues and investigate areas that may affect revenue and customer experience.

## Project Workflow

**Raw Data → Cleaning → Transformation → Data Modelling → DAX → Analysis → Dashboard → Insights**
