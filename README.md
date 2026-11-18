# Quantitative Market Risk Analysis

## Overview

This project explores quantitative methods used in market risk management, focusing on Monte Carlo simulation and Bootstrap techniques.

The analysis uses a diversified portfolio inspired by Ray Dalio's All Weather Portfolio to study portfolio risk and quantify potential losses.

## Methodology

The project covers:

- **Portfolio Construction:** Building a diversified portfolio using ETFs across different asset classes.
- **Monte Carlo Simulation:** Simulating correlated asset returns and portfolio performance.
- **Value at Risk (VaR):** Estimating potential portfolio losses at a 95% confidence level.
- **Expected Shortfall (ES):** Measuring average losses beyond the VaR threshold.
- **Monte Carlo Estimator Accuracy:** Analysing standard error, mean squared error (MSE), and approximate unbiasedness.
- **Bootstrap Analysis:** Estimating uncertainty around the probability of experiencing severe portfolio losses.

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- yfinance
- Jupyter Notebook

## How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install numpy pandas matplotlib yfinance jupyter
```

3. Open the notebook in Jupyter:

```bash
jupyter notebook
```

4. Run the cells sequentially.

Historical market data is retrieved through Yahoo Finance using `yfinance`.

## Author

David Sainero Valle
