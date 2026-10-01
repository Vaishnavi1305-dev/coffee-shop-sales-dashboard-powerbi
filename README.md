☕ coffee-shop-sales-dashboard-powerbi

Interactive Coffee Shop Sales Dashboard developed using Power BI, DAX, Power Query, and data visualization techniques to analyze sales, profit, orders, products, and customer trends.


📊 Project Overview

The Coffee Shop Sales Dashboard is an interactive data analytics project developed using Microsoft Power BI. The dashboard provides a comprehensive view of coffee shop sales performance by analyzing sales, orders, products, profit, quantity, and time-based trends.

The project demonstrates practical skills in data cleaning, data transformation, DAX calculations, data modeling, and interactive data visualization.

🎯 Project Objectives
Analyze overall coffee shop sales performance.
Track total sales, profit, orders, and quantity sold.
Identify top-performing products.
Analyze sales by product category.
Understand monthly and daily sales trends.
Compare product performance.
Create an interactive and user-friendly Power BI dashboard.
Provide useful insights from sales data.

🛠️ Technologies Used
Power BI
Power Query
DAX
Microsoft Excel
Data Visualization
Data Modeling


📌 Dashboard Pages
1. Sales Overview

This page provides an overall summary of coffee shop performance.

Key KPIs:

Total Sales
Total Orders
Total Quantity Sold
Total Profit
Average Sales
Average Order Value
Profit Margin %

Visualizations:

Sales by Month
Sales by Product Category
Sales by Day
Sales Trend
Top Products
2. Product Analysis

This page focuses on product-level performance.

Analysis includes:

Top-selling products
Product-wise sales
Product quantity
Product profit
Category-wise performance
Coffee vs non-coffee sales

Visualizations:

Top Products by Sales
Product Category Comparison
Product Quantity Analysis
Product Profit Analysis
3. Time & Sales Analysis

This page analyzes sales performance across different time periods.

Analysis includes:

Monthly sales trends
Daily sales trends
Weekday vs weekend sales
Sales by hour
Peak sales periods

Visualizations:

Monthly Sales Trend
Daily Sales Trend
Sales by Day of Week
Sales by Hour
Time-based performance

📈 Key Performance Indicators

The dashboard uses important KPIs such as:

KPI	Description
Total Sales	Total revenue generated
Total Profit	Total profit generated
Total Orders	Number of customer orders
Total Quantity	Total products sold
Average Sales	Average sales value
Average Profit	Average profit per transaction
Average Order Value	Average value of each order
Profit Margin %	Profit as a percentage of sales
Maximum Sales	Highest sales value
Minimum Sales	Lowest sales value

🧮 Important DAX Measures
Total Sales
Total Sales = SUM(Sales[Sales])
Total Quantity
Total Quantity = SUM(Sales[Quantity])
Total Orders
Total Orders = DISTINCTCOUNT(Sales[Order_ID])
Total Profit
Total Profit = SUM(Sales[Profit])
Average Sales
Average Sales = AVERAGE(Sales[Sales])
Average Order Value
Average Order Value =
DIVIDE([Total Sales], [Total Orders], 0)
Profit Margin %
Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0) * 100
Coffee Sales
Coffee Sales =
CALCULATE(
    [Total Sales],
    Sales[Category] = "Coffee"
)
🔄 Data Preparation

The dataset was prepared using Power Query.

Data Cleaning Steps
Imported the Excel dataset into Power BI.
Removed duplicate records.
Handled missing values.
Corrected column data types.
Standardized text values.
Created required calculated columns.
Created date-related fields.
Checked invalid or inconsistent records.
Loaded the cleaned dataset into the Power BI data model.

🗂️ Data Modeling

The cleaned data was structured in Power BI to support efficient analysis.

The model contains sales-related information such as:

Order ID
Order Date
Order Time
Product
Category
Quantity
Sales
Cost
Profit

A date table can also be used for time-based analysis.

📊 Data Visualization

The dashboard uses different Power BI visualizations including:

KPI Cards
Bar Charts
Column Charts
Line Charts
Donut Charts
Slicers
Tables
Matrix Visuals

Interactive filters allow users to analyze the data according to different products, categories, dates, and other dimensions.

🎛️ Dashboard Features

Interactive slicers
Dynamic KPI cards
Product-level analysis
Time-based analysis
Category-level analysis
Drill-down analysis
Interactive charts
Clean dashboard layout
Business-oriented visualizations

💡 Business Insights

The dashboard can help identify:

Products generating higher sales.
Categories contributing more to revenue.
High and low sales periods.
Changes in sales over time.
Products with higher quantities sold.
Overall profitability.
Peak business periods.





🚀 How to Use
Download or clone this repository.
Open the .pbix file using Microsoft Power BI Desktop.
If required, update the dataset/file path.
Refresh the data.
Use the slicers and interactive visuals to explore the dashboard.
🎓 Skills Demonstrated

This project demonstrates practical knowledge of:

Power BI
DAX
Power Query
Data Cleaning
Data Transformation
Data Modeling
Data Visualization
Excel
KPI Development
Business Intelligence
Sales Analysis

👩‍💻 Author

Vaishnavi Patil

B.Tech – Computer Science & Engineering

Project: Coffee Shop Sales Dashboard
