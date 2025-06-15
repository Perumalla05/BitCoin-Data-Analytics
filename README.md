

```markdown
# 📊 Bitcoin Price Analysis Dashboard with Tableau

Welcome to the **Bitcoin Price Analysis Dashboard** — an interactive Tableau project that uncovers trends and insights from historical Bitcoin data 📈. This project visualizes daily, monthly, and yearly patterns in Bitcoin prices, volume, and volatility using a clean, well-structured Tableau dashboard.

---

## 🗂️ Project Contents

```

📁 Bitcoin-Price-Tableau
├── Bitcoin\_Cleaned.csv         # Cleaned and preprocessed dataset
├── Bitcoin\_Dashboard.twbx      # Tableau Workbook file
├── dashboard\_preview\.png       # Screenshot of final dashboard
└── README.md                   # This README file

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

| Sheet | Visualization | Rows | Columns | Chart Type | Purpose |
|-------|----------------|------|---------|-------------|---------|
| 1. Latest Price | Price (Latest) | - | - | KPI | Shows most recent BTC price |
| 2. % Change Today | Daily % Change | - | - | KPI | Daily performance tracker |
| 3. Volume (Latest) | Vol. | - | - | KPI | Latest market volume |
| 4. Daily Price Trend | Date | Price | Line | Shows overall trend over time |
| 5. Monthly Avg Price | Month(Date) | AVG(Price) | Bar | Monthly price comparison |
| 6. Yearly High-Low | Year(Date) | High, Low | Bar | Yearly volatility |
| 7. Volume Distribution | Month/Year | Volume | Pie | Market share by time |
| 8. Avg Daily % Change | Month(Date) | AVG(Change %) | Heatmap | Shows volatility patterns |
| 9. Price Spread | Date | High - Low | Line/Area | Intraday volatility |
| 10. Price Distribution | Year | Price | Box Plot | Outliers & price distribution |



## 🧹 Data Cleaning Summary

Performed in **Python (Pandas)**:
- Removed commas from price columns
- Converted volume units (K, M, B) to numbers
- Handled missing/null values
- Converted dates into proper datetime format
- Calculated metrics like % change and spread

---

## 🔧 Tools Used

- 🐍 Python (Pandas)
- 📊 Tableau Public
- 📁 GitHub



## 📈 Key Insights

- Bitcoin shows seasonality in monthly performance
- High volatility is observed during market events
- Volume spikes often align with large price swings
- Spread between High and Low prices gives insight into risk



