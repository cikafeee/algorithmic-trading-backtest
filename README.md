# 📊 Distributed Algorithmic Trading Backtesting Engine

A scalable backtesting framework using PySpark to evaluate trading strategies across 100 stocks.

![Trading Strategy Analysis](3D%20visualization.png)

## 🎯 Project Overview

Built a distributed backtesting engine that processes **12,300 backtests** across **100 stocks**, analyzing **303,600 price records** spanning 10 years of real market data (2014-2026).

### Key Results
- 📊 **12,300** backtests completed
- 🧪 **123** trading strategies tested
- 💹 **100** stocks analyzed (S&P 500 constituents)
- 📈 **303,600** price records processed
- 🏆 **Best Sharpe:** 0.274 (RSI strategy)
- 🎯 **Best Return:** 38.5%
- 💻 **Platform:** Kaggle (30GB RAM, FREE)

## 📈 Visualizations

### Complete Analysis Dashboard
![Dashboard](Complete%20Trading%20Backtesting%20analysis%20dash....png)

*9-panel interactive dashboard showing comprehensive strategy performance*

### Strategy Type Comparison
![Strategy Types](Strategy%20Type%20Performance%20Comparison.png)

### Top Strategies
![Top 15](Top%2015%20trading%20strategies.png)

## 🏆 Top 5 Strategies

| Rank | Type | Sharpe | Return | Drawdown | Stocks |
|------|------|--------|--------|----------|--------|
| 1 | RSI | 0.274 | 38.5% | -32.2% | 100 |
| 2 | RSI | 0.218 | 31.0% | -36.2% | 100 |
| 3 | Mean Reversion | 0.216 | 13.7% | -20.3% | 100 |
| 4 | RSI | 0.213 | 16.7% | -26.7% | 100 |
| 5 | RSI | 0.199 | 37.1% | -39.6% | 100 |

**Key Finding:** RSI mean-reversion strategies outperformed trend-following during the volatile 2014-2026 period.

## 🛠️ Tech Stack

- **Big Data:** PySpark 3.5.0
- **Visualization:** Plotly, Matplotlib, Seaborn
- **Data:** yfinance (Yahoo Finance API)
- **Platform:** Kaggle Notebooks (30GB RAM)
- **Language:** Python 3.12

## 🚀 Quick Start

### Run on Kaggle (Recommended - 30GB RAM)
1. Open [`algorithmic-backtesting.ipynb`](algorithmic-backtesting.ipynb) on Kaggle
2. Enable Internet in Settings
3. Run all cells (~30-60 minutes)

### Run on Google Colab (12GB RAM)
1. Open [`colab_quick_demo.ipynb`](colab_quick_demo.ipynb) on Colab
2. Run all cells (~15-30 minutes)

### Run Locally
```bash
# Clone repo
git clone https://github.com/Het415/algorithmic-trading-backtest.git
cd algorithmic-trading-backtest

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter notebook

# Open and run notebook
```

## 💡 Key Insights

1. **RSI Dominance:** Mean-reversion outperformed in choppy 2014-2026 markets
2. **Market Cycles:** Tested across COVID crash, bull run, bear market
3. **Validation:** Results consistent across 100 different stocks
4. **Best Return:** 38.5% from top RSI strategy

## 🎓 What I Learned

- Distributed computing with PySpark and pandas UDFs
- Quantitative finance metrics (Sharpe, Calmar, Drawdown)
- Big data processing (300K+ records)
- Strategy validation across market cycles
- Professional data visualization with Plotly

## 🔮 Future Enhancements

- [ ] Deploy to AWS EMR for 500+ stock scale
- [ ] Add walk-forward analysis
- [ ] Implement transaction costs & slippage
- [ ] Real-time backtesting with streaming data
- [ ] ML-based parameter optimization

## 📊 Project Structure
```
algorithmic-trading-backtest/
├── algorithmic-backtesting.ipynb    # Main Kaggle notebook (100 stocks)
├── colab_quick_demo.ipynb           # Quick demo (30 stocks)
├── requirements.txt                  # Python dependencies
├── 3D visualization.png              # Bubble chart
├── Complete Trading Backtesting analysis dash....png
├── Strategy Type Performance Comparison.png
└── Top 15 trading strategies.png
```

## 📫 Contact

Linkedin - https://www.linkedin.com/in/het-prajapati6210/

Email- hetprajapati6210@gmail.com

Built: January 2026
