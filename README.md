# Regional-Sales-Performance-Analysis
Regional sales performance project using Excel, Power Query, and Power BI, where the data was cleaned, the faulty many‑to‑many model was fixed, and interactive dashboards were built to show revenue, discounts, returns, and shipping time for each manager and region in a clear way.

**Project Overview and Objective**
This project uses Excel and Power BI to analyse regional sales performance and manager results for an e commerce business. The main goal is to understand which products, regions, and managers drive revenue and where discounts, returns, and shipping time are low.

**Data sources**
Source Description & Timeline: UCI -> 2023 - 2025
Domain: E - Commerce Sales Analysis
Tools: Excel & Power Query for data cleaning and preparation
           Power BI for data modelling, DAX measures, and interactive dashboards

**Problem Statement**
The current sales report is not reliable because the data model is incorrect. A many to many relationship between the sales table and the manager/region table makes key metrics hard to calculate and filter. This project rebuilds the model so revenue, discounts, returns, and shipping time can be analysed accurately by manager and region. It allows the business to clearly see how discounting and return rates affect net revenue, so they can protect profit and manage risk.

**Tools & Technologies**
Excel: Data cleaning and transformation.
Power BI: Data modelling, DAX calculations, Data visualizations, and Dashboard creation.

**Data Pre-Processing (Excel/ Power Query)**
Tasks Performed 
•	Data cleaning and transformation: Removed duplicate rows, checked for missing values, and standardised product, region, and manager names. 
•	New calculated fields: Created columns for Net Revenue (Gross Sales – Discount), Average Order Value, Average Selling Price, Shipping Time (in days), and Return Flag. 
•	Filtering and sorting: Filtered out test or invalid records and sorted data by date, region, and manager to prepare it for modelling in Power BI.

**Data Modelling and DAX (Power BI)**
Data model: Established relationships between tables and defined cardinality.
Converted data into Fact and Dimension Table

Calculated Columns and DAX Measures: Implemented DAX formulas for key metrics, such as total sales, total net revenue, total quantity, total discount value, avg. order value, avg. selling price, Avg. shipping time (days), Return rate % and Total orders.

**Analysis and Visualizations (Power BI)**
Dashboard features
Multiple visualizations based on problem statement: Bar chart, line chart, donut chart, and tables and cumulative totals.
Have made this report interactive with Drill-down, filters and slicers.
Have used page navigation and enabled its action. 

**Insights and Conclusion**
Key findings: 
Overall financial performance: The audit covers 1,500 orders and a Total Net Revenue of about $4.38 million. The Average Order Value is around $2.92 thousand, showing a strong ticket size across transactions.

Manager and cost accountability: Total Net Sales per manager are quite similar, at roughly $4.7 million each. However, Ryan and Cameron give higher discounts, so their discounting strategy should be reviewed in more detail.

Regional efficiency: Average Shipping Time is about 6.04 days across regions and stores. The Return Rate of 0.25 indicates a meaningful operational risk that needs attention.

Sales contribution: The top five products by revenue are Tablet, Laptop, Printer, Monitor, and Chair. These high value items drive most of the revenue and should remain a focus for sales and inventory planning.
**Analysis insights**
Descriptive and Diagnostic view:
Sales show clear seasonality, with a noticeable drop between May and October. High return rates in high revenue regions (North, East, West) suggest a link between sales volume and returns, and point to possible fulfilment or quality issues.

Predictive and Prescriptive view:
The May–October slump is likely to repeat each year, so the business should plan campaigns and resources to stabilise revenue in that period. Reducing average shipping time and auditing heavy discounting for some managers can help improve both profit and customer experience.

**Conclusion**
This project cleans up the data model by fixing the many to many issue that was causing incorrect results. With the new dashboards, teams can clearly see revenue, discounts, returns, and shipping time for each manager and region, making it easier to plan actions and keep risks under control.




