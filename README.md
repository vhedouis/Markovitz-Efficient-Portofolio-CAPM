# Markovitz-Efficient-Portofolio-CAPM

This project focuses on exploring and implementing portfolio optimization strategies using the Markowitz framework on the CAC-40 index. It is structured into three main sections:

## Mathematical Foundations
The mathematical principles behind the optimization problem are detailed in the accompanying notebook.

## Project Structure
1. Data Exploration and Estimation of the Mean Vector and Covariance Matrix of Returns:
- Visualization of stock performance across various time horizons (daily, monthly, and annual).
- Data exploration and empirical estimation of the mean vector ($\mu$) and covariance matrix ($\Omega$) for CAC-40 stock data.

2. Portfolio Optimization with a Risk-Free Asset:
- Implementation of the Markowitz optimization problem, including a risk-free asset.
- Numerical solutions to the optimization problem, plotting of the efficient frontier, and interpretation of the results.

3. Portfolio Optimization without a Risk-Free Asset (No ASR):
- Implementation of the Markowitz optimization problem, excluding a risk-free asset.
- Numerical solutions to the optimization problem, plotting of the efficient frontier, and analysis of the non-linear relationship between risk and return.

## Key Results
1. Efficient Frontier with a Risk-Free Asset:
- The efficient frontier is linear, supporting the theory that with a risk-free asset, there is a direct proportional relationship between risk and expected return.

2. Efficient Frontier without a Risk-Free Asset:
- The efficient frontier forms a semi-parabola, reflecting the non-linear trade-off between risk and return in the absence of a risk-free asset.
- The absence of feasible solutions at low-risk levels demonstrates the intrinsic risk constraints of the market, making extremely low-risk portfolios un attainable.

## Conclusion
This project successfully applies Markowitz portfolio optimization theory to the CAC-40 index, offering insights into portfolio optimization both with and without a risk-free asset. The results align with theoretical expectations, showcasing the distinct differences in the efficient frontier when a risk-free asset is included versus when it is not.


Overall, this project serves as a comprehensive guide for implementing and understanding Markowitz portfolio optimization in real-world stock markets.
