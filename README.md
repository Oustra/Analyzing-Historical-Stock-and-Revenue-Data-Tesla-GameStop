# Analyzing Historical Stock and Revenue Data — Tesla & GameStop

This project explores the relationship between stock performance and company revenue using two popular publicly traded companies — **Tesla (TSLA)** and **GameStop (GME)**.  
It demonstrates how to gather, clean, and visualize financial data from multiple sources using Python libraries like **yfinance**, **BeautifulSoup**, and **Plotly**.

---

## 📊 Project Overview

The notebook performs the following key tasks:

1. **Extract Stock Data:**  
   Uses the `yfinance` library to download historical stock data for Tesla and GameStop.

2. **Scrape Revenue Data:**  
   Uses `requests` and `BeautifulSoup` to scrape revenue data for both companies from financial websites.

3. **Data Cleaning:**  
   Formats the scraped data into clean Pandas DataFrames suitable for analysis.

4. **Data Visualization:**  
   Uses `Plotly` to create interactive charts that compare stock price trends with revenue growth over time.

---

## 🧰 Technologies Used

- **Python 3.x**
- **pandas** – data manipulation and analysis  
- **yfinance** – to download historical stock price data  
- **BeautifulSoup (bs4)** – for scraping revenue tables  
- **html5lib**, **lxml** – HTML parsing libraries  
- **requests** – for HTTP requests during scraping  
- **plotly** – for interactive visualizations
