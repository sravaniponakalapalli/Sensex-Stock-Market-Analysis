# Sensex Market Performance & Risk Analysis Dashboard
## Project Overview
This project presents an interactive Power BI dashboard analyzing 30+ years of Sensex market data to evaluate market performance, risk, volatility, drawdowns, and crash behavior.
The dashboard is designed to support long-term investors, analysts, and risk managers by combining return metrics with downside risk visualization.
## Objectives
- Analyze long-term wealth creation in the Sensex
- Identify major market drawdowns and crash periods
- Visualize volatility clustering during crises
- Measure downside risk using professional financial metrics
- Enable interactive exploration across multiple time horizons
## Dataset
Source: Historical Sensex data
Time Period: ~1997 – Present
Granularity: Daily

Fields Used:

Date - The trading day for which data is recorded

Open - The first traded price of the index when the market opened

High - The highest price of the index reached during the trading day

## Key Performance Indicators (KPIs)

CAGR – Long-term annualized return

Maximum Drawdown – Worst peak-to-trough decline

Worst Daily Return – Extreme downside risk

Total Crash Days – Frequency of large negative moves

## Dashboard Features
### Market Drawdown Over Time
![Market Drawdown Over Time](https://github.com/sravaniponakalapalli/images/blob/main/SA1.png)

- Visualizes peak-to-trough declines

- Highlights bear markets using a –20% crash zone

- Identifies severity and duration of historical crashes

### Closing Price with Daily Crash Events
![Closing Price with Daily Crash Events](https://github.com/sravaniponakalapalli/images/blob/main/SA5.png)

- Plots Sensex closing price

- Highlights extreme negative return days

- Reveals clustering of crash events during crises

### Market Close vs Historical Peak
![Market Close Vs Historical Peak](https://github.com/sravaniponakalapalli/images/blob/main/SA2.png)
- Compares current price to cumulative historical highs

- Shows recovery periods after major downturns

- Illustrates market resilience

### Normalized Index (Rebased to 100)
![Normalized Index](https://github.com/sravaniponakalapalli/images/blob/main/SA3.png)
- Normalizes Sensex value to a base of 100

- Visualizes long-term compounded growth

- Removes scale bias for clearer trend interpretation

### Trading Volume vs Closing Price
![Trading Volume vs Closing Price](https://github.com/sravaniponakalapalli/images/blob/main/SA4.png)

- Combines volume histogram with price line

- Analyzes market participation

- Detects panic selling and accumulation phases

### OHLC Candlestick Chart
![OHLC Candlestick Chart](https://github.com/sravaniponakalapalli/images/blob/main/SA6.png)
- Displays daily price action

- Useful for short-term market behavior analysis

- Highlights volatility and trend reversals

### Volatility Heatmap
![](https://github.com/sravaniponakalapalli/images/blob/main/SA7.png)
- Monthly volatility aggregated by year and month

- Crisis periods (2008, 2020) stand out visually

- Efficient detection of risk regimes
### Tools & Technologies
- Power BI
- DAX
- Financial time-series analysis
- Data visualization & dashboard design
### Conclusion
This dashboard provides a comprehensive view of Sensex performance by combining returns, risk, drawdowns, and volatility. It highlights that while long-term wealth creation is strong, market crashes and high-volatility periods are integral to equity investing. The project demonstrates how Power BI can be used effectively for financial time-series analysis to deliver clear, interactive, and decision-ready insights.
