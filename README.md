# Portfolio Strategy Comparison: Equal Weight vs. Risk Parity

![screenshot-localhost_8888-2025 04 05-14_51_19](https://github.com/user-attachments/assets/46fc0360-1e52-49bc-9857-0a7a4e720cf2)

### Project Overview

This project compares two portfolio construction strategies—Equal Weight (EW) and Hierarchical Risk Parity (HRP)—to evaluate their performance, risk characteristics, and diversification benefits. The analysis includes:

- Return and volatility metrics (annualized returns, Sharpe ratio)
- Risk contribution analysis (how each asset impacts portfolio risk)
- Diversification effectiveness (Diversification Ratio, Effective Number of Bets)

The goal is to help investors understand the trade-offs between simple equal-weighted allocation and more sophisticated risk-balanced approaches.

### Dataset

The dataset contains historical stock price data for a group of selected assets. This data is used to compute:

- Daily and annualized returns
- Covariance and correlation matrices
- Inputs for portfolio performance simulation

### Key Features

Portfolio Strategy Comparison
- Equal Weight (EW): Assigns identical weights to all assets.
- Risk Parity (HRP): Uses hierarchical clustering to balance risk contributions.

Performance Metrics
- Annualized returns, volatility, and Sharpe ratio.
- Visualizations of portfolio weights and risk contributions.

Diversification Analysis
- Diversification Ratio (DR): Measures how well risk is spread across assets.
- Effective Number of Bets (ENB): Quantifies the portfolio's true diversification.

Visualizations
- Bar charts comparing allocations.
- Risk contribution plots for each strategy.

## Key Findings

- Risk Parity (HRP) provides better risk-adjusted returns (higher Sharpe ratio).
- Equal Weight (EW) delivers higher raw returns but with greater volatility.
- HRP is more diversified (higher DR and ENB), making it more resilient to market shocks.
    
### Source

[Stock Portfolio Optimization Dataset for Efficient from Kaggle](https://www.kaggle.com/datasets/chibss/stock-dataset-for-portfolio-optimization)
