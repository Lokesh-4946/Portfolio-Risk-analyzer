Portfolio Risk Analyzer

Overview

Python-based tool that helps investors analyze their portfolio's risk metrics, optimize asset allocation, and assess market sentiment. The tool integrates financial data from Yahoo Finance and news sentiment analysis to provide insights into stock risk, volatility, and liquidity.

Features

 - Portfolio Risk Metrics: Computes volatility, Sharpe ratio, Sortino ratio, Value-at-Risk (VaR), Conditional VaR (CVaR), and maximum drawdown.

 - Beta Calculation: Measures each stock's beta relative to the S&P 500 index.

 - Portfolio Optimization: Uses mean-variance optimization to determine optimal asset allocation.

 - Stress Testing: Simulates portfolio performance under adverse market conditions.

 - Sentiment Analysis: Uses the NewsAPI and TextBlob to evaluate news sentiment for each stock.

 - Liquidity Risk Assessment: Evaluates stock liquidity based on average trading volume.

 - Tax-Loss Harvesting: Identifies potential tax-saving opportunities by recognizing underperforming stocks.



* Ensure you have a valid NewsAPI key and replace api_key in the script.

* Place your portfolio data in a CSV file (Portfolio.csv) with at least a Ticker


- Input CSV Format
Ensure your CSV file follows this format:
Ticker	Shares	Price
AAPL	50	145.3
MSFT	30	299.6
TSLA	10	950

Output

The script provides:
- Portfolio risk metrics (volatility, Sharpe ratio, max drawdown, etc.).
- Beta values for each stock.
- Stress test results.
- Risk mitigation suggestions.
- Optimal asset allocation weights.
- News sentiment and liquidity risk analysis.
- Tax-loss harvesting candidates.
