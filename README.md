# 📊 Trader Performance vs Market Sentiment Analysis

## 🎯 Objective

This project analyzes how market sentiment (Fear vs Greed) impacts trader behavior and performance using historical trading data. The goal is to identify patterns that can inform better trading strategies.

---

## 📂 Datasets Used

1. Bitcoin Market Sentiment Dataset (Fear/Greed classification by date)
2. Historical Trader Data (Hyperliquid trades including price, size, side, and PnL)

---

## ⚙️ Methodology

* Performed data cleaning and handled missing values
* Converted timestamps and aligned both datasets at a daily level
* Merged sentiment data with trader activity
* Created key metrics such as:

  * Profit & Loss (PnL)
  * Win rate
  * Trade size
  * Trade frequency
* Conducted sentiment-based analysis and trader segmentation

---

## 📌 Key Insights

1. Traders generate higher average PnL during Greed periods compared to Fear periods, indicating stronger performance in bullish sentiment.

2. Trade sizes increase during Greed phases, showing higher risk appetite among traders.

3. Losing traders exhibit significantly larger losses compared to gains by winning traders (~-154 vs +90), highlighting poor risk management.

4. Trading activity and position sizes tend to decrease during Fear periods, indicating cautious behavior.

---

## 💡 Strategy Recommendations

1. During Fear periods, traders should reduce position sizes and avoid aggressive trading strategies.

2. During Greed periods, traders can increase participation but must implement strict risk management (e.g., stop-loss).

3. Traders should focus on minimizing large losses, as downside risk is significantly higher than upside gains.

---

## 🛠️ Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📈 Output

All analysis, visualizations, and results are available in the notebook:
`market_sentiment_vs_trader_performance.ipynb`

---
