# FinScope AI
An AI-powered stock market analysis and insight generation platform.

##  Overview
FinScope AI is a Python-based system that analyzes real-time stock data, detects trends, evaluates risk, and explains market movements using financial data and news.

## Features

* Fetches real-time stock data using Yahoo Finance
* Displays price trends with graphs
* Calculates moving averages for trend analysis
* Detects trend (Uptrend / Downtrend / Sideways)
* Computes percentage change over time
* Measures volatility (risk level classification)
* Fetches relevant financial news
* Generates AI-style explanations for stock movement

---

## Flow of Code
1. User inputs stock symbol (e.g., `TCS.NS`)
2. System retrieves historical price data
3. Performs analysis:
   * Trend detection
   * Volatility calculation
   * Percentage change
4. Fetches related financial news
5. Generates insights and explanation
6. Visualizes stock performance


## 🛠️ Tech Stack
* Python
* yfinance
* matplotlib
* NewsAPI
* python-dotenv

## 🔐 Environment Setup

Create a `.env` file in the root directory:

NEWS_API_KEY=your_api_key_here

Install dependencies:

pip install yfinance matplotlib newsapi-python python-dotenv


## ▶️ Usage

Run the program: python main.py

Enter stock symbol: TCS.NS (Sample input)

## 📈 Example Output

* Stock summary (price, high, low)
* Trend detection
* Volatility classification
* Insight statement
* Relevant news headlines
* Price + Moving Average graph

## 🔮 Future Improvements

* Sentiment analysis using NLP
* AI-based explanation generation
* Web-based dashboard
* Portfolio analysis


## Project Status
✔ Version 1 — Data fetching & visualization
✔ Version 2 — Analysis (trend, volatility, insights)
✔ Version 3 — News integration + explanation

## 👩‍💻 Author
Sahithi Singh
