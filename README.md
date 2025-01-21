# Portfolio_Management_Project

This project demonstrates how to manage an investment portfolio by analyzing and optimizing asset allocations across different indices. Using Python, the project explores financial metrics, such as annualized returns, volatility, and the Sharpe ratio, to identify the optimal Tangent Portfolio.

---

## **Project Objective**

The main objective is to analyze a portfolio comprising the following indices:
- **`^RUT`**: Russell 2000
- **`^IXIC`**: NASDAQ Composite
- **`^GSPC`**: S&P 500
- **`XWD.TO`**: iShares MSCI World Index ETF

### Tasks:
1. Calculate the **allocation of the Tangent Portfolio**.
2. Compute the **annualized volatilities** and **returns** of the four assets and the Tangent Portfolio.
3. Determine the **Sharpe ratio** of the four assets and the Tangent Portfolio.

---

## **Key Features**
1. **Data Collection**:
   - Fetch historical data for the specified indices using the `yfinance` library.
2. **Portfolio Analysis**:
   - Calculate annualized returns and volatilities for individual assets.
   - Evaluate the covariance matrix to assess asset relationships.
3. **Portfolio Optimization**:
   - Find the Tangent Portfolio by maximizing the Sharpe ratio.
---

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - `yfinance`: For retrieving historical stock/index data.
  - `pandas` and `numpy`: For data manipulation and numerical computations.

---

## **Results**
- **Optimal Tangent Portfolio**:
  - Allocation of weights to maximize the Sharpe ratio.
- **Performance Metrics**:
  - Annualized returns, volatilities, and Sharpe ratios for individual assets and the Tangent Portfolio.
- **Efficient Frontier**:
  - Visualization of the portfolio optimization process with the Tangent Portfolio highlighted.
