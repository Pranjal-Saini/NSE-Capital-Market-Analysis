# 📈 NSE Stock Market Performance & Investment Intelligence Analytics
 
A Python and Power BI-based stock market analytics project to analyze NSE-listed stocks, identify market trends, sector performance, and predict bullish or bearish momentum using machine learning.
 
---
 
## 🛠️ Tech Stack
Python · Pandas · Seaborn · Scikit-learn · Power BI · TradingView API · Jupyter Notebook
 
---
 
## 📋 What's Covered
 
| Step | Description |
|---|---|
| 🔍 Data Extraction | Scraped live NSE data via TradingView's stock screener API |
| 🧹 Data Cleaning | Handled nulls, dropped sparse columns, standardized market cap to lakhs |
| 📊 EDA & Insights | Analyzed price, P/E, RSI distributions, sector market cap, EPS growth YoY |
| 🤖 ML Model Building | Random Forest Classifier with SMOTE to predict bullish vs bearish momentum |
| 📉 Power BI Dashboard | KPI overview, market sentiment, technical analysis, and sector dashboards |
 
---
 
## 🗂️ Dataset
Live NSE stock data scraped from TradingView covering price, volume, P/E ratio, RSI, EPS TTM, EPS Growth YoY, SMA indicators, market cap, and sector classifications across 2,383 listed companies.
 
---
 
## 💡 Key Findings
- 📊 Finance sector holds the highest total market cap among all NSE sectors
- 🟢 73% of NSE stocks showed bullish momentum; Communications sector led at 93% bullish
- 🔗 Strong positive correlation (0.88) between stock price and EPS TTM
- 🤖 ML model achieved 83.4% accuracy in classifying bullish vs bearish stock behavior
- 📉 Consumer Non-Durables recorded the highest EPS Growth YoY across all sectors
---
 
## 📁 Project Structure
 
```
nse-stock-market-analysis/
│
├── Data Scraping Script.ipynb                # TradingView API scraping
├── EDA & ML File.ipynb                       # Analysis & model building
├── NSE Dashboard.pbix                        # Power BI dashboard file
└── README.md                                 # Project documentation
```
 
---
