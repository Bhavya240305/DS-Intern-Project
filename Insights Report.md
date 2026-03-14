# Trader Behavior vs Market Sentiment

## Methodology

This project analyzes the relationship between Bitcoin market sentiment and trader behavior on the Hyperliquid trading platform.

Two datasets were used:
1. Bitcoin Fear & Greed Index
2. Hyperliquid historical trading data

The datasets were merged using daily timestamps to align trader activity with market sentiment conditions. Several behavioral and performance metrics were then computed, including:

- Daily trader PnL
- Win rate
- Trade frequency
- Trade size distribution
- Risk (PnL volatility)

Visualization techniques were used to analyze the relationship between sentiment and trader performance. Additional segmentation was performed to classify traders into groups such as frequent vs infrequent traders and profitable vs unprofitable traders.

---

## Key Insights

1. **Trading activity increases during Fear sentiment periods.**  
The analysis shows that Fear sentiment days have the highest number of trades, indicating that traders become more active during periods of market uncertainty and volatility.

2. **Trader profitability is highly concentrated.**  
A small number of traders generate a disproportionately large share of the total profits. This suggests that trading success is concentrated among a limited group of skilled or algorithmic traders.

3. **Fear sentiment leads to higher volatility in trader performance.**  
During Fear periods, traders experience both extreme profits and extreme losses, indicating greater market uncertainty.

4. **Trade size distribution is highly skewed.**  
Most trades are small in size, while a small number of very large trades dominate overall market exposure.

5. **Higher risk does not necessarily lead to higher returns.**  
The risk vs return analysis shows that traders with moderate risk exposure often achieve more consistent profitability compared to high-risk traders.

---

## Strategy Recommendations

1. **Reduce position size during Fear sentiment periods.**  
Higher volatility during Fear markets increases risk exposure. Traders should use smaller position sizes and tighter risk controls during these periods.

2. **Focus on consistent strategies rather than high-risk trading.**  
The risk vs return analysis suggests that traders with balanced risk exposure achieve more stable performance than those taking excessive risk.

3. **Monitor sentiment signals to adjust trading behavior.**  
Sentiment indicators can provide useful signals about market conditions, allowing traders to adapt position sizes and strategies accordingly.

---

## Conclusion

Market sentiment plays a significant role in shaping trader behavior and performance. Fear sentiment periods lead to increased trading activity and higher volatility, while Greed sentiment periods show relatively more stable outcomes. Understanding these behavioral patterns can help traders develop more adaptive and risk-aware trading strategies.
