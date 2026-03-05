# Chocolate & Beverage Sales and Profitability Analysis

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Data Source](#-data-source)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [How to Use](#-how-to-use)

---

## 📊 Project Overview
This project analyzes chocolate and beverage sales data to evaluate business performance in terms of revenue, expenses, and profitability across different countries, states, and products.

The goal of this analysis is to identify high-performing and low-performing products, understand regional sales patterns, and analyze profit margins to support data-driven business decisions.

---

## 🗂️ Data Source
- Dataset used for **academic data analysis and visualization practice**.
- The dataset contains **1,500 sales transactions**.
- Includes an **order-level sales table** and supporting **dimension tables**.

### Key Variables
- Order ID
- Product ID
- SalesPerson ID
- Country
- State
- Order Date
- Selling Price
- Product Cost
- Sales Amount
- Expenses
- Profit
- Profit Margin
- Order Status
- Customers
- Quantity

---

## 🛠️ Tools & Technologies
- **Microsoft Excel** – Dataset storage
- **Power BI Desktop** – Data modeling and dashboard creation
- **Power Query** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – Calculated columns and metrics
- **Data Visualization** – Interactive dashboards

---

## 🧹 Data Cleaning & Preparation
The following data preprocessing steps were performed:

- Cleaned and trimmed text fields to remove hidden spaces and inconsistencies.
- Standardized **Country and State** names.
- Converted **Date column** to proper date format.
- Converted numerical columns such as **Sales, Expenses, Selling Price, and Product Cost** to appropriate data types.
- Standardized **Order Status and Customer fields**.
- Created calculated columns using **DAX formulas**.

### Calculated Metrics

**Profit Calculation**
```
Profit = Sales - (Product Cost + Expenses)
```

**Profit Margin Calculation**
```
Profit_Margin = DIVIDE(Sales[Profit], Sales[Selling Price])
```

---

## 🔍 Exploratory Data Analysis (EDA)

The analysis explored several business questions:

- What is the overall sales performance across countries?
- Which products generate the highest revenue and profit?
- How do sales trends vary across months?
- Which regions experience higher order cancellations?
- Which product categories contribute the most to profitability?

The Power BI dashboard visualizes these insights through KPIs, charts, and trend analysis.

---

## 💡 Key Insights

- Total sales are approximately **₹3 million from 1,500 orders**.
- **Top-selling products:**
  - Milk Choco Delights
  - Hot Cocoa
  - Chocolate Almond Bites
- **Most profitable category:** Bites & Snacks, followed by Cookies and Cocoa Drinks.
- **Highest profit by country:**
  - United Kingdom
  - Canada
  - Philippines
- Sales data shows **seasonal demand patterns**, especially for chocolate and cocoa-based products.
- **United Kingdom has the highest order cancellations**, indicating potential operational challenges.

---

## 🚀 Recommendations

Based on the analysis:

- Increase inventory levels for high-demand products such as:
  - Hot Cocoa
  - Milk Choco Delights
  - Chocolate Almond Bites
- Improve supply chain and delivery processes in the **United Kingdom** to reduce cancellation rates.
- Focus marketing campaigns on **high-margin categories** like Bites & Snacks and Cookies.
- Provide support and coaching for salespersons with high cancellation rates.
- Implement **demand forecasting models** to improve inventory planning.
- Introduce **cancellation root-cause tracking** to identify logistics or supply issues.

---

## ⚙️ How to Use

1. Download the **Power BI (.pbix) file** from the repository.
2. Open the file using **Power BI Desktop**.
3. Explore the interactive dashboard to analyze:
   - Sales performance
   - Profitability trends
   - Regional sales distribution
   - Product performance insights
