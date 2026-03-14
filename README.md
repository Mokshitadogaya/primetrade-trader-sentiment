# primetrade-trader-sentiment
# Primetrade.ai Internship Assignment
## Trader Performance vs Market Sentiment Analysis

---

## What I Did (Methodology)

I analyzed two datasets:
1. Bitcoin Fear & Greed Index — 2,644 days of sentiment data
2. Hyperliquid Trader Data — 2,11,224 trades from 32 traders

Steps I followed:
- Loaded and cleaned both datasets (0 missing values found)
- Converted timestamps and merged both datasets by date
- Created daily metrics like PnL, win rate, trade size, long/short ratio
- Grouped traders into segments based on their win rate

---

## What I Found (Insights)

### Insight 1 — Traders are MORE active on Fear days
On Fear days traders placed 105 trades per day on average,
compared to only 77 trades on Greed days.
They also used bigger position sizes on Fear days ($7,182 vs $4,574).
This shows traders are confidently buying the dip during fear.

### Insight 2 — Fear days actually generate higher PnL
Average daily PnL on Fear days was $5,185 vs $4,144 on Greed days.
This was surprising — most people think Greed = more profit.
But here, fear-driven buying is actually more profitable.

### Insight 3 — Win rate stays the same regardless of sentiment
Fear days win rate: 35.7%
Greed days win rate: 36.3%
Almost no difference — meaning sentiment does not affect
how often you win, but it does affect how much you make per trade.

---

## My Strategy Recommendations

### Strategy 1 — Buy more during Fear
When the Fear & Greed index shows Fear (below 30),
traders should consider increasing their position size slightly.
The data shows this is already working for profitable traders.

### Strategy 2 — Take profits during Greed
When the index shows Greed (above 60),
focus on closing existing positions rather than opening new ones.
Some coins like @107 perform extremely well on Greed days,
so momentum trades can be taken on those specific coins.

---

## Charts Made
1. PnL Performance — Fear vs Greed vs Neutral
2. Trader Behavior Analysis
3. Trader Segmentation
4. Coin Performance by Sentiment
5. Final Summary Dashboard

---

## How to Run

1. Install libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn

2. Place data files in same folder:
   - fear_greed_index.csv
   - hyperliquid_trades.csv

3. Open and run notebook.ipynb top to bottom

---

Submitted by: Mokshita Dogaya
