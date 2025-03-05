# AtliQ-Business-Insights-360
Power BI project analyzing AtliQ Hardware's sales, finance, marketing, and supply chain data.

## Project Overview

AltiQ Hardware, a fast-growing company expanding globally, specializes in selling computers and accessories through three main channels: retailers, direct sales, and distributors.

Despite its growth, the company faced unexpected losses after opening a store in America. These setbacks were identified through surveys, intuition, and basic Excel analysis. With competitors boasting robust analytics teams, AltiQ Hardware recognizes the urgent need to develop its analytics capabilities to thrive in the industry.

The company has decided to implement Power BI for analytics to surpass competitors and enable data-driven decision-making. This project aims to give stakeholders insights into finance, sales, marketing, and supply chain, ensuring informed decisions at all levels.

I worked on this project by following the Codebasics PowerBi Course, 

Here is my report link - https://app.powerbi.com/groups/me/reports/a057b46e-8b80-478d-bc8f-0b9e57881807/0225e9e7eb02500e3011?experience=power-bi

Here is my presentation link -

## Datasets:

Before diving into analysis, understanding the datasets is crucial. The datasets consist of two tables:

**Dimension table:** Static data like customer and product details.

**Fact table:** Transaction data.

gdb041:
* dim_customer
* dim_market
* dim_product
* fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
* fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056:
* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_dedutions
* Post_invoice_deductions


### Importing Data and Data Modeling:

Data was imported from MySQL into Power BI, and a data model was created after cleaning and transforming the data. But why data modeling is very important for analysis right??

If you break down the whole work of a data analyst then you will come up with 4 steps of work 

✅ Data Extract ---> ✅ Data Cleaning---> ✅ Data Modelling ---> ✅ Data Analysis

See you can't skip the 3rd step if you want to reach the last step (analysis part), 
Data modeling is essential because it lays the foundation for reports. All visuals are built upon the data model, and poor modeling can affect report performance.

In this project, we have followed the Snowflake schema data modeling method. 


![data modelling](https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Data%20modelling.png)


## Power BI Dashboard Overview:

The dashboard comprises six pages-->

### Home Page: A landing page with buttons to navigate to different pages.

https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/home%20page.png


### Finance Page: Focuses on improving financial planning, budgeting processes, and cost control. Includes Profit and Loss statements, Top and Bottom Products and Customers by Net Sales, and more.

https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Financeview.png


### Sales Page: Aims to increase sales revenue and market share. Features Customer performance by Net Sales, Gross Margin, Gross Margin %, and more.

https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Sales%20view.png


### Marketing Page: Aims to increase brand visibility and customer engagement. Provides Segment Performance by Gross Margin% and Net Profit%, and more.

https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Marketing%20view.png


### Supply Chain Page: Aims to optimize inventory management and enhance supplier relationships for cost savings. Includes details about Forecast Accuracy, Net error, and more.

https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Supply%20chain%20view.png


### Executive Page: Provides an overview of the organization's performance for top management. Includes Net Sales, Gross Margin%, Net Profit%, Revenue Contribution by channel, Top 5 Customer and Product, Sub Region performance, and more.

https://github.com/SHRADDHA-92/AtliQ-Business-Insights-360/blob/main/Executive%20view.png


## Skills Learned:

During the Codebasics Bootcamp course and this project, I learned:
Power BI fundamentals,
Calculated columns and DAX measures,
Data Modeling, Data Cleaning, Bookmarks, Conditional formatting,
Custom Tooltip usage, Dynamic Title Creation, and more.

### Tools Used:

SQL, Power BI Desktop, DAX language, DAX studio (to reduce file size), Project Charter file.

### Business Terms Learned:

Gross Margin, Gross Margin %, Gross Sales, Gross Sales %, Pre-invoice deductions, Post-invoice deductions, Net sales, Net Invoice Sales, Net Profit, Net Profit %, COGS (cost of goods sold), YTG (year to go), YTD (year to date), Direct, Retailer, Consumer, Distributors.

## Conclusion :

This report empowers decision-making based on data, addressing numerous "why" questions across various scenarios. It serves as a tool to extract insights and guide actions, ultimately aiming to enhance AltiQ's profitability through data-driven decisions.
