# Volatility Forecasting Using GARCH Model[^1^][1]

## Objective
Forecasting volatility in asset returns using the GARCH (Generalized Autoregressive Conditional Heteroskedasticity) model[^1^][1].

## Data
- Historical stock prices of S&P 500 from 2010-01-01 to 2023-01-01.

## Methodology
- Calculated daily returns from stock prices.
- Visualized returns and checked for volatility clustering.
- Implemented GARCH(1, 1) model for volatility forecasting.
- Backtested model using rolling window approach.

## Results
- RMSE of GARCH(1, 1): 0.0058
- Value at Risk (95% confidence): 0.0205

## Files
- `volatility_forecasting_garch.ipynb`: Jupyter notebook with code and analysis.
- `data/`: Folder containing the dataset.
- `images/`: Folder containing plots and visualizations.

## Dependencies
- Python 3.x
- pandas, numpy, matplotlib, seaborn, yfinance, arch, sklearn, scipy, statsmodels

## Usage
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook.
