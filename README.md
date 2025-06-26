# Quantitative Portfolio Optimization

## Project Overview
A systematic framework for constructing and evaluating optimized portfolios using 5 years of market data (2020-2025). Implements two distinct strategies:
- **High-risk**: Tech/growth stocks (NVDA-heavy)
- **Low-risk**: Defensive equities (KO-dominated)

## Key Features
- 📈 Market regime detection (PCA + K-Means)
- 🤖 ML trading signals (90% accuracy)
- ⚖️ Blended portfolio optimization
- 🧪 Comprehensive backtesting
- 📉 Advanced risk metrics (VaR, CVaR)
- 🌪️ Stress testing framework
- 🛡️ Auto-hedging system

## Portfolio Performance
| Metric          | High-Risk | Low-Risk |
|-----------------|----------|----------|
| Annual Return   | 39.51%   | 14.1%    |
| Sharpe Ratio    | 1.31     | 0.94     |
| Max Drawdown    | -29.41%  | -12.90%  |

## Installation
```bash
git clone https://github.com/yourusername/portfolio-optimization.git
cd portfolio-optimization
pip install -r requirements.txt
