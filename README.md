# Chocolate & Beverage Export Sales Dashboard 

## Project Description

This Power BI dashboard provides a comprehensive analysis of chocolate and beverage export sales performance across multiple countries. The dashboard offers deep insights into sales trends, product profitability, order cancellations, and salesperson performance, enabling data-driven decision-making for export operations.

## Key Features:
- **Overall Product Sales Performance** - Track sales across different product categories
- **Product Profitability Analysis** - Analyze profit margins by product category
- **Sales & Expense Tracking** - Monitor monthly sales trends and expenses
- **Cancellation Analytics** - Detailed breakdown of cancelled orders by country, product, and time
- **Geographic Performance** - Country-wise sales distribution and performance metrics
- **Salesperson Performance** - Individual performance scores and sales contributions

## Key Metrics:
- Total Sales: ₹3M
- Total Profit: ₹2.70M
- Total Order Quantity: 1,500 units
- Total Cancelled Quantity: 80 units
- Total Loss: ₹138K

## Installation Instructions

## Prerequisites
- **Power BI Desktop** (Latest version recommended)
- Windows 10/11 or macOS (with Parallels/Boot Camp)

## Setup Steps

1. Clone the Repository
2. Download Power BI Desktop
- Visit Power BI Desktop Download
- Download and install the latest version
3. Open the Dashboard
- Launch Power BI Desktop
- Open Chocolate_and_Beverage_Export_Sales.pbix file
4. Configure Data Source (if needed)
- Go to File → Options and settings → Data source settings
- Update the data source path if required
- Click Refresh to load the data
5. Publish to Power BI Service (Optional)
- Sign in to your Power BI account
- Click Publish to share the dashboard online

 Data Sources
- The dashboard utilizes export sales data with the following key tables:
# Sales Transactions Table
- Order ID, Date, Product Name, Category
- Quantity, Unit Price, Total Sales
- Country, State/Region
- Sales Person
# Product Information
- Product Categories:
  - Cocoa Drinks (Hot Cocoa, Milk Choco Delights)
  - Chocolate Bars (Chocolate Almond Bites, Dark Chocolate Bites)
  - Snacks (Bites-Snacks, Energy-Health Bars)
  - Specialty (Raspberry Velvet, Peanut Butter Cubes, etc.)
# Geographic Data
- Primary Markets: United Kingdom, Canada, Philippines, Australia, New Zealand, United States
- Regional breakdowns by State/Province
# Order Status
- Delivered Orders
- Cancelled Orders with reasons

# Code/Project Structure
 
  chocolate-beverage-export-sales/
│
├── 📄 Chocolate_and_Beverage_Export_Sales.pbix    # Main Power BI dashboard file
├──  data/
│   ├── 📄 sales_transactions.csv                   # Raw sales data
│   ├── 📄 product_information.csv                  # Product catalog
│   └──  customer_data.csv                        # Customer and location data
│
├──  documentation/
│   ├── 📄 README.md                                # This file
│   ├── 📄 data_dictionary.md                       # Field descriptions
│   └── 📄 user_guide.md                            # Dashboard usage guide
│
├──  reports/
│   └── 📄 monthly_reports/                         # Generated reports
│
└── 📄 LICENSE

# Results and Evaluation
# Key Findings
# Sales Performance
# Top Performing Products:
  - Milk Choco Delights - ₹0.34M
  - Hot Cocoa - ₹0.31M
  - Chocolate Almond Bites - ₹0.28M
# Geographic Distribution
  - United Kingdom: Highest profit contributor (₹0.81M - 30.1%)
  - Canada: Second highest (₹0.65M - 23.96%)
  - Philippines: Third position (₹0.49M - 18.03%)
  - New Zealand: ₹0.43M (15.85%)
  - United States: ₹0.30M (10.97%)
  - Australia: ₹0.03M (1.09%)
# Top Sales Performers
  - Oliver - ₹213K (Performance Score: 100%)
  - Lucas - ₹211K (Performance Score: 99.02%)
  - Henry - ₹202K (Performance Score: 94.72%)
  - Thomas - ₹198K (Performance Score: 92.75%)
# Cancellation Insights
 Highest Cancellations by Country:
  - United Kingdom: 26 orders (Supply chain challenges identified)
  - United States: 18 orders
  - Philippines: 15 orders
  - Product-Level Issues:
  - Hot Cocoa: 11 cancellations
  - Milk Chocolate: 9 cancellations
  - Indicates potential quality or availability issues
# Seasonal Patterns:
  - Peak cancellations in June (13) and July (12)
  - Suggests seasonal demand fluctuations or operational constraints
# Sales Person Performance:
  - Lucas and Luciano show higher cancellation counts
  - May indicate need for additional training or support
# Business Impact
  - Revenue Optimization: Identified top-performing products and regions for focused marketing
  - Risk Mitigation: Cancellation patterns highlight areas needing operational improvement
  - Resource Allocation: Sales performance data enables better territory management
  - Customer Satisfaction: Geographic insights help address regional delivery challenges
  - Future Work
Planned Enhancements
Predictive Analytics
Implement forecasting models for sales trends
Predict potential cancellations using machine learning
Demand forecasting for inventory optimization
Advanced Visualizations
Add interactive drill-through capabilities
Implement custom visuals for better user experience
Real-time dashboard updates
Enhanced Data Integration
Connect to live database sources
Automated data refresh schedules
Integration with CRM systems
Additional Metrics
Customer lifetime value analysis
Product return rate tracking
Shipping and logistics performance
Customer satisfaction scores
Mobile Optimization
Create mobile-responsive dashboard layout
Power BI mobile app configuration
Advanced Segmentation
Customer segmentation analysis
Product bundling opportunities
Market basket analysis
Alert System
Automated alerts for KPI thresholds
Cancellation rate monitoring
Low stock notifications
 Acknowledgments & References
Tools & Technologies
Microsoft Power BI Desktop - Data visualization and business analytics
DAX (Data Analysis Expressions) - Custom calculations and measures
Power Query - Data transformation and preparation
Data Sources
Export sales transaction records
Product catalog database
Customer and geographic information systems


