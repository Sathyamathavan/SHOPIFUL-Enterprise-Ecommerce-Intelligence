🛒 SHOPIFUL – Enterprise E-Commerce Intelligence Platform
📌 Industry

E-Commerce – Online Retail & Enterprise Business Analytics

📖 Project Overview

SHOPIFUL – Enterprise E-Commerce Intelligence Platform is a data analytics and business intelligence project developed to analyze the performance of an e-commerce business across multiple operational areas.

The project integrates data related to customers, products, categories, orders, payments, returns, deliveries, reviews, and warehouse operations.

MySQL and SQL are used for database creation, data storage, validation, and analysis, while Microsoft Power BI is used to build interactive dashboards and generate business insights.

The primary goal of the project is to transform raw e-commerce data into meaningful visual insights that support data-driven business decision-making.

🎯 Business Areas Covered
📈 Sales and revenue performance
👥 Customer behaviour and order frequency
📦 Product and category performance
🛒 Order analysis
💳 Payment analysis
🔄 Returns and delivery performance
⭐ Product reviews and ratings
🏭 Warehouse and inventory operations
🌍 Geographical business performance
🎯 Project Objectives
Build a structured relational database for e-commerce operations.
Organize customer, product, category, order, payment, return, delivery, review, and warehouse data.
Analyze sales, orders, revenue, discounts, and product performance.
Identify top-performing products and categories.
Analyze customer purchasing behaviour and geographical distribution.
Evaluate payment methods and payment revenue.
Analyze return patterns and delivery performance.
Monitor warehouse capacity and stock distribution.
Build interactive Power BI dashboards for management reporting.
Generate actionable business recommendations.
🛠️ Tools & Technologies
Tool / Technology	Purpose
Microsoft Excel	Dataset source, inspection and initial preparation
MySQL	Database creation and data storage
SQL	Data validation, querying and business analysis
Power Query	Data cleaning and transformation
Microsoft Power BI	Interactive dashboard development
DAX	KPI and calculated measure creation
GitHub	Project documentation and version control
📂 Dataset Introduction

The project uses an Enterprise E-Commerce Dataset containing 10 related tables:

Table	Description
Customers	Customer details and geographical information
Products	Product details, pricing and product information
Categories	Product category information
Orders	Main order transaction data
Order_Items	Individual products and quantities within orders
Payment	Payment method and payment transaction information
Returns	Return status and return-related information
Deliveries	Delivery and delivery partner information
Reviews	Customer ratings and product review information
Warehouse	Warehouse capacity, stock and location information
🗄️ MySQL – Database & Tables

A relational MySQL database was created to organize the SHOPIFUL e-commerce data.

The database contains:

customers
products
categories
orders
order_items
payment
returns
deliveries
reviews
warehouse

Orders and Order_Items form the primary transaction area and are connected with customer, product, category, payment, return, delivery, review, and warehouse information.

🔎 SQL Analysis

SQL was used for:

Database creation
Table creation
Data inspection
Data validation
Record-count validation
Duplicate checking
Null/value checking
KPI validation
Cross-table analysis
Business performance analysis
Analysis Areas
Order volume
Sales and revenue
Product performance
Category performance
Customer analysis
Payment analysis
Return analysis
Delivery analysis
Warehouse stock analysis
🔗 Connecting MySQL with Power BI

The MySQL database was connected to Microsoft Power BI to create an integrated business intelligence solution.

Process:

MySQL Database → Power BI → Power Query → Data Model → DAX → Dashboard

The required tables were imported and relationships were established between the related datasets before developing the dashboards.

🔄 ETL – Data Loading & Transformation

Power Query was used as the ETL layer.

Extract

Data was obtained from the MySQL database and source datasets.

Transform

The data was cleaned, standardized, and prepared for analysis.

Load

The transformed data was loaded into the Power BI data model.

🧹 Data Cleaning

Major data preparation activities included:

Removing duplicate records
Handling null and invalid values
Correcting data types
Standardizing column values
Cleaning numerical fields
Validating relationships
Checking key fields
Preparing data for visualization
📐 Basic DAX Measures

DAX was used to create dynamic KPIs and calculated measures.

Examples include:

Total Sales
Total Orders
Total Customers
Total Units Sold
Average Order Value
Total Profit
Return Rate
Payment Amount
Warehouse Capacity
Stock Quantity

These measures dynamically respond to dashboard filters and slicers.

📊 Power BI Dashboard

The project contains 7 interactive Power BI dashboard pages.

1️⃣ Executive Overview Dashboard

Provides a high-level overview of overall business performance.

Visuals
Monthly Sales Trend → Line Chart
Sales by Category → Donut Chart
Sales by State → Horizontal Bar Chart
Top 10 Products by Sales → Horizontal Bar Chart
Payment Method Analysis → Donut Chart
Purpose

Provides management with a quick view of sales trends, category performance, geographical sales, top products, and payment preferences.

2️⃣ Customer Intelligence Dashboard

Focuses on customer behaviour and geographical distribution.

Visuals
Customer Revenue by State → Bar Chart
Orders by Status → Bar Chart
Customer Order Frequency → Bar Chart
Geographic Distribution → Map of India
Purpose

Helps understand customer revenue contribution, purchasing frequency, order behaviour, and geographical customer distribution.

3️⃣ Product Performance Dashboard

Analyzes product and category-level performance.

Visuals
Sales by Category → Pie Chart
Product Sales Trend → Line Chart
Product Price vs Sales → Bar Chart
Purpose

Helps identify high-performing categories, sales trends, and product pricing performance.

4️⃣ Sales & Orders Dashboard

Provides detailed sales and order analysis.

Visuals
Total Orders by State → Pie Chart
Total Orders by Order Status → Pie Chart
Selling Price by Brand → Horizontal Bar Chart
Review by Rating → Line Chart
Sales Amount by Year → Vertical Bar Chart
Purpose

Helps analyze order distribution, order status, brand pricing, customer ratings, and yearly sales performance.

5️⃣ Returns & Delivery Dashboard

Focuses on post-order operations.

Visuals
Total Orders by Return Status → Pie Chart
Total Returns by Reason → Bar Chart
Delivery Partner by State → Pie Chart
Purpose

Helps identify return patterns, major return reasons, and delivery partner distribution across states.

6️⃣ Payment & Revenue Dashboard

Analyzes payment behaviour and revenue contribution.

Visuals
Payment Method Distribution → Pie Chart
Payment Amount by Method → Donut Chart
Payment Amount by Year → Line Chart
Payment Amount by Category → Horizontal Bar Chart
Purpose

Provides visibility into payment preferences, payment revenue, yearly payment trends, and category-wise payment contribution.

7️⃣ Warehouse Operations Dashboard

Analyzes warehouse and inventory performance.

Visuals
Warehouse Capacity Utilization → Gauge Chart
Stock Distribution by Warehouse → Pie Chart
Stock Quantity by Warehouse ID → Bar Chart
Warehouse State Map → Map of India
Purpose

Helps monitor warehouse capacity, stock distribution, inventory levels, and warehouse locations.

🎛️ Filters & Slicers

Interactive filters and slicers are used to make the dashboards dynamic.

They allow users to:

Filter data by date
Analyze specific states
Explore categories
Compare business performance
Filter order and payment information
Cross-filter related visuals
Navigate between dashboard pages
📌 Key KPIs
KPI	Business Purpose
Total Sales	Measures overall revenue generated
Total Orders	Measures order volume
Total Customers	Measures customer base
Total Units Sold	Measures product sales volume
Average Order Value	Measures average revenue per order
Total Profit	Measures overall profitability
Return Rate	Measures return frequency
Payment Amount	Measures payment revenue
Warehouse Capacity	Measures warehouse capacity
Stock Quantity	Measures inventory availability
💡 Key Business Insights
Sales Performance – Monitor sales trends across months, years, categories, and states.
Product Performance – Identify products and categories contributing significantly to sales.
Customer Behaviour – Understand customer distribution, revenue contribution, and order frequency.
Order Performance – Analyze order volume and order-status patterns.
Payment Behaviour – Identify popular payment methods and payment revenue contribution.
Returns Analysis – Identify return patterns and major return reasons.
Delivery Analysis – Understand delivery partner distribution across states.
Warehouse Performance – Monitor warehouse capacity and stock distribution.
Geographical Analysis – Identify states contributing significantly to customers, orders, and revenue.
Management Reporting – Provide a centralized dashboard for faster, data-driven decision-making.
🔄 Project Workflow
Raw Dataset
     ↓
Data Inspection
     ↓
Data Cleaning & Validation
     ↓
MySQL Database Creation
     ↓
Table Creation
     ↓
SQL Data Validation
     ↓
SQL Analysis
     ↓
MySQL Connection to Power BI
     ↓
Power Query ETL
     ↓
Data Modelling & Relationships
     ↓
DAX Measures & KPIs
     ↓
Dashboard Development
     ↓
Filters & Slicers
     ↓
Business Insights
     ↓
Recommendations
📁 Repository Structure
SHOPIFUL-Enterprise-Ecommerce-Intelligence/
│
├── 📁 Dashboard Screenshots/
│   ├── Executive_Overview.png
│   ├── Customer_Intelligence.png
│   ├── Product_Performance.png
│   ├── Sales_Orders.png
│   ├── Returns_Delivery.png
│   ├── Payment_Revenue.png
│   └── Warehouse_Inventory.png
│
├── 📁 Dataset/
│   └── SHOPIFUL_Ecommerce_Dataset.xlsx
│
├── 📁 SQL/
│   ├── Database_Creation.sql
│   ├── Table_Creation.sql
│   ├── Data_Validation.sql
│   └── Analysis_Queries.sql
│
├── 📁 PowerBI/
│   └── SHOPIFUL_Enterprise_Analytics.pbix
│
└── 📄 README.md
💼 Recommendations
Focus on high-performing products and categories.
Develop targeted strategies for high-revenue states.
Improve customer retention by monitoring order frequency.
Analyze returned orders to reduce operational losses.
Optimize payment options based on customer preferences.
Monitor delivery partner performance across states.
Improve warehouse capacity utilization.
Maintain appropriate stock levels based on demand.
Use Power BI dashboards for recurring management reporting.
🚀 Future Enhancements
Real-time sales monitoring
Sales and demand forecasting
Customer churn prediction
Product demand prediction
Automated inventory-reorder recommendations
Advanced customer segmentation
Automated Power BI data refresh
Predictive return analysis
Delivery performance prediction
AI-based business recommendations
👩‍💻 Author
Sathya Sri M

Project: SHOPIFUL – Enterprise E-Commerce Intelligence Platform

Industry: E-Commerce

Technologies: MySQL | SQL | Power BI | DAX | Power Query | Excel

Project Focus: Data Analytics | Business Intelligence | Sales Analytics | Customer Analytics | Product Analytics | Operations Analytics

📜 License

This project is created for educational, portfolio, and data analytics demonstration purposes.
