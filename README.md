# Stock Scraper

## Overview
This project is a Python-based web scraping tool designed to extract real-time stock market data from Yahoo Finance. It fetches key financial indicators such as current stock prices, price changes, and percentage changes for multiple stock tickers. The data is then neatly formatted and saved into CSV files for further analysis.


## Key Skills Demonstrated
- **Web Scraping & Data Extraction:** Utilizing `requests` and `BeautifulSoup` to navigate and parse complex HTML structures and extract relevant financial data.
- **Data Automation:** Implementing periodic data retrieval with Python’s `time` module to collect stock data at regular intervals.
- **Data Storage & Management:** Exporting scraped data into CSV files with timestamps for organized and time-series data analysis.
- **Error Handling & Robustness:** Handling HTTP requests and parsing exceptions to ensure smooth operation despite potential webpage changes or network issues.
- **Python Programming:** Writing clean, modular, and reusable code following best practices for maintainability.
- **Financial Data Understanding:** Extracting and interpreting stock market indicators critical for market analysis.


## Requirements
- Python 3.x
- Libraries:
  - `requests`
  - `beautifulsoup4`

    
## Features
- Scrapes real-time stock prices and changes for multiple tickers.
- Supports periodic updates with customizable intervals.
- Saves clean, timestamped CSV files.
- Handles errors gracefully.
- Easily extendable for more metrics.


## Use Cases
- **Analysts:** Monitor stock fluctuations for decisions.
- **Data Scientists:** Gather data for analysis and modeling.
- **Educators:** Teach web scraping and automation.
- **Developers:** Build on for financial apps.
- **Investors:** Track portfolio stocks efficiently.


## Example Output
Fetching stock data at 2025-09-17 21:30:02

AAPL: $173.45 USD | Change: +2.13 (+1.24%)
MSFT: $328.67 USD | Change: -1.01 (-0.31%)
GOOGL: $139.22 USD | Change: +0.89 (+0.64%)
TSLA: $258.10 USD | Change: +3.40 (+1.34%)
AMZN: $134.95 USD | Change: -0.76 (-0.56%)

Data saved to stock_data_20250917_213002.csv
