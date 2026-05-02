# Portfolio Optimization + PCA Analysis - JSE Equities

**Modern Portfolio Theory (MPT) + Principal Component Analysis** on 16 major Johannesburg Stock Exchange stocks (2020–2024).

## 🎯 Project Overview

This project combines classical **Portfolio Optimization** with **PCA** to:
- Build and visualize the **Efficient Frontier** using Monte Carlo simulation
- Identify the **Maximum Sharpe Ratio** and **Minimum Volatility** portfolios
- Use **PCA** to uncover the underlying risk factors driving the portfolio

## 📊 Key Features

### 1. Portfolio Optimization
- Downloaded historical price data via `yfinance`
- Computed annualized returns and covariance matrix
- Simulated 10,000+ random portfolios
- Identified optimal allocations (e.g. strong weights in SHP.JO, PRX.JO, NPN.JO)

### 2. Principal Component Analysis (PCA)
- Applied PCA on daily returns to identify **latent risk factors**
- Analyzed **explained variance** to determine how many components capture most market risk
- Examined **component loadings** to understand which stocks drive each factor (e.g. Banking factor, Mining factor, Market factor)
- Visualized cumulative explained variance and top feature contributions

## 🔍 PCA Insights

- The first 3–5 principal components typically explain **70–85%** of total variance in the JSE dataset.
- Clear sector clustering visible in loadings (Banking stocks load together, Mining stocks on another component, etc.).
- Demonstrates the effectiveness of dimensionality reduction while retaining most portfolio risk information.

## 🛠️ Technologies Used

- Python, pandas, NumPy, yfinance
- scikit-learn (`PCA`)
- Matplotlib / Seaborn

## 📌 Key Learnings & Skills Demonstrated

- Modern Portfolio Theory & Efficient Frontier construction
- Risk management using full covariance matrix
- **Dimensionality reduction** and latent factor discovery with PCA
- Interpretation of financial data through statistical methods
- Python proficiency for quantitative finance
