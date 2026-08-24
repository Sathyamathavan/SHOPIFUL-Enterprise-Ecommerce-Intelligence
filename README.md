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
  <img width="880" height="500" alt="Executive overview" src="https://github.com/user-attachments/assets/b2d31f65-b678-4d5a-abf1-650597045c5b" />


### Dashboard 2 – Customer Intelligence
- Customer Revenue by State
- Orders by Status
- Customer Order Frequency
- Geographic Customer Distribution
<img width="889" height="501" alt="Customer intelligence" src="https://github.com/user-attachments/assets/f8bfd0f9-d2cd-4c78-af09-4a0fd4f97e80" />

### Dashboard 3 – Product Performance
- Sales by Category
- Product Sales Trend
- Product Price vs Sales
- Product Rating Distribution
- Top Products / Units Sold
  <img width="881" height="496" alt="product performance" src="https://github.com/user-attachments/assets/f8e0c2e3-adda-4082-93ca-0af6fde27605" />

  
### Dashboard 4 – Sales & Orders
- Total Orders by State
- Total Orders by Order Status
- Selling Price by Brand
- Reviews by Rating
- Sales Amount by Year

<img width="877" height="496" alt="sales and order performance" src="https://github.com/user-attachments/assets/cc157525-1e5b-4301-b573-826669e17420" />


### Dashboard 5 – Returns & Delivery
- Total Orders by Return Status
- Total Returns by Reason
- Delivery Partner by State
<img width="882" height="500" alt="Return and delivery performance" src="https://github.com/user-attachments/assets/792734e9-e884-435e-b4d6-505e1a720096" />

### Dashboard 6 – Payment & Revenue
- Payment Method Distribution
- Payment Amount by Method
- Payment Amount by Year
- Payment Amount by Category
  <img width="883" height="495" alt="payment and revenew " src="https://github.com/user-attachments/assets/f8ab2638-6b46-4e3f-98ee-8bbe0bbd0882" />


### Dashboard 7 – Warehouse & Inventory Intelligence
- Warehouse Capacity Utilization
- Stock Distribution by Warehouse
- Stock Quantity by Warehouse ID
- Warehouse State Map
<img width="884" height="503" alt="warehouse performance" src="https://github.com/user-attachments/assets/4721df9e-5e79-4771-b14d-affd4e6c4c43" />

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
