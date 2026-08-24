# SHOPIFUL – Enterprise E-Commerce Intelligence Platform

## 📊 Industry
**E-Commerce – Online Retail & Enterprise Business Analytics**

## 📌 Project Overview
SHOPIFUL Enterprise E-Commerce Intelligence Platform is a data analytics and business intelligence project designed to analyze the sales, customer, product, order, payment, return, delivery, review, and warehouse performance of an e-commerce business.

The project uses **MySQL and SQL** for database creation, data storage, validation, and analysis, and **Microsoft Power BI** for interactive dashboards and business intelligence reporting.

The solution integrates customers, products, categories, orders, payments, returns, deliveries, reviews, and warehouse operations to identify sales trends, customer behaviour, product performance, operational issues, payment patterns, and inventory-related insights.

## 🎯 Business Areas Covered
- Sales and revenue performance
- Customer behaviour and order frequency
- Product and category performance
- Order analysis
- Payment analysis
- Returns and delivery performance
- Product reviews and ratings
- Warehouse and inventory operations
- Geographical business performance

## 🎯 Project Objectives
- Build a structured relational database for e-commerce operations.
- Organize customer, product, category, order, payment, return, delivery, review, and warehouse data.
- Analyze sales, orders, revenue, discounts, and product performance.
- Identify top-performing products and categories.
- Analyze customer purchasing behaviour and geographical distribution.
- Evaluate payment methods and payment revenue.
- Analyze return patterns and delivery performance.
- Monitor warehouse capacity and stock distribution.
- Build interactive Power BI dashboards for management reporting.
- Generate actionable business recommendations.

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Excel | Dataset source, inspection and initial preparation |
| MySQL | Database creation and data storage |
| SQL | Data validation, querying and business analysis |
| Power Query | Data cleaning and transformation |
| Microsoft Power BI | Interactive dashboard development |
| DAX | KPI and calculated measure creation |
| GitHub | Project documentation and version control |

## 📂 Dataset Description
The project uses an **Enterprise E-Commerce Dataset** containing multiple related tables.

| Table | Description |
|---|---|
| Customers | Customer details and geographical information |
| Products | Product details, pricing and product information |
| Categories | Product category information |
| Orders | Main order transaction data |
| Order_Items | Individual products and quantities within orders |
| Payment | Payment method and payment transaction information |
| Returns | Return status and return-related information |
| Deliveries | Delivery and delivery partner information |
| Reviews | Customer ratings and product review information |
| Warehouse | Warehouse capacity, stock and location information |

## 🗄️ Database Design
The database follows a relational structure where **Orders** and **Order_Items** act as the main transaction areas, connected with customer, product, category, payment, return, delivery, review, and warehouse information.

## 🔎 SQL Analysis
SQL was used for:
- Database creation
- Table creation
- Data inspection
- Data validation
- Record-count validation
- Duplicate checking
- NULL/value checking
- KPI validation
- Cross-table business analysis

### Business Analysis Performed
- Order volume analysis
- Sales and revenue analysis
- Product performance analysis
- Category performance analysis
- Customer analysis
- Payment analysis
- Return analysis
- Delivery analysis
- Warehouse stock analysis
- Data validation

## 📊 Power BI Dashboards

### Dashboard 1 – Executive Overview
- Monthly Sales Trend
- Sales by Category
- Sales by State
- Top 10 Products by Sales
- Payment Method Analysis

### Dashboard 2 – Customer Intelligence
- Customer Revenue by State
- Orders by Status
- Customer Order Frequency
- Geographic Customer Distribution

### Dashboard 3 – Product Performance
- Sales by Category
- Product Sales Trend
- Product Price vs Sales
- Product Rating Distribution
- Top Products / Units Sold

### Dashboard 4 – Sales & Orders
- Total Orders by State
- Total Orders by Order Status
- Selling Price by Brand
- Reviews by Rating
- Sales Amount by Year

### Dashboard 5 – Returns & Delivery
- Total Orders by Return Status
- Total Returns by Reason
- Delivery Partner by State

### Dashboard 6 – Payment & Revenue
- Payment Method Distribution
- Payment Amount by Method
- Payment Amount by Year
- Payment Amount by Category

### Dashboard 7 – Warehouse & Inventory Intelligence
- Warehouse Capacity Utilization
- Stock Distribution by Warehouse
- Stock Quantity by Warehouse ID
- Warehouse State Map

## 🖼️ Dashboard Screenshots

### Customer Intelligence Dashboard
![Customer Intelligence Dashboard](Dashboard_Screenshots/Customer_Intelligence.png)

### Product Performance Dashboard
![Product Performance Dashboard](Dashboard_Screenshots/Product_Performance.png)

### Other Dashboard Pages
Additional dashboard screenshots are included in the `Dashboard_Screenshots` folder.

## 📈 Key KPIs

| KPI | Business Purpose |
|---|---|
| Total Sales | Measures overall revenue generated |
| Total Orders | Measures order volume |
| Total Customers | Measures customer base |
| Total Units Sold | Measures product sales volume |
| Average Order Value | Measures average revenue per order |
| Total Profit | Measures overall profitability |
| Return Rate | Measures return frequency |
| Payment Amount | Measures payment revenue |
| Warehouse Capacity | Measures available warehouse capacity |
| Stock Quantity | Measures inventory availability |

## 💡 Key Business Insights

### Sales Performance
Monitor sales trends across months, years, categories, and states.

### Product Performance
Identify products and categories contributing significantly to sales.

### Customer Behaviour
Understand customer distribution, revenue contribution, and order frequency.

### Order Performance
Analyze order volume and order-status patterns.

### Payment Behaviour
Identify popular payment methods and payment revenue contribution.

### Returns Analysis
Identify return patterns and major return reasons.

### Delivery Analysis
Understand delivery partner distribution across states.

### Warehouse Performance
Monitor warehouse capacity and stock distribution.

### Geographical Analysis
Identify states contributing significantly to customers, orders, and revenue.

### Management Reporting
Provide a centralized dashboard for faster, data-driven decisions.

## 🔄 Project Workflow
```text
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
Power BI Data Connection
    ↓
Power Query Transformation
    ↓
Data Modelling & Relationships
    ↓
DAX Measures & KPIs
    ↓
Dashboard Development
    ↓
Business Insights
    ↓
Recommendations
SHOPIFUL-Enterprise-Ecommerce-Intelligence/
│
├── README.md
│
├── Dataset/
│   └── SHOPIFUL_Ecommerce_Dataset.xlsx
│
├── SQL/
│   ├── Database_Creation.sql
│   ├── Table_Creation.sql
│   ├── Data_Validation.sql
│   └── Analysis_Queries.sql
│
├── PowerBI/
│   └── SHOPIFUL_Enterprise_Analytics.pbix
│
├── Dashboard_Screenshots/
│   ├── Executive_Overview.png
│   ├── Customer_Intelligence.png
│   ├── Product_Performance.png
│   ├── Sales_Orders.png
│   ├── Returns_Delivery.png
│   ├── Payment_Revenue.png
│   └── Warehouse_Inventory.png
│
└── Documentation/
    └── Project_Report.pdf
💼 Recommendations
Focus on high-performing products and categories.
Develop targeted strategies for high-revenue states.
Improve customer retention by monitoring order frequency.
Analyze unsuccessful and returned orders to reduce operational losses.
Optimize payment options based on customer preferences.
Monitor delivery partner performance across states.
Improve warehouse capacity utilization.
Maintain appropriate stock levels based on demand.
Use Power BI dashboards as a recurring management reporting system.
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

👤 Author

Sathya Sri M

Project: SHOPIFUL – Enterprise E-Commerce Intelligence Platform

Industry: E-Commerce

Technologies: MySQL | SQL | Power BI | DAX | Power Query | Excel

Project Focus: Data Analytics | Business Intelligence | Sales Analytics | Customer Analytics | Product Analytics | Operations Analytics

📜 License

This project is created for educational, portfolio, and data analytics demonstration purposes.
