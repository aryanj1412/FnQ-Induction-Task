**📘 Overview:**

This task implements and evaluates a Trend-Following Trading Strategy tailored for the Indian stock market. It leverages a combination of technical indicators to maximize profitability across various market conditions.
The system is developed and tested in a Jupyter Notebook using Python, with performance metrics evaluated over multiple historical market regimes.


**⚙️ Strategy Components:**

1. Exponential Moving Average (EMA) Crossover:

Detects trend reversals.

Bullish signal: Short EMA crosses above Long EMA.

Bearish signal: Short EMA crosses below Long EMA.

2. Average Directional Index (ADX):

Filters trades to include only strong trends (ADX > 25).

Non-directional: Measures trend strength regardless of direction.

3. Sector Rotation

Enhances returns by rotating into high-performing sectors.

Reduces risk through diversification across sectors.

**📊 Backtesting:**

The strategy was tested in four different Indian market regimes using the backtesting.py library:
1. Sideways Market (Jan 2011 – Jun 2013)
2. Bull Market (Jun 2014 – Dec 2015)
3. COVID-19 Period (Jan 2020 – Dec 2021)
4. Present Scenario (Jan 2022 – Dec 2024)

**📂 Project Structure:**

├── Report.pdf

├── TradingStrategy.ipynb

├── README.md

**🛠️ Dependencies:**

Make sure you have the following installed:

1. Python 3.8+
2. backtesting.py
3. pandas
4. numpy
5. ta-lib
6. yfinance
