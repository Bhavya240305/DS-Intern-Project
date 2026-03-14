# DS-Intern-Project
# Trader Behavior vs Market Sentiment Analysis

## Overview
This project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on the Hyperliquid platform. The goal is to uncover patterns in trading activity, profitability, and risk-taking behavior based on market sentiment.

The analysis combines two datasets:
1. Bitcoin Fear & Greed Index
2. Hyperliquid historical trader data

By merging these datasets at a daily level, we examine how trader performance and behavior change under different sentiment conditions.

---

## Project Structure
trader-sentiment-analysis
│
├── data
│ ├── fear_greed_index.csv
│ └── historical_data.csv
│
├── notebook
│ └── trader_sentiment_analysis.ipynb
│
├── charts
│ ├── trades_per_day.png
│ ├── pnl_vs_sentiment.png
│ ├── trade_size_by_sentiment.png
│ ├── trader_leaderboard.png
│ ├── risk_vs_return.png
│ ├── sentiment_heatmap.png
│ └── long_vs_short.png
│
├── outputs
│ ├── trader_segments.csv
│ └── daily_trader_pnl.csv
│
└── README.md


---

## Installation

Install required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn


## How to Run

1. Clone the repository

git clone https://github.com/yourusername/trader-sentiment-analysis.git

2. Navigate to the project directory

cd trader-sentiment-analysis

3. Open the notebook

jupyter notebook

4. Run the notebook:

notebook/trader_sentiment_analysis.ipynb
