# 📊 Stock Analysis & Forecasting AI Agent (All‑in‑One Local Version)
Overview
This Python script is a self‑contained, locally executable AI agent that retrieves financial data, analyzes company fundamentals, forecasts stock prices, and provides valuation metrics.
It integrates financial ratio analysis, Prophet time series forecasting, and traditional valuation models (DCF & DDM), with the option to generate AI‑driven investment opinions via the OpenAI API.

## ✨ Features
Financial Data Retrieval using yfinance

Company info, market data, dividends, balance sheet, income statement

Financial Ratio Calculations

Return on Equity (ROE)

Price‑to‑Earnings (P/E) ratio

Price Forecasting

Prophet‑based time series forecasts for customizable horizons

Valuation Models

Discounted Cash Flow (DCF)

Dividend Discount Model (DDM)

Trend & Valuation Analysis

Detect uptrend/downtrend

Identify undervaluation or overvaluation

AI‑Generated Investment Opinions (optional)

Uses OpenAI API to produce concise recommendations

## 📂 Project Structure

Since this is an all‑in‑one version, everything is inside a single Python file:

stock_agent.py   # Complete tool: data fetch, analysis, forecasting, valuation, AI opinion

## 📦 Installation
Clone this repository

git clone https://github.com/yourusername/stock-analysis-agent.git
cd stock-analysis-agent
Install dependencies

pip install yfinance prophet openai pandas
Set your OpenAI API key (optional, for AI opinions)


export OPENAI_API_KEY="your_api_key_here"   # macOS/Linux
setx OPENAI_API_KEY "your_api_key_here"     # Windows
🚀 Usage
Run the script and follow prompts:

python stock_agent.py
Example:

java
Copy
Edit
Enter stock symbol (e.g., AAPL): AAPL
Days to predict: 30

## 📊 Output Example
Company Summary

Recent Dividends

Last 5 days’ closing prices

Forecasted price trends

DCF & DDM valuations

AI‑generated investment opinion (if enabled)

## 🛠 Technologies Used
Python 3.x

yfinance

Prophet

pandas

OpenAI API (optional)

⚠️ Disclaimer
This tool is for educational purposes only and does not constitute financial advice.
All investment decisions should be made with proper due diligence.
