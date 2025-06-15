

```markdown
# 📊 Bitcoin Price Analysis Dashboard with Tableau

Welcome to the **Bitcoin Price Analysis Dashboard** — an interactive Tableau project that uncovers trends and insights from historical Bitcoin data 📈. This project visualizes daily, monthly, and yearly patterns in Bitcoin prices, volume, and volatility using a clean, well-structured Tableau dashboard.

---

## 🗂️ Project Contents

📁 **Bitcoin-Price-Tableau**

```

├── Bitcoin Historical Data.csv     # Raw dataset
├── Bitcoin\_Cleaned.csv             # Cleaned dataset (Python preprocessing)
├── Bitcoin\_preprocessing.ipynb     # Python notebook for data cleaning
├── dashboard1.twb                  # Tableau Workbook (Part 1)
├── dashboard2.twb                  # Tableau Workbook (Part 2)
├── dashboard3.twb                  # Tableau Workbook (Part 3)
├── README.md                       # This README file

```

---

## 🎯 Objective

To explore and analyze historical Bitcoin data using Tableau, identify market patterns, and communicate insights through an engaging and interactive dashboard.

---

## 📌 Key Features

✅ Cleaned & transformed Bitcoin dataset (using Python)  
✅ Interactive and colorful Tableau dashboard  
✅ 10 Insightful Sheets with different types of charts  
✅ Covers price trends, volume, volatility & more  
✅ Perfect for academic or data analytics portfolio use

---

## 📊 Tableau Sheets Overview

| Sheet                    | Visualization     | Rows         | Columns         | Chart Type   | Purpose                            |
|--------------------------|-------------------|--------------|------------------|--------------|------------------------------------|
| 1. Latest Price          | Price (Latest)    | -            | -                | KPI          | Shows most recent BTC price        |
| 2. % Change Today        | Daily % Change    | -            | -                | KPI          | Daily performance tracker          |
| 3. Volume (Latest)       | Vol.              | -            | -                | KPI          | Latest market volume               |
| 4. Daily Price Trend     | Date              | Price        | Line             | Line Chart   | Shows overall trend over time      |
| 5. Monthly Avg Price     | Month(Date)       | AVG(Price)   | Bar              | Bar Chart    | Monthly price comparison           |
| 6. Yearly High-Low       | Year(Date)        | High, Low    | Bar              | Bar Chart    | Yearly volatility                  |
| 7. Volume Distribution   | Month/Year        | Volume       | Pie              | Pie Chart    | Market share by time               |
| 8. Avg Daily % Change    | Month(Date)       | AVG(Change%) | Heatmap          | Heatmap      | Shows volatility patterns          |
| 9. Price Spread          | Date              | High - Low   | Line/Area        | Area Chart   | Intraday volatility                |
| 10. Price Distribution   | Year              | Price        | Box Plot         | Box Plot     | Outliers & price distribution      |

---

## 🧹 Data Cleaning Summary

Performed in **Python (Pandas)**:
- Removed commas from price columns  
- Converted volume units (K, M, B) to numerical values  
- Handled missing/null values  
- Converted `Date` column to datetime format  
- Calculated metrics like `% Change` and `Price Spread`  

---

## 🔧 Tools Used

- 🐍 Python (Pandas)  
- 📊 Tableau Public  
- 📁 GitHub  

---

## 📈 Key Insights

- 📅 Bitcoin shows **seasonality** in monthly performance  
- ⚠️ High **volatility** is observed during major market events  
- 📊 **Volume spikes** often align with large price swings  
- 📉 The **spread** between High and Low prices reveals market risk levels  
```

