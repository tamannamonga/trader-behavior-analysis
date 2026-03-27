# trader-behavior-analysis
Analysis of trader performance vs market sentiment (Fear vs Greed)
# Trader Performance vs Market Sentiment Analysis

## 📌 Objective
This project analyzes how market sentiment (Fear vs Greed) impacts trader behavior and performance using Hyperliquid trading data.

---

## 📊 Methodology

- Cleaned and preprocessed both datasets
- Converted timestamps to daily level and merged datasets
- Created key metrics:
  - Daily PnL
  - Trade count
  - Average trade size
- Segmented traders into:
  - Consistent vs Inconsistent traders
  - High vs Low activity traders

---

## 🔍 Key Insights

### 1. Market Sentiment Impacts Profitability
Trader performance varies significantly with market sentiment.  
The analysis shows that average PnL is higher during **Greed periods** compared to **Fear periods**, indicating that traders benefit from bullish market conditions.

---

### 2. Traders Change Behavior Based on Sentiment
Traders adjust their behavior depending on market sentiment.  
During **Greed phases**, trade frequency and average trade size increase, indicating higher confidence and risk-taking.  
During **Fear phases**, trading becomes either cautious or erratic.

---

## 🎯 Strategy Recommendations

### 1. Adjust Risk Based on Sentiment
During **Fear periods**, traders should reduce leverage and position size to manage volatility and avoid large losses.

---

### 2. Use Momentum in Greed Markets
During **Greed periods**, traders can increase trade frequency and follow trend-based strategies to capitalize on market momentum.

---

### 3. Focus on Consistency
Focus on consistent trading strategies rather than short-term profits, as high returns are often associated with unstable and high-risk trading behavior.

---

## ⚙️ How to Run

1. Download the datasets
2. Open the notebook `analysis.ipynb`
3. Run all cells step-by-step

---

## 📁 Files Included

- `analysis.ipynb` → Full analysis notebook
- `README.md` → Project overview and insights
