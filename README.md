# AtliQ-Business-Insights-360
Power BI project analyzing AtliQ Hardware's sales, finance, marketing, and supply chain data.

## Project Overview

AtliQ Hardware, a fast-growing company expanding globally, specializes in selling computers and accessories through three main channels: retailers, direct sales, and distributors.

Despite its growth, the company faced unexpected losses after opening a store in America. These setbacks were identified through surveys, intuition, and basic Excel analysis. With competitors boasting robust analytics teams, AtliQ Hardware recognizes the urgent need to develop its analytics capabilities to thrive in the industry.

The company has decided to implement Power BI for analytics to surpass competitors and enable data-driven decision-making. This project aims to give stakeholders insights into finance, sales, marketing, and supply chain, ensuring informed decisions at all levels.

I worked on this project by following the Codebasics Power BI Course, 

Here is my report link - https://app.powerbi.com/groups/me/reports/a057b46e-8b80-478d-bc8f-0b9e57881807/0225e9e7eb02500e3011?experience=power-bi

Here is my presentation link -

## Datasets:

Before diving into analysis, understanding the datasets is crucial. The datasets consist of two tables:

**Dimension table:** Contains static data such as customer and product details.

**Fact table:** Stores transaction data.

### gdb041:
* dim_customer
* dim_market
* dim_product
* fact_forecast_monthly - Used to forecast customer demand, aiding in higher customer satisfaction and reducing warehouse storage costs.
* fact_sales_monthly - Similar to the fact_forecast_monthly table, but the last column represents the sold quantity instead of the forecasted value.

### gdb056:
* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_deductions
* Post_invoice_deductions

### Importing Data and Data Modeling:

Data was imported from MySQL into Power BI, followed by data cleaning and transformation before modeling. But why is data modeling crucial for analysis?

A data analyst’s workflow typically consists of four key steps:

🔹 Data Extraction ---> 🔹 Data Cleaning ---> 🔹 Data Modeling ---> 🔹 Data Analysis

Skipping data modeling can negatively impact the final analysis. Proper modeling lays the foundation for reports, as all visuals rely on the underlying data model. Poor modeling can also reduce report performance.

In this project, the **Snowflake schema** data modeling method was used.

![data modelling](https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Data%20modelling.png)

## Power BI Dashboard Overview:

The dashboard consists of six pages:

### Home Page: A landing page with buttons to navigate to different pages.

![Home page](https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/home%20page.png)

### Finance Page: Focuses on financial planning, budgeting, and cost control. Includes Profit & Loss statements, Top/Bottom Products and Customers by Net Sales, and more.

![Finance view](https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Financeview.png)

### Sales Page: Aims to boost sales revenue and market share. Features Customer Performance by Net Sales, Gross Margin, and Gross Margin %.

![Sales view](https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Sales%20view.png)

### Marketing Page: Focuses on increasing brand visibility and customer engagement. Shows Segment Performance by Gross Margin% and Net Profit%.

![Marketing view](https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Marketing%20view.png)

### Supply Chain Page: Aims to optimize inventory management and improve supplier relationships. Includes Forecast Accuracy, Net Error, and more.

![Supply chain view](https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Supply%20chain%20view.png)

### Executive Page: Provides top-level management insights. Displays Net Sales, Gross Margin%, Net Profit%, Revenue Contribution by Channel, Top 5 Customers & Products, and Sub-Region Performance.

![Executive view](https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Executive%20view.png)

## Skills Learned:

Through the Codebasics Bootcamp and this project, I gained expertise in:
- Power BI fundamentals
- Calculated columns and DAX measures
- Data Modeling
- Data Cleaning
- Bookmarks
- Conditional formatting
- Custom Tooltips
- Dynamic Title Creation

### Tools Used:

- SQL
- Power BI Desktop
- DAX language
- DAX Studio (to optimize file size)
- Project Charter File

### Business Terms Learned:

- Gross Margin, Gross Margin %
- Gross Sales, Gross Sales %
- Pre-invoice Deductions, Post-invoice Deductions
- Net Sales, Net Invoice Sales, Net Profit, Net Profit %
- COGS (Cost of Goods Sold)
- YTG (Year to Go), YTD (Year to Date)
- Direct Sales, Retailers, Consumers, Distributors

## Conclusion:

This Power BI report enables data-driven decision-making by addressing multiple business questions across various scenarios. It provides actionable insights that help AtliQ Hardware enhance profitability and remain competitive in the market.
