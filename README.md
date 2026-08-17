Sales & Revenue Analysis Dashboard

An interactive Power BI dashboard designed to analyze sales performance, revenue trends, product performance, profitability, and regional sales using business data.

📊 Project Overview

The dashboard transforms raw sales data into meaningful business insights using KPIs, charts, DAX measures, filters, and slicers. It helps users quickly understand overall business performance and identify high-performing products, categories, and regions.

🎯 Key Features
Total Sales KPI – Tracks overall sales revenue.
Total Profit KPI – Measures total generated profit.
Total Orders KPI – Calculates the number of unique orders.
Average Order Value – Calculates average revenue generated per order.
Monthly Sales Trend – Shows how sales change over time.
Top 5 Products – Identifies the products generating the highest sales.
Sales by Category – Compares sales performance across product categories.
Sales by Region – Analyzes regional sales performance.
Interactive Slicers – Filter the dashboard by:
Region
Category
Order Date
🛠️ Tools & Technologies
Power BI Desktop
DAX
Excel / CSV Dataset
Data Visualization
Data Analysis
📐 DAX Measures
Total Orders
Total Orders =
DISTINCTCOUNT('Superstore sales dataset'[Order ID])
Average Order Value
Average Order Value =
DIVIDE(
    SUM('Superstore sales dataset'[Sales]),
    DISTINCTCOUNT('Superstore sales dataset'[Order ID]),
    0
)
📈 Dashboard Insights

The dashboard can be used to identify:

Overall sales and profitability
Monthly sales growth and decline
Best-selling products
Highest-performing categories
Strongest and weakest regions
Average customer order value
Business performance under different filters
📁 Dataset

The project uses a Superstore Sales dataset containing fields such as:

Order ID
Order Date
Product Name
Category
Sub-Category
Region
Sales
Profit
Quantity
Discount
Customer Name
State
City
🚀 How to Use
Open the .pbix file in Power BI Desktop.
Load or replace the sales dataset.
Refresh the data.
Use the KPI cards to view overall performance.
Use the charts to analyze sales trends and product performance.
Use the slicers to filter the dashboard interactively.
💡 Business Value

This dashboard demonstrates how raw sales data can be converted into an interactive business intelligence solution that supports data-driven decision-making and performance monitoring.

👨‍💻 Project Skills Demonstrated

Data Cleaning • Data Visualization • Power BI • DAX • KPI Development • Business Analytics • Interactive Dashboards • Data-Driven Insights
