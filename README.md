
# 📊 Power BI Sales Analytics Dashboard

This project is a dynamic **Sales Analytics Dashboard** developed using **Power BI**, designed to deliver comprehensive insights into sales performance across time, store locations, product categories, and more.

---

## 🚀 Project Overview

The dashboard enables users to monitor and analyze:

- 📈 **Monthly Sales Trends**
- 📦 **Total Orders & Quantity Sold**
- 📆 **Sales Distribution on a Calendar Heat Map**
- 🏪 **Store-wise Sales Comparison**
- 📅 **Weekday vs Weekend Performance**
- 📊 **Category & Product Analysis**

The dashboard dynamically updates based on user slicer selections (e.g., selected month), providing detailed Month-over-Month (MoM) comparisons and trends.

---

## 📌 KPI Metrics Implemented

### 1. Total Sales Analysis
- Monthly total sales calculation
- Month-on-Month (MoM) growth %
- Absolute sales difference vs previous month

### 2. Total Orders Analysis
- Count of distinct orders per month
- MoM order growth & difference

### 3. Total Quantity Sold
- Monthly sum of quantities sold
- MoM trend & quantity difference

---

## 📊 Visualizations

### 1. **Calendar Heat Map**
- Daily color-coded sales volume
- Hover tooltips showing: Sales, Orders, Quantity

### 2. **Sales by Weekdays vs Weekends**
- Comparative analysis of weekday and weekend sales

### 3. **Sales by Store Location**
- Sales split by store with MoM indicators
- Conditional formatting for trend direction

### 4. **Daily Sales with Average Line**
- Line and bar chart showing daily sales
- Highlights above/below average days

### 5. **Sales by Product Category**
- Visualization of category contribution to overall sales

### 6. **Top 10 Products by Sales**
- Bar chart showing top-performing products

---

## 🛠️ DAX & Modeling Features

- Custom Date Table with calculated columns:
  - Month, Month-Year, Weekday/Weekend, Week Number, etc.
- DAX Measures for:
  - `Total Sales`, `Orders`, `Quantities`
  - `Current Month (CM)` and `Previous Month (PM)` values
  - MoM Growth % and Differences
  - Dynamic Labels for Tooltips and Titles
- Categorization of days into **Weekday/Weekend**
- **Conditional Coloring** for average-based visual cues

---

## 🧱 Technologies Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data modeling, dashboard creation |
| **DAX** | Calculated columns and measures |
| **Power Query** | Data transformation and cleanup |

---

## 📂 Folder Structure

```bash
.
├── README.md
├── [CoffeeShopSales Dashboard.pbix] | (https://github.com/GnanadeepHarijana/powerbi-sales-dashboard/blob/main/CoffeeShopSales%20Dashboard.pbix)  |          # Main Power BI file
├── Data/
│   └── [RAW_DATA CoffeShopSales.xlsx]        # Sample or real transaction data
├── Assets/
│   └── [CoffeeShopSales Dashboard.pdf] | (https://github.com/GnanadeepHarijana/powerbi-sales-dashboard/blob/main/CoffeeShopSales%20Dashboard.pdf) |    
└── DAX/
    └── [powerBI_Documentation.txt]  | (https://github.com/GnanadeepHarijana/powerbi-sales-dashboard/blob/main/PowerBI_Documentation.txt)                  | #DAX measures used
