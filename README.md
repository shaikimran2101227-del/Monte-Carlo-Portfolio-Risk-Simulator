# Monte Carlo Portfolio Risk Simulator

## About the Project

This project simulates 10,000 possible one-year outcomes for a portfolio containing four assets. It uses NumPy to calculate portfolio values, volatility, and 95% Value-at-Risk (VaR).

The project also includes a market-crash stress test and a comparison of different portfolio allocations.

## Technologies Used

- Python
- NumPy
- Matplotlib
- Google Colab

## Features

- Simulates 10,000 portfolio paths over 252 trading days.
- Generates daily asset returns using `np.random.normal()`.
- Calculates portfolio values using matrix multiplication, `np.log1p()`, and `np.exp()`.
- Estimates portfolio volatility and 95% VaR.
- Displays a histogram of final portfolio values and sample portfolio paths.
- Tests normal, moderate-crash (-5%), and severe-crash (-10%) scenarios.
- Generates an automatic risk report with average portfolio value, VaR, and probability of loss.
- Compares equal-weight and alternative-weight portfolios.
- Displays risk comparison graphs using Matplotlib.

## NumPy Concepts Used

`np.array()`, `np.random.seed()`, `np.random.normal()`, `np.mean()`, `np.std()`, `np.percentile()`, `np.sum()`, `np.cumsum()`, `np.log1p()`, `np.exp()`, multidimensional arrays, and matrix multiplication.

## How to Run

1. Open Google Colab.
2. Create a new Python notebook.
3. Copy each code block into a separate cell in the correct order.
4. Run all cells from top to bottom.
5. View the simulation results, reports, and graphs.

## Innovations

**Market Crash Stress Test:** Compares portfolio outcomes under normal market conditions and hypothetical moderate and severe crashes.

**Automatic Risk Report:** Displays portfolio values, estimated VaR, loss probability, and a simple risk alert for each scenario.

**Portfolio Allocation Comparison:** Compares the simulated average value and volatility of two different portfolio allocations.

## Limitations

This is an educational simulation, not a real investment forecasting tool. It uses hypothetical return assumptions, independent asset returns, and simplified market-crash scenarios. It does not fully model real-world asset correlations, transaction costs, taxes, or changing market conditions.

The results are not financial advice or guarantees of future performance.

## Conclusion

This project demonstrates how NumPy and Matplotlib can be used to simulate portfolio outcomes, estimate financial risk, and visualize uncertainty. The additional stress-testing and allocation-comparison features make it easier to explore different hypothetical market conditions.

## Author

Created as a Python, NumPy, and Matplotlib learning project.# Monte-Carlo-Portfolio-Risk-Simulator
