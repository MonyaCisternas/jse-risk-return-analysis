# JSE Stock Risk & Return Analysis
This project analyses the risk and return characteristics of selected Johannesburg Stock Exchange (JSE) equities using Python. The goal is to evaluate asset performance using common financial metrics and visualize relationships between different stocks.
The analysis focuses on measuring volatility, correlations, and risk-adjusted returns to better understand how different equities perform relative to their level of risk.

## Project Objectives
- Calculate daily stock returns from historical price data
- Measure volatility and risk characteristics of each asset
- Compare risk vs return across multiple JSE stocks
- Analyse correlations between equities to understand diversification opportunities
- Visualize key financial metrics using Python

## Financial Metrics Calculated 
The following financial metrics were used in the analysis:
- Daily Returns – Percentage change in stock prices over time
- Annualized Volatility – Measure of asset risk based on return variability
- Sharpe Ratio – Risk-adjusted return metric comparing excess return relative to      volatility
- Correlation Matrix – Relationship between asset price movements
- Risk vs Return Comparison – Scatter plot illustrating portfolio positioning

## Technologies Used
- Python
- Pandas for data manipulation and analysis
- NumPy for numerical computations
- Matplotlib/Seaborn for data visualization
- Jupyter Notebook for interactive financial analysis

## Project Structure
jse-risk-return-analysis

─ data
   jse_stock_data.csv

─ notebooks
   jse_risk_return_analysis.ipynb

─ visuals
   volatility_chart.png
   correlation_matrix.png
   risk_return_scatter.png

─ README.md
  requirements.txt

## Example Visualizations
The analysis produces several visualizations that help interpret the financial data, including:
- Risk vs Return Scatter Plot comparing stock performance
- Correlation Heatmap illustrating relationships between equities
- Volatility Analysis highlighting differences in asset risk

These visualizations help identify higher-risk, higher-return assets and diversification opportunities within the portfolio.

## Key Insights
- Stocks with higher volatility tend to offer greater potential returns but increased risk.
- Correlation analysis highlights diversification opportunities between assets.
- Risk-adjusted metrics such as the Sharpe Ratio provide deeper insight than returns alone.

## Future Improvements
Potential extensions for this project include:
- Portfolio optimization using Modern Portfolio Theory
- Monte Carlo simulations for portfolio forecasting
- Integration of additional financial indicators
- Building an interactive dashboard for portfolio analysis

## Author
Monya Cisternas
Finance Data Science/Analytics
