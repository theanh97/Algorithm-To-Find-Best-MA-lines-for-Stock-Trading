# Stock Analysis with Simple Moving Average (SMA) Backtest

This project implements a stock analysis tool that downloads historical stock data, performs a Simple Moving Average (SMA) backtest, and visualizes the results. It's designed to help traders and analysts identify potentially profitable trading strategies based on SMA crossovers.

## Features

- Download historical stock data from Yahoo Finance
- Calculate and plot Simple Moving Averages (SMA)
- Perform SMA backtest with customizable parameters
- Visualize stock prices and SMA
- Statistical analysis of backtesting results

## Requirements

- Python 3.x
- yfinance
- pandas
- numpy
- matplotlib
- scipy

## Installation

1. Clone this repository
2. Install the required packages using pip

## Usage

1. Import the required libraries and functions from the script.
2. Use the `download_historical_data` function to fetch stock data.
3. Perform the SMA backtest using the `perform_sma_backtest` function.
4. Analyze the results and visualize the best SMA strategy.

Detailed usage instructions and examples can be found in the project documentation.

## Example Output

The script will output the best SMA length based on the highest training forward return, along with the following information:

- Training forward return
- Test forward return
- P-value of the statistical test

It will also generate plots showing the stock's closing price and the best SMA.

## Customization

You can customize the following parameters:

- Stock symbol
- Date range for analysis
- Number of forward days for return calculation
- SMA range for backtesting
- Train-test split ratio

## Disclaimer

This tool is for educational and research purposes only. It is not financial advice, and should not be used as the sole basis for making investment decisions. Always consult with a qualified financial advisor and do your own research before making any investment.

## License

[MIT License](LICENSE)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
