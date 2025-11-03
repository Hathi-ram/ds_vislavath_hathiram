# Data Science Assignment - Web3 Trading Team

**Candidate Name:** Vislavath Hathiram  
**Platform:** Jupyter Notebook  
**Dataset Source:** Web3 Trading Team Assignment  

---

##  Project Overview
This project analyzes how trader behavior (profitability, risk, leverage, and volume) aligns with overall **market sentiment (Fear vs Greed)** in Bitcoin trading.

Two datasets were used:
1. **Historical Trader Data (Hyperliquid)**
2. **Bitcoin Market Sentiment (Fear & Greed Index)**

The goal is to understand how trading behavior changes under different market emotions and to identify any consistent trends that could influence smarter trading strategies.

---

## Steps Performed
1. **Data Loading:** Imported both datasets into Python using Pandas.  
2. **Data Cleaning:** Handled missing values, converted timestamps, and standardized column names.  
3. **Data Merging:** Combined sentiment data and trading data on date.  
4. **Feature Engineering:** Calculated PnL, win rate, trade size (USD), and categorized market sentiment.  
5. **Descriptive Statistics:** Summary tables and mean, median, and t-tests.  
6. **Visualizations:** Created 8 meaningful graphs to show the relationship between trading performance and sentiment.  
7. **Insights:** Analyzed how sentiment affects trader performance and risk-taking behavior.  

---

## Visualizations Included
1. Average Daily PnL: Fear vs Greed  
2. Daily Average PnL Over Time  
3. Average Profit by Sentiment  
4. Total Trading Volume by Sentiment  
5. Profit Trend Over Time  
6. Distribution of Profit (Histogram)  
7. Win Rate by Sentiment  
8. Correlation Heatmap  

All images are saved inside the **outputs/** folder.

---

## 📁 Folder Structure -Downloads/ds_Vislavath_Hathiram
ds_vislavath_hathiram/
├── notebook_1.ipynb
├── csv_files/
│ ├── historical_data.csv
│ ├── fear_greed_index.csv
│ ├── merged_trading_sentiment.csv
│ └── daily_summary.csv
├── outputs/
│ ├── 1_avg_daily_pnl_fear_vs_greed.png
│ ├── 2_daily_avg_pnl_over_time.png
│ ├── 3_avg_profit_by_sentiment_bar.png
│ ├── 4_total_trading_volume_pie.png
│ ├── 5_profit_trend_over_time.png
│ ├── 6_distribution_of_profit_hist.png
│ ├── 7_win_rate_by_sentiment_bar.png
│ └── 8_correlation_heatmap.png
├── ds_report.pdf
└── README.md

---

## Key Insights
- During **Greed**, traders tend to show higher PnL and higher trading volume.  
- **Fear** periods show lower risk-taking and lower leverage usage.  
- Correlation Heatmap shows a strong relationship between **PnL** and **Trade Volume**.  
- Emotional sentiment clearly influences trading outcomes.

---

## Tools Used
- **Python**: Pandas, NumPy, Scipy, Seaborn, Matplotlib  
- **Notebook**: Jupyter / Google Colab  
- **Visualization**: Seaborn and Matplotlib for charts  
- **PDF Report**: Exported from Notebook  

---

## Conclusion
Market sentiment plays a significant role in trader decision-making.  
Understanding emotional indicators like **Fear and Greed** can help predict market behavior and build data-driven trading strategies.
