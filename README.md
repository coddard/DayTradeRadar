<img src="logo.png" alt="Logo" style="width:50%;">

# DayTradeRadar

DayTradeRadar is a fast, intuitive stock scanner designed for day traders. It scans markets in real-time to identify high-potential stocks for intraday trading, delivering clear, actionable advice on which stocks are "hot" for trades based on momentum, volume, and key technical signals.


A robust, modular stock scanner and backtesting platform for day trading and swing trading. It fetches live data (Yahoo Finance, Alpaca, Polygon), applies technical and fundamental filters, detects key patterns (like engulfing candles), and outputs actionable stock picks with detailed analytics.

## Features
- **Live Data Integration:** Fetches real-time data for NASDAQ 100 stocks using Yahoo Finance (via `yfinance`).
- **Technical Analysis:** Calculates indicators (VWAP, RSI, ATR, volume spikes, engulfing patterns, etc.).
- **Pattern Detection:** Detects bullish/bearish engulfing candles for buy/sell signals.
- **Backtesting:** Simulate strategies over historical data and analyze performance.
- **Database Support:** Saves scan results to SQLite for later review.
- **Robust Error Handling:** Handles API failures, missing data, and edge cases gracefully.
- **Modular Design:** Easily extendable for new data sources, indicators, or strategies.

## Installation

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd stock_scan_app
   ```
2. **Create a virtual environment (recommended):**
   ```sh
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

---



