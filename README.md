Chocolate & Beverage Export Sales Dashboard
Project Description

This Power BI dashboard provides a comprehensive analysis of chocolate and beverage export sales performance across multiple countries.

The dashboard offers deep insights into sales trends, product profitability, order cancellations, and salesperson performance.

It supports data-driven decision-making for export operations.

Key Features

Overall Product Sales Performance – Track sales across different product categories

Product Profitability Analysis – Analyze profit margins by product category

Sales & Expense Tracking – Monitor monthly sales trends and expenses

Cancellation Analytics – Breakdown of cancelled orders by country, product, and time

Geographic Performance – Country-wise sales distribution and performance metrics

Salesperson Performance – Individual performance scores and sales contributions

Key Metrics

Total Sales: ₹3M

Total Profit: ₹2.70M

Total Order Quantity: 1,500 units

Total Cancelled Quantity: 80 units

Total Loss: ₹138K

Installation Instructions
Prerequisites

Power BI Desktop (Latest version recommended)

Windows 10/11 or macOS (with Parallels or Boot Camp)

Setup Steps

Clone the repository

Download Power BI Desktop

Visit Power BI Desktop Download

Download and install the latest version

Open the dashboard

Launch Power BI Desktop

Open Chocolate_and_Beverage_Export_Sales.pbix file

Configure data source (if required)

Go to File → Options and settings → Data source settings

Update the data source path if required

Click Refresh to load the data

Publish to Power BI Service (optional)

Sign in to your Power BI account

Click Publish to share the dashboard online

Data Sources

The dashboard uses export sales data with the following key tables:

Sales Transactions Table

Order ID

Date

Product Name

Category

Quantity

Unit Price

Total Sales

Country

State/Region

Sales Person

Product Information

Product Categories:

Cocoa Drinks (Hot Cocoa, Milk Choco Delights)

Chocolate Bars (Chocolate Almond Bites, Dark Chocolate Bites)

Snacks (Bites-Snacks, Energy-Health Bars)

Specialty (Raspberry Velvet, Peanut Butter Cubes, etc.)

Geographic Data

Primary Markets:

United Kingdom

Canada

Philippines

Australia

New Zealand

United States

Regional breakdown by State or Province

Order Status

Delivered Orders

Cancelled Orders with reasons

Code / Project Structure
chocolate-beverage-export-sales/
│
├── Chocolate_and_Beverage_Export_Sales.pbix
├── data/
│   ├── sales_transactions.csv
│   ├── product_information.csv
│   └── customer_data.csv
│
├── documentation/
│   ├── README.md
│   ├── data_dictionary.md
│   └── user_guide.md
│
├── reports/
│   └── monthly_reports/
│
└── LICENSE
Results and Evaluation
Key Findings
Sales Performance
Top Performing Products

Milk Choco Delights – ₹0.34M

Hot Cocoa – ₹0.31M

Chocolate Almond Bites – ₹0.28M

Geographic Distribution

United Kingdom – ₹0.81M (30.1%)

Canada – ₹0.65M (23.96%)

Philippines – ₹0.49M (18.03%)

New Zealand – ₹0.43M (15.85%)

United States – ₹0.30M (10.97%)

Australia – ₹0.03M (1.09%)

Top Sales Performers

Oliver – ₹213K (Performance Score: 100%)

Lucas – ₹211K (Performance Score: 99.02%)

Henry – ₹202K (Performance Score: 94.72%)

Thomas – ₹198K (Performance Score: 92.75%)

Cancellation Insights

Highest cancellations by country:

United Kingdom – 26 orders

United States – 18 orders

Philippines – 15 orders

Product-level issues:

Hot Cocoa – 11 cancellations

Milk Chocolate – 9 cancellations

Indicates possible quality or availability issues

Seasonal patterns:

Peak cancellations in June (13) and July (12)

Suggests seasonal demand fluctuations or operational constraints

Salesperson performance:

Lucas and Luciano show higher cancellation counts

Indicates need for additional training or support

Business Impact

Revenue optimization through top product and region identification

Risk mitigation using cancellation pattern analysis

Better resource allocation with performance-based territory management

Improved customer satisfaction through geographic delivery insights

Future Work
Planned Enhancements

Predictive analytics

Sales forecasting

Cancellation prediction

Inventory demand forecasting

Advanced visualizations

Drill-through reports

Custom visuals

Real-time updates

Enhanced data integration

Live database connections

Automated refresh

CRM integration

Additional metrics

Customer lifetime value

Product return rate

Shipping and logistics KPIs

Customer satisfaction scores

Mobile optimization

Power BI mobile layout

Mobile app support

Advanced segmentation

Customer segmentation

Product bundling

Market basket analysis

Alert system

KPI alerts

Cancellation rate alerts

Low stock alerts

Acknowledgments & References
Tools & Technologies

Microsoft Power BI Desktop

DAX (Data Analysis Expressions)

Power Query

Data Sources

Export sales transaction records

Product catalog database

Customer and geographic information systems
