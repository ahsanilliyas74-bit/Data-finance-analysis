# Automated Stock Portfolio Tracker
A Python project that automatically fetches live stock data and generates a portfolio report.

## Features
- Downloads latest prices using **yfinance** (free Yahoo Finance data)
- Calculates total profit/loss and allocation
- Visualizes portfolio composition and historical performance
- Fully self-updating: re-run the notebook anytime for fresh results

## Sample Output
![Portfolio Allocation](portfolio_pie.png)

![Historical Growth](historical_growth.png)

## How to Use
1. Open `portfolio_analysis.ipynb` in [Google Colab](https://colab.research.google.com) or any Jupyter environment.
2. Run all cells. The notebook will automatically install dependencies and fetch today's data.
3. Customize the `portfolio` dictionary with your own stocks.

## Tools & Libraries
- Python 3
- yfinance
- pandas, matplotlib
- Jupyter Notebook

## Data Source
- Yahoo Finance via `yfinance` (free for non-commercial use)

## Future Improvements
- Add benchmark comparison (S&P 500)
- Automate daily email delivery of the report
- Deploy as an interactive Streamlit web app
