# Market Beta & Linear Regression Calculator

## Description
The Market Beta Calculator is an automated financial modeling tool built entirely within Google Sheets. Using Google Apps Script and the `GOOGLEFINANCE` API, this script eliminates repetitive data entry by instantly pulling 5-year weekly historical data for any stock and index. It dynamically calculates the market beta, covariance, and linear regression, providing immediate quantitative insights into a stock's volatility relative to the broader market.

## Features
* **Automated Data Retrieval:** Fetches 5 years of weekly closing prices for both the target stock and the benchmark index using the `GOOGLEFINANCE` API.
* **Instant Quantitative Analysis:** Automatically calculates daily returns, Covariance, Slope, and Linear Regression (`LINEST`).
* **One-Click Execution:** Formats the sheet, sets up the mathematical formulas, and auto-fills data down to 260+ rows instantly.
* **No Manual Updates Needed:** Timeframes use dynamic date functions (`TODAY() - 1825`) to ensure data is always up to date.

## Prerequisites
* A standard Google Account (to access Google Sheets).
* Basic knowledge of Google Finance ticker symbols (e.g., `NASDAQ:AAPL` for Apple, `INDEXSP:.INX` for the S&P 500).

## Setup
1. Create a new, blank Google Sheet.
2. Navigate to **Extensions > Apps Script** in the top menu.
3. Delete any existing code in the editor and paste the `market_beta_calculator.js` script from this repository.
4. Save the project and click **Run** to authorize the script for the first time.
5. Close the Apps Script editor.

## Usage
1. In your Google Sheet, trigger the macro (either via the script editor, a custom menu, or an assigned drawing/button).
2. The script will automatically format the sheet and prompt you to enter the Stock Ticker in cell `B1` and the Index Ticker in cell `B2`.
3. Once the tickers are entered, the formulas will instantly populate the 5-year weekly data and output the Beta and Linear Regression in column G.
