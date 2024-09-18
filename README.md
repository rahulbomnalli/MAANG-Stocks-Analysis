# MAANG Stock Analysis

This project analyzes the performance of the MAANG (Meta, Apple, Amazon, Netflix, Google) stocks over a given period. The analysis includes visualizations of stock data, returns, market capitalization, volatility, and correlation, providing insights into the stock market behavior of these major tech companies.

## Features

- **Stock Data Fetching**: Retrieves historical stock data for MAANG stocks using the `yfinance` library.
- **Visualizations**:
  - Market Capitalization Pie Chart
  - Daily Returns Line Chart
  - Cumulative Returns Plot
  - Volatility Bar Plot
  - Correlation Heatmap
  - Scatter Matrix Plot for Daily Returns
  - Bubble Chart for Market Cap vs Mean Daily Returns
  - Stock Ranking based on Cumulative Returns
- **Analysis**: 
  - Stock volatility and correlation are examined to understand risk and market dynamics.
  - A detailed comparison of each stock's market cap and return performance.

## Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`
- `yfinance`

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/rahulbomnalli/MAANG-Stocks-Analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter notebook to fetch and analyze MAANG stock data:
   ```bash
   jupyter notebook MAANG_Stock_Analysis.ipynb
   ```
2. Customize the start and end dates for data analysis by modifying the variables in the notebook:
   ```python
   start_date = '2022-01-01'
   end_date = '2023-11-01'
   ```

## Results

The analysis provides comprehensive insights into the performance of MAANG stocks. Each stock is compared based on its market cap, daily returns, cumulative returns, and volatility. Visualizations make it easier to identify trends, correlations, and the overall market dynamics of these tech giants.

## License

This project is licensed under the MIT License.
