📊 Retail Sales Performance Dashboard (Power BI)
📌 Overview

This project is a Power BI dashboard built to analyze retail sales performance, product trends, and customer returns.
It simulates a real-world business reporting system using Power Query-based data transformation and interactive visual analytics.

The dashboard helps stakeholders understand:

Sales performance across categories and regions
Monthly revenue trends
Top-performing products
Return patterns and reasons

🎯 Business Objective

The goal of this project is to provide a clear, interactive view of retail business performance to support data-driven decision making.
It answers key business questions such as:
Which categories generate the highest revenue?
Which products perform best?
Which regions generate the most sales?
What are the main reasons for product returns?

🛠️ Tools & Technologies Used

Power BI Desktop
Power Query (Data Cleaning & Transformation)
Excel/CSV (Data Source)

📂 Dataset Description

1. Orders Table

Contains transaction-level data:
Order ID, Order Date, Ship Date
Customer details (ID, Name, Region, Segment)
Product ID, Quantity, Unit Price
Sales Amount

2. Products Table

Contains product master data:
Product ID, Product Name
Category, Sub Category
Unit Price, Stock Available, Supplier

3. Returns Table

Contains return transaction details:
Return ID, Order ID
Return Date, Return Reason
Return Status

🔄 Data Preparation Steps

Imported Orders, Products, and Returns datasets into Power BI
Cleaned data using Power Query
Removed duplicates and handled null values
Standardized data types (Date, Text, Number)

Merged:

Orders ↔ Products using Product ID
Orders ↔ Returns using Order ID
Expanded required fields after merging
Created derived columns:
Order Month
Order Year
Is Returned flag

📊 Dashboard Pages

📌 1. Sales Overview

KPI Cards:
Total Revenue
Total Orders
Total Quantity
Revenue by Category
Monthly Revenue Trend
Revenue by Region
Slicers: Region, Category, Year

📌 2. Product Performance

Top 10 Products by Revenue
Revenue by Sub-Category
Orders by Category (Donut Chart)

📌 3. Returns Analysis

Returns by Region
Returns by Reason
Return Status Distribution

📈 Key Insights

Certain categories significantly outperform others in revenue contribution
Revenue shows clear monthly trends and seasonality patterns
Some regions have higher return rates compared to others
Product returns are driven mainly by a few key reasons

📷 Dashboard Preview

(Add screenshots here if uploading on GitHub)

Sales Overview Page
Product Performance Page
Returns Analysis Page

📁 Project Files

YourName_RetailDashboard.pbix → Power BI file
YourName_RetailDashboard.pdf → Dashboard export
ImplementationNote.pdf → Project documentation

🚀 How to Use

Download the .pbix file
Open it using Power BI Desktop
Explore interactive dashboards using filters and slicers

📌 Skills Demonstrated

Data Cleaning & Transformation (Power Query)
Data Modeling (Table Relationships)
Business Intelligence Reporting
Data Visualization Design
Analytical Thinking

⭐ Final Note

This project demonstrates a complete end-to-end BI workflow from raw data to actionable insights using Power BI.
