# sales_analysis
📱 Mobile Sales Dashboard — Power BI Project
🧾 Overview

The Mobile Sales Dashboard is an interactive Power BI report designed to analyze and visualize mobile phone sales performance across various dimensions — including brand, model, city, payment method, and time period.

It helps businesses and analysts understand sales trends, customer behavior, and key performance metrics through dynamic filters, charts, and KPIs.

🎯 Project Objective

To create a comprehensive and interactive sales dashboard that provides:

Insights into total revenue, average price, sales quantity, and transactions.

Clear visualization of brand performance, payment method usage, and customer ratings.

Month-to-date (MTD) and year-over-year (YoY) comparisons for performance tracking.

Geographic and temporal insights to support data-driven business decisions.

🧰 Tools & Technologies Used

Power BI Desktop

Microsoft Excel / CSV data source

DAX (Data Analysis Expressions) for calculated measures

Power Query for data cleaning and transformation

Map visuals, cards, bar charts, line charts, and slicers

📊 Dashboard Pages & Features
1️⃣ Main Dashboard

KPIs displayed:

🪙 Average Price → ₹40.11K

💰 Total Sales → ₹769M

📦 Total Quantity Sold → 19K

🔁 Total Transactions → 4K

Filters: Mobile Model, Brand, Payment Method

Visuals:

Line chart showing Total Quantity by Month

Map showing Sales distribution by City

Table of Top Performing Brands (Apple, OnePlus, Samsung, Vivo, Xiaomi)

Rating bar chart (Good, Average, Poor)

Pie chart of Transactions by Payment Method (UPI, Debit Card, Credit Card)

Bar charts for:

Total Sales by Mobile Model

Total Sales by Day Name

2️⃣ MTD (Month-to-Date) Report

Displays sales and quantity for the current month, allowing a detailed monthly analysis.

KPIs:

Average Price: ₹38.96K

Total Sales: ₹19M

Total Quantity: 483

Transactions: 100

Includes Month selector slicer.

Simple MTD trend visualization by Month.

3️⃣ Same Period Comparison

Compares sales performance between the current year and the same period last year.

KPIs:

Average Price: ₹42.81K

Total Sales: ₹24M

Total Quantity: 545

Transactions: 110

Visuals:

Bar charts showing Total Sales vs Same Period Last Year by Month and Quarter

Table summarizing quarterly and yearly comparison

🗺️ Geographical Insights

City-level visualization using Power BI Map:

Major sales hubs: Delhi, Mumbai, Bangalore, Hyderabad, Kolkata, Bhopal, Indore.

Helps track regional performance and sales coverage.

💳 Payment Insights

Distribution of transactions across payment methods:

UPI

Debit Card

Credit Card

Helps identify customer preferences for digital vs card payments.

📈 Key Insights

Apple and Samsung lead in total sales and transactions.

UPI is the most preferred payment method.

Sales volume peaks around January–March.

Average mobile price remains around ₹40K–₹43K.

Good ratings dominate overall product feedback.

🧮 Calculated Metrics (DAX Examples)
Total_Sales = SUM(Sales[purchase_amount])
Total_Quantity = SUM(Sales[quantity])
Average_Price = DIVIDE([Total_Sales], [Total_Quantity])
MTD_Sales = TOTALMTD([Total_Sales], Sales[Date])
YoY_Sales = CALCULATE([Total_Sales], SAMEPERIODLASTYEAR(Sales[Date]))

💼 Business Value

Empowers business teams to track sales in real time.

Enables data-driven decisions for inventory and marketing.

Provides insights into regional and seasonal sales trends.

Helps compare current performance vs past years.

📂 Project Files

Mobile_Sales_Dashboard.pbix → Power BI dashboard file

Sales_Data.xlsx → Source dataset

README.md → Project documentation (this file)

🚀 How to Use

Open the .pbix file in Power BI Desktop.

Click Refresh to load or update data.

Use filters (Brand, Model, Payment Method, Month, Year) to interact with visuals.

Navigate between the Dashboard, MTD Report, and Same Period tabs for insights.
