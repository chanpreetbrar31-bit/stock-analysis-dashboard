# Stock Analysis Dashboard

A comprehensive stock analysis dashboard that tests stocks across multiple indicators:
- **Fundamentals**: P/E Ratio, ROE, ROA, Debt-to-Equity, Dividend Yield, EPS Growth
- **Technical Indicators**: RSI, MACD, Bollinger Bands, Moving Averages, ATR, Stochastic Oscillator
- **Sentiment Analysis**: News sentiment, Social media sentiment
- **Valuation Metrics**: PEG Ratio, Free Cash Flow, Book Value

## Features

- Real-time stock data fetching
- Multi-indicator analysis
- Interactive dashboard visualization
- Stock screening and comparison
- Technical analysis charts
- Fundamental analysis reports
- Alert system for trading signals

## Project Structure

```
stock-analysis-dashboard/
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── config.py
│   ├── routes/
│   └── templates/
├── data/
│   ├── fetchers.py
│   ├── processors.py
│   └── storage.py
├── analysis/
│   ├── fundamentals.py
│   ├── technicals.py
│   ├── sentiment.py
│   └── screening.py
├── indicators/
│   ├── technical_indicators.py
│   ├── fundamental_ratios.py
│   └── valuation_metrics.py
├── visualizations/
│   ├── charts.py
│   └── dashboards.py
├── tests/
│   ├── test_indicators.py
│   ├── test_analysis.py
│   └── test_fetchers.py
├── requirements.txt
└── config.yaml
```

## Installation

```bash
git clone https://github.com/chanpreetbrar31-bit/stock-analysis-dashboard.git
cd stock-analysis-dashboard
pip install -r requirements.txt
```

## Usage

```bash
python app/main.py
```

Then navigate to `http://localhost:5000` in your browser.

## API Integrations

- **yfinance**: Stock price data and financials
- **Alpha Vantage**: Technical indicators and time series data
- **NewsAPI**: News sentiment analysis
- **Finnhub**: Company fundamentals

## License

MIT License
