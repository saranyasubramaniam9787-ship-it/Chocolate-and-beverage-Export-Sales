
# Chocolate & Beverage Sales Analytics Dashboard

A comprehensive **Power BI analysis of chocolate and beverage sales data** to evaluate business performance, identify profitable products, and support **data-driven decision-making across regions**.

---

# 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Data Source](#-data-source)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [How to Use](#-how-to-use)
- [Conclusion](#-conclusion)

---

# Project Overview

**Objective:**  
Analyze chocolate and beverage sales data to evaluate business performance in terms of **revenue, expenses, and profitability** across different countries, states, and products.

## Business Problems Addressed

🔍 Identify high-performing and low-performing chocolate and beverage products  

🌍 Understand regional sales patterns and profitability by country/state  

💰 Analyze profit margins to optimize pricing and cost strategies  

📉 Investigate order cancellation patterns to reduce revenue loss  

📈 Support data-driven decisions for inventory, marketing, and supply chain improvements  

---

## 🗂️ Data Source

- **Source:** Public dataset selected for independent data analysis.
- **Data Type:** Panel Data (sales observations across multiple products and regions over time)
- **File Format:** Excel (.xlsx)
- **Dataset Size:** ~1–2 MB
- **Records:** 1,500+ sales transactions
- **Total Transactions:** 2,391

### Key Variables

- **Order_ID, Product_ID, SalesPerson_ID** – Unique identifiers  
- **Country, State** – Geographic dimensions  
- **Date** – Transaction timestamp  
- **Selling Price, Product Cost, Sales, Expenses** – Financial metrics  
- **Profit, ProfitMargin** – Calculated profitability KPIs  
- **Order Status, Customers, Quantity, Box Size** – Operational attributes  

---

# 🛠️ Tools & Technologies

- **Power BI Desktop** – Data modeling, DAX calculations, interactive dashboards  
- **Power Query (M Language)** – ETL, data cleaning & transformation  
- **Microsoft Excel** – Source data storage & validation  
- **DAX (Data Analysis Expressions)** – Custom metrics such as Profit and Profit Margin  
- **Markdown** – GitHub documentation formatting  

---

# 🧹 Data Cleaning & Preparation

All preprocessing was performed in **Power Query** before loading the data into the Power BI model.

## Standardization Steps

- **Order_ID, Product_ID, SalesPerson_ID**
  - Applied `Clean()` and `Trim()` to remove hidden characters and extra spaces.

- **Country, State**
  - Applied `Clean()` and `Trim()`.
  - Standardized formatting using **Capitalize Each Word**.

- **Date**
  - Applied `Clean()` and `Trim()`.
  - Converted the column to **Date data type**.

- **Sales, Expenses, Selling Price**
  - Applied `Clean()` and `Trim()`.
  - Converted values to **Decimal Number format**.

- **Quantity, Boxes, Product Cost, Customers**
  - Applied `Clean()` and `Trim()`.
  - Converted values to **Whole Number format**.

- **Order Status**
  - Applied `Clean()` and `Trim()`.
  - Converted values to **Text format**.
## Feature Engineering (DAX)

```DAX
-- Profit Calculation
Profit = Sales[Sales] - (Sales[Product Cost] + Sales[Expenses])

-- Profit Margin Calculation
Profit_Margin = DIVIDE(Sales[Profit], Sales[Selling Price])
```

## Data Quality Checks

- Removed hidden characters and extra whitespace  
- Standardized geographic field formatting  
- Validated numeric data types for aggregations  
- Used `DIVIDE()` to prevent division-by-zero errors  

---

# 🔍 Exploratory Data Analysis (EDA)

## Statistical Summary – Sales Distribution

| Metric | Value |
|------|------|
| Mean | 1,805.19 |
| Median | 709.20 |
| Mode | 132.00 |
| Standard Deviation | 2,895.80 |
| Skewness | 3.67 (Right Skewed) |
| Kurtosis | 19.24 (Heavy-tailed distribution) |
| Range | 1.00 – 30,502.50 |
| Total Sum | 2,707,782.90 |

## Key Analytical Questions

- What are the **top-selling products by revenue and volume**?
- Which products generate the **highest profit margins**?
- How do **sales and cancellations vary across countries and seasons**?
- Is there a **relationship between order size and cancellation risk**?
- Which **regions or salespersons need operational improvements**?

---

# 💡 Key Insights

🏆 **Top-Selling Products**  
- Milk Choco Delights  
- Hot Cocoa  
- Chocolate Almond Bites  

💰 **Most Profitable Category**  
- Bites & Snacks  
- Cookies  
- Cocoa Drinks  

🌐 **Regional Performance**

- 🇬🇧 United Kingdom and 🇨🇦 Canada generate the **highest total profit**
- However, **United Kingdom has the highest cancellations (80 orders)**

📅 **Seasonal Patterns**

Sales peaks occur in **April, June, and July**, indicating seasonal demand for chocolate and cocoa products.

📉 **Cancellation Drivers**

- Products with highest cancellations: **Hot Cocoa and Milk Choco Delights**
- Cancellations increase during **June and July**

---

# 🚀 Recommendations

## 📦 Inventory & Supply Chain

- Increase stock levels for **Hot Cocoa, Milk Choco Delights, and Chocolate Almond Bites** during peak months.
- Improve **logistics and delivery operations in the UK**.

## 🎯 Marketing Strategy

- Promote **high-margin categories such as Bites & Snacks and Cookies**.
- Conduct **customer feedback surveys** for products with high cancellation rates.

## 👥 Sales Performance

- Provide training for **salespersons with higher cancellation rates**.
- Segment territories by **risk and performance level**.

## 🤖 Advanced Analytics

- Implement **demand forecasting models**.
- Build a **cancellation root-cause tracking system**.

---

# ⚙️ How to Use

## Prerequisites

- Microsoft **Power BI Desktop**
- Excel to open the source dataset

## Running the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/chocolate-sales-analytics.git
```

### 2️⃣ Open the Power BI File

1. Launch **Power BI Desktop**
2. Go to **File → Open**
3. Select **Chocolate_Sales_Analysis.pbix**

### 3️⃣ Refresh Data

- Click **Home → Refresh**
- Ensure the file path to **Chocolate_Sales_Dataset.xlsx** is correct.

### 4️⃣ Explore the Dashboard

Navigate through report pages:

- Sales Overview  
- Product Performance  
- Regional Analysis  
- Cancellation Analysis  
- Salesperson Insights  

Use **slicers (Country, Date, Product Category)** for interactive filtering.

---

# 📁 Project Structure

```
chocolate-sales-analytics
│
├── Chocolate_Sales_Analysis.pbix
├── data
│   └── Chocolate_Sales_Dataset.xlsx
│
├── docs
│   └── Documentation_of_Chaoculate.docx.pdf
│
├── README.md
└── requirements.txt
```

---

 Conclusion

This Power BI dashboard provides a **complete analytical view of chocolate and beverage sales performance**, helping businesses to:

- Identify **top revenue drivers**
- Detect **operational bottlenecks**
- Optimize **inventory and marketing strategies**
- Improve **sales performance and regional operations**

By leveraging these insights, organizations can **increase revenue, reduce cancellations, and improve supply chain efficiency through data-driven decision-making**.
## 📊Project Overview
This project analyzes chocolate and beverage sales data to evaluate business performance in terms of revenue, expenses, and profitability across different countries, states, and products.

The goal of this analysis is to identify high-performing and low-performing products, understand regional sales patterns, and analyze profit margins to support data-driven business decisions.

---
