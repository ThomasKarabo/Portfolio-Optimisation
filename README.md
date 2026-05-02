# Portfolio Optimization Project - Johannesburg Stock Exchange (JSE)

A comprehensive **Modern Portfolio Theory (MPT)** implementation analyzing 16 major JSE-listed stocks. This project simulates thousands of random portfolios to construct the **Efficient Frontier** and identifies the **Maximum Sharpe Ratio** portfolio for optimal risk-adjusted returns.

## 🎯 Project Overview

This project applies Harry Markowitz’s Portfolio Theory to real market data (2020–2024) to:
- Calculate annualized returns and covariance matrix
- Simulate 10,000+ random portfolios
- Visualize the **Efficient Frontier**
- Identify the portfolio with the **highest Sharpe Ratio**
- Determine the **Minimum Volatility** portfolio

## 📊 Key Features

- **Data Source**: Real-time historical prices via `yfinance`
- **Stocks Analyzed**: 16 major JSE companies across Banking, Mining, Retail, Telecom, and Consumer sectors:
  - Banking: SBK, FSR, ABG, NED
  - Mining: AGL, IMP, SOL
  - Retail/Consumer: SHP, PIK, WHL, BVT, REM
  - Telecom: MTN, VOD
  - Others: NPN, PRX

- **Metrics Calculated**:
  - Annualized Returns & Volatility
  - Portfolio Risk (using full covariance matrix)
  - Sharpe Ratio (Risk-adjusted performance)

- **Optimization Techniques**:
  - Monte Carlo Simulation (10,000+ portfolios)
  - Identification of Max Sharpe & Global Minimum Variance portfolios

## 📈 Results Highlights

- **Maximum Sharpe Ratio Portfolio** achieved strong risk-adjusted returns with significant allocations to high-performing stocks like **SHP.JO (21.6%)**, **PRX.JO (15.6%)**, and **NPN.JO (15.6%)**.
- Clear visualization of the **Efficient Frontier** showing the trade-off between risk and return.
- Diversified allocation across sectors, reducing unsystematic risk.

## 🛠️ Technologies Used

- Python
- pandas, NumPy
- yfinance
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook

## 📁 Project Structure
