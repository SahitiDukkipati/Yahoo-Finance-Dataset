# 📈 Stock Market Analysis & Dashboard



End-to-end stock market analysis project covering data cleaning, exploratory analysis, and an interactive Power BI and Tableau dashboard with DAX measures — built on the Massive Yahoo Finance Dataset (AAPL, MSFT, GOOGL, AMZN, NVDA).

---

## 📁 Project structure
```
stock-market-analysis/
├── data/
│   ├──Massive Yahoo Finance Dataset/ ← original Kaggle dataset
│   
|--Data cleaning/
|   └── Finance_dataset.ipynb

├── screenshots/
│   └── dashboard_preview.png
|   └── dashboard_preview_1.png
└── README.md
```

---

## 🔧 Data cleaning
- Removed null values and duplicate rows
- Standardised date formats for time intelligence
- Filtered top companies by average closing price
- Engineered Daily_Return and Volatility columns

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

## 🗂️ Dataset
**Source:** [Massive Yahoo Finance Dataset](https://www.kaggle.com/datasets/iveeaten3223times/massive-yahoo-finance-dataset) on Kaggle  
**Columns:** Date, Open, High, Low, Close, Volume, Dividends, Stock Splits, Company, Daily_Return, Volatility

---

## 🛠️ Tools used
| Tool | Purpose |
|---|---|
| VS Code | Date cleaning& Analysis |
| Power BI Desktop | Dashboard & visualizations |
| Power Query | Data cleaning & transformation |
| DAX |
| Excel / CSV | Raw data handling |

Dashboard: ![Dashboard Preview](https://github.com/SahitiDukkipati/Yahoo-Finance-Dataset/blob/d357dcc7a5dc789dabf0f7b1dab45b1ae81c5f91/dashboard_preview.png)
