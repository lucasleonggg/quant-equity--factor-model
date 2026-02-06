# Quant Equity Factor Model

Multi-factor equity return model built in Python.

## Factors
- Value (Earnings-to-Price)
- Momentum (12-month return, skip last month)
- Volatility (rolling annualised)

## Data Handling
- Time-aligned factor construction
- Missing data control
- Mean imputation using SimpleImputer
- Cross-sectional standardisation

## Methodology
1. Download equity price data
2. Clean and align time series
3. Construct factor exposures
4. Impute missing values
5. Estimate factor premiums via OLS
6. Predict expected returns
7. Rank assets into a portfolio

## Tech Stack
- Python
- pandas
- numpy
- statsmodels
- scikit-learn
- yfinance

## Disclaimer
Educational project only. Not financial advice.
