# ☕ Coffee Sales Dashboard - Excel Data Analysis Project

## 📋 Project Overview
This project demonstrates a **complete data analysis workflow using Microsoft Excel**.  
It features a **Coffee Sales Dashboard**, created using:

- Pivot Tables
- Pivot Charts
- Slicers
- Formulas (VLOOKUP, IF, TEXT, etc.)

The goal is to generate **clear and actionable insights** to understand coffee sales performance across multiple dimensions.

---

## 📊 Analysis Dimensions
This dashboard provides insights into:

- **Sales Over Time** - Monthly and yearly sales trends
- **Product Preferences** - Coffee type (roast type) and size analysis
- **Top Customers** - Identify highest spending customers
- **Sales By Country** - Geographical sales breakdown
- **Impact of Loyalty Cards** - Comparing loyal customers vs. others

---

## 📑 Data Structure

- **Orders Sheet:** Main sales table (central fact table) enriched with data from other sheets
- **Total Sales Sheet:** Aggregated view of total sales for quick reference
- **Products Sheet:** Product catalog including coffee type, size, and roast
- **Customers Sheet:** Customer data, including country and loyalty card information

---

## 🧹 Data Cleaning & Preparation
### Key Steps Performed
- Merged data from **Products** and **Customers** sheets into **Orders** using `VLOOKUP`
- Created **calculated columns** like `Order Month`, `Order Year`
- Removed duplicates and handled missing data
- Standardized date, numeric, and text formats for consistency
- Applied **conditional formatting** to highlight key metrics

---

## 💡 Key Insights

### 1️⃣ Sales Trends
- Seasonal peaks visible in **December** and **February**.
- Different coffee types (Arabica, Excelsa, Liberica) show different sales cycles.

### 2️⃣ Country-Wise Sales
- **United States** leads in sales, followed by **Ireland** and **United Kingdom**.

### 3️⃣ Top 5 Customers
- **Allis Wilmore** is the biggest buyer.
- Loyalty program targeting top buyers can boost retention.

### 4️⃣ Product Preferences
- Most popular sizes: **0.5 kg** and **1.0 kg**.
- Preferences differ by country and customer type.

### 5️⃣ Loyalty Card Impact
- Comparison of loyalty card holders vs non-holders reveals customer behavior differences.

---

## ⚒️ Tools & Techniques Used

| Technique/Feature  | Usage |
|-------------------|--------------------|
| **VLOOKUP**       | Combined data across sheets |
| **Pivot Tables**  | Built dynamic reports |
| **Pivot Charts**  | Created visual insights |
| **Slicers**       | Added interactive filters |
| **Formulas (IF, TEXT)** | Created derived columns |
| **Conditional Formatting** | Highlighted key patterns |
| **Data Cleaning Tools** | Removed duplicates, fixed dates, handled blanks |

---

