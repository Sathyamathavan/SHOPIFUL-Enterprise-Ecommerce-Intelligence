# 🛒 SHOPIFUL – Enterprise E-Commerce Intelligence Platform

## 📌 Industry

**E-Commerce – Online Retail & Enterprise Business Analytics**

---

## 📖 Project Overview

**SHOPIFUL – Enterprise E-Commerce Intelligence Platform** is a data analytics and business intelligence project developed to analyze and monitor the performance of an e-commerce business.

The project integrates multiple business areas including **customers, products, categories, orders, order items, payments, returns, deliveries, reviews, and warehouse operations**.

The solution uses **MySQL and SQL** for database creation, data storage, data validation, and business analysis. **Power Query** is used for ETL and data transformation, while **Microsoft Power BI** is used to create interactive dashboards, KPIs, and business reports.

The main objective is to transform raw e-commerce data into meaningful business insights that can support **data-driven decision-making, sales optimization, customer analysis, operational improvement, and inventory planning**.

---

# 🎯 Business Areas Covered

- 📈 Sales and Revenue Performance
- 👥 Customer Behaviour
- 📦 Product Performance
- 🛒 Order Analysis
- 💳 Payment Analysis
- 🔄 Returns Analysis
- 🚚 Delivery Operations
- ⭐ Customer Reviews and Ratings
- 🏭 Warehouse and Inventory Operations
- 🌍 Geographical Business Analysis

---

# 🎯 Project Objectives

- Build a structured relational database for e-commerce operations.
- Organize data from multiple business functions into related tables.
- Perform data cleaning and validation.
- Analyze sales, orders, revenue, products, and customers.
- Identify high-performing products and categories.
- Analyze customer purchasing behaviour and geographical distribution.
- Understand payment methods and payment revenue.
- Analyze return patterns and delivery operations.
- Monitor warehouse capacity and stock distribution.
- Build interactive Power BI dashboards.
- Generate meaningful business insights for management decision-making.

---

# 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| **Microsoft Excel** | Dataset source and initial data preparation |
| **MySQL** | Relational database creation and data storage |
| **SQL** | Data querying, validation and business analysis |
| **Power Query** | Data cleaning and ETL transformation |
| **Microsoft Power BI** | Interactive dashboards and data visualization |
| **DAX** | KPI and calculated measure creation |
| **GitHub** | Project documentation and version control |

---

# 📂 Dataset Introduction

The SHOPIFUL project uses an enterprise e-commerce dataset containing **10 related tables**.

| Table | Description |
|---|---|
| **Customers** | Customer information and geographical details |
| **Products** | Product information, pricing and brand details |
| **Categories** | Product category information |
| **Orders** | Main order transaction information |
| **Order_Items** | Products, quantities and order-level item information |
| **Payment** | Payment methods and payment transaction details |
| **Returns** | Return status and return-related information |
| **Deliveries** | Delivery details and delivery partner information |
| **Reviews** | Customer ratings and review information |
| **Warehouse** | Warehouse capacity, stock and location information |

---

# 🗄️ Database Design

The SHOPIFUL database is designed using a relational structure.

The **Orders** and **Order_Items** tables represent the primary transaction area, while other tables provide customer, product, payment, delivery, return, review, category, and warehouse information.

### Main Database Tables

```text
Customers
Products
Categories
Orders
Order_Items
Payment
Returns

Logical Data Flow
Customers
    │
    ↓
  Orders
    │
    ↓
Order_Items ───────→ Products ───────→ Categories
    │
    ├──────────────→ Payment
    │
    ├──────────────→ Returns
    │
    ├──────────────→ Deliveries
    │
    └──────────────→ Reviews

Warehouse
    │
    ↓
Stock & Capacity Analysis
🗃️ Database Creation

The database was created using MySQL.

Database Setup
CREATE DATABASE shopiful;
USE shopiful;

The required tables were then created according to the business requirements.

🔎 SQL Analysis

SQL was used throughout the project for:

Database creation
Table creation
Data inspection
Data validation
Record count validation
Duplicate checking
Null value checking
Data consistency checks
Business analysis
KPI validation
Cross-table analysis

SQL Analysis Areas
Order Volume
Sales & Revenue
Product Performance
Category Performance
Customer Analysis
Payment Analysis
Return Analysis
Delivery Analysis
Warehouse Stock Analysis
Data Validation

🧹 Data Cleaning & Validation

Before developing the dashboards, the dataset was cleaned and validated.

Data Cleaning Activities
Removed duplicate records where required.
Checked and handled null values.
Corrected incorrect data types.
Standardized categorical values.
Converted numerical columns into appropriate numeric data types.
Validated date fields.
Checked primary and related key values.
Verified table relationships.
Performed record-count validation.
🔄 ETL Process

The project follows an ETL workflow using Power Query.

Extract

Data was extracted from the MySQL database and source datasets.

Transform

The data was cleaned, standardized, formatted, and prepared for analysis.

Load

The transformed data was loaded into the Power BI data model.

ETL Workflow
MySQL / Dataset
      ↓
    Extract
      ↓
   Transform
      ↓
      Load
      ↓
 Power BI Model

🔗 Connecting MySQL with Power BI

The MySQL database was connected to Microsoft Power BI to create the analytical environment.

Process
Open Power BI Desktop.
Select the MySQL database connector.
Connect to the SHOPIFUL database.
Select the required tables.
Load the data into Power Query.
Perform required transformations.
Apply the transformations.
Create relationships between related tables.
Develop DAX measures.
Build dashboards and visualizations.
📐 Basic DAX Measures

DAX was used to create important business KPIs.

Example – Total Customers


Example – Total Customers
Total Customers = DISTINCTCOUNT(Customers[Customer_ID])
Example – Total Orders
Total Orders = DISTINCTCOUNT(Orders[Order_ID])
Example – Total Quantity
Total Quantity = SUM(Order_Items[Quantity])

Additional measures were created for sales, revenue, average order value, payment amount, returns, and other business metrics.

📊 Power BI Dashboard

The SHOPIFUL project contains 7 interactive Power BI dashboard pages.

1️⃣ Executive Overview Dashboard

The Executive Overview provides a high-level summary of the overall e-commerce business performance.

Visualizations
Monthly Sales Trend → Line Chart
Sales by Category → Donut Chart
Sales by State → Horizontal Bar Chart
Top 10 Products by Sales → Horizontal Bar Chart
Payment Method Analysis → Donut Chart
Purpose

This dashboard provides management with a quick overview of:

Sales trends
Category performance
State-wise sales
Top-performing products
Payment preferences
2️⃣ Customer Intelligence Dashboard

This dashboard focuses on customer behaviour and geographical distribution.

Visualizations
Customer Revenue by State → Bar Chart
Orders by Status → Bar Chart
Customer Order Frequency → Bar Chart
Geographic Distribution → Map of India
Purpose

The dashboard helps analyze:

Customer revenue contribution
Customer order frequency
Order status
Geographical customer distribution
3️⃣ Product Performance Dashboard

This dashboard analyzes product and category performance.

Visualizations
Sales by Category → Pie Chart
Product Sales Trend → Line Chart
Product Price vs Sales → Bar Chart
Purpose

The dashboard helps identify:

High-performing categories
Product sales trends
Product pricing and sales performance
4️⃣ Sales & Orders Dashboard

This dashboard provides detailed analysis of sales and order activity.

Visualizations
Total Orders by State → Pie Chart
Total Orders by Order Status → Pie Chart
Selling Price by Brand → Horizontal Bar Chart
Review by Rating → Line Chart
Sales Amount by Year → Vertical Bar Chart
Purpose

The dashboard helps understand:

State-wise order distribution
Order status
Brand-level selling price
Customer ratings
Yearly sales performance
5️⃣ Returns & Delivery Dashboard

This dashboard focuses on returns and delivery operations.

Visualizations
Total Orders by Return Status → Pie Chart
Total Returns by Reason → Bar Chart
Delivery Partner by State → Pie Chart
Purpose

The dashboard helps identify:

Return status
Major return reasons
Delivery partner distribution
Operational areas requiring attention
6️⃣ Payment & Revenue Dashboard

This dashboard analyzes payment behaviour and revenue contribution.

Visualizations
Payment Method Distribution → Pie Chart
Payment Amount by Method → Donut Chart
Payment Amount by Year → Line Chart
Payment Amount by Category → Horizontal Bar Chart
Purpose

The dashboard provides insights into:

Customer payment preferences
Payment revenue
Yearly payment trends
Category-wise payment contribution
7️⃣ Warehouse Operations Dashboard

This dashboard focuses on warehouse and inventory operations.

Visualizations
Warehouse Capacity Utilization → Gauge Chart
Stock Distribution by Warehouse → Pie Chart
Stock Quantity by Warehouse ID → Bar Chart
Warehouse State Map → Map of India
Purpose

The dashboard helps monitor:

Warehouse capacity utilization
Stock distribution
Warehouse-level inventory
Geographical warehouse locations
🎛️ Filters & Slicers

Interactive filters and slicers were implemented to make the dashboards dynamic.

Users can filter and analyze information based on relevant dimensions such as:

Date
State
Category
Product
Order Status
Payment Method
Return Status
Warehouse
Brand

The filters allow users to drill into specific business areas and compare performance dynamically.

Deliveries
Reviews
Warehouse
