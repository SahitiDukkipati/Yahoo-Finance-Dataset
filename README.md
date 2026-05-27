# 📈 Stock Market Analysis & Dashboard



End-to-end stock market analysis project covering data cleaning, exploratory analysis, and an interactive Power BI and Tableau dashboard with DAX measures — built on the Massive Yahoo Finance Dataset (AAPL, MSFT, GOOGL, AMZN, NVDA).

---

## 📁 Project structure
```
stock-market-analysis/
├── data/
│   ├──Massive Yahoo Finance Dataset/ ← original Kaggle dataset

├── screenshots/
│   └── dashboard_Screenshot.png
|   └── dashboard_screnshoot..png
|   └── Dax Screenshot.png
└── README.md
```

## 🗂️ Dataset
**Source:** [Massive Yahoo Finance Dataset](https://www.kaggle.com/datasets/iveeaten3223times/massive-yahoo-finance-dataset) on Kaggle  
**Columns:** Date, Open, High, Low, Close, Volume, Dividends, Stock Splits, Company

---

## 🔧Data Cleaning (Power Query — Power BI)

The raw dataset was sourced from Yahoo Finance and cleaned using Power Query in Power BI before analysis.

Steps performed:
- Removed null and blank values
- Changed data types (Date, Decimal, Integer)
- Renamed columns for clarity
- Removed duplicate rows
- Filtered out irrelevant date ranges
- Extracted Date components (Year, Month) for time-based analysis

---

## 📐 DAX measures used
-  - `Avg_Close`,  `Min_Low` — basic aggregations

---

## 📊 Dashboard visuals
- Stock price trend line chart (by company & date)
- Volume comparison bar chart
- Daily return distribution
- Company performance ranking table
- Volatility heatmap

---

## 💡 Key insights
- Identified Average-volatility periods across each company yearly
-Found the average closing price of each company
- Average spread and Total trading volume
- Highest prices reached per year

---

## 🛠️ Tools used
| Tool | Purpose |
|---|---|
| VS Code | Date cleaning& Analysis |
| Power BI Desktop | Dashboard & visualizations |
| Power Query | Data cleaning & transformation |
| DAX |
| Excel / CSV | Raw data handling |

Dashboard: ![Dashboard Preview](https://github.com/SahitiDukkipati/Yahoo-Finance-Dataset/blob/9df3f38845445aaa1c22fca24d860b1f4616719d/Dashboard_Screenshot.png)
