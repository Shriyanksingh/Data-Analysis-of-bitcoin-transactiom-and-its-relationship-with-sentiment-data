📊 Market Sentiment Trading Analysis

This project looks at how **market sentiment** (Fear & Greed Index) affects trading results.

We use:
- `historical_data.csv` → past trades (PnL, volume, accounts, etc.)
- `fear_greed_index.csv` → market sentiment per day

We merge them and check:
- Win rate by sentiment
- Profitability by sentiment
- Trading volume by sentiment
- Account bias vs profitability

📂 Files in This Project
- `historical_data.csv` → trade history
- `fear_greed_index.csv` → daily fear/greed index
- `analysis.py` → Python code for cleaning, merging, and plotting
- `win_rate_by_market_sentiments.png` → Win rate chart
- `net_pnl_by_market_sentiments.png` → Net PnL chart
- `volume_by_market_sentiments.png` → Trading volume chart
- `Account_sentiment_bias_vs_profitability.png` → Account scatter plot
- `REPORT.md` → Simple report with findings (like explained to a 15-year-old)

🚀 How to Run
1. Install Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
Run the script:
bash
Copy code
python analysis.py
Check the generated charts and report.

📊 Key Insights
Greed = higher win rate
Fear = more total profit
Extreme fear = really bad results
Bias (buying in greed, selling in fear) doesn’t always help

🎯 Goal
The goal is to help traders see how emotions and market mood affect performance.

Shriyank Singh


