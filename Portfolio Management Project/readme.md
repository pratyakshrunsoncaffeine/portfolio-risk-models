# Portfolio Optimization and Risk Analysis

This project explores the fundamental concepts and practical implementation of portfolio management using Python. It covers essential techniques for measuring risk, return, diversification benefits, and optimal asset allocation. The project is designed to simulate real-world investment decision-making using financial theory, statistical modeling, and data-driven analysis.

---

## Project Scope

The following key concepts and tools are demonstrated:

### 1. Data Collection and Stack
- Financial data fetched using **Yahoo Finance (`yfinance`)**
- Core Python libraries used: `NumPy`, `Pandas`, `Matplotlib`, `Seaborn`, `datetime`

### 2. Return and Risk Analysis
- **Arithmetic vs Geometric Annualized Returns**:
  - Demonstrates the impact of volatility drag (variance drain)
  - Includes visual representation in Excel
- **Annualized Risk**:
  - Computed using standard deviation of daily returns
- **Diversification Risk**:
  - Analysis of how combining assets lowers portfolio-level volatility
  - Portfolio correlation matrix visualized using a Seaborn heatmap

### 3. Two-Asset Portfolio Simulation
- Simulates a **60/40 allocation** between risky and safe assets
- Demonstrates the reduction in risk compared to holding a single asset

### 4. Efficient Frontier and Sharpe Ratio
- Monte Carlo simulation of random portfolio weights
- Constructs the **Efficient Frontier** and calculates the **Sharpe Ratio**
- Identifies the **Minimum Risk Portfolio** and the **Optimal Risk-Return Portfolio**

### 5. Comparative Risk–Return Analysis
- Compares multiple portfolios on a risk–return scatter plot:
  - Minimum volatility portfolio
  - Maximum Sharpe ratio portfolio
  - Equal-weight portfolio

---

##  Planned Enhancements (In Progress)
###  Portfolio Optimization with Constraints
  - Maximize Sharpe Ratio with constraints
  - No shorting (weights ≥ 0)
  - Max 30% allocation per asset

###  Rolling Window Backtest
- Simulate optimal portfolio allocations over time
- Evaluate time-varying Sharpe Ratio and returns

###  Benchmark Comparison (e.g., SPY)
- Benchmark performance against **S&P 500 ETF (SPY)**
- Compare cumulative returns, volatility, and Sharpe Ratio

### Factor Models (CAPM / Fama-French)
- Regress portfolio excess returns using CAPM:
- Analyze portfolio beta and alpha relative to market index

###  Stress Testing / Scenario Analysis
- Evaluate how portfolio performance changes under:
- AAPL crash
- Bond volatility spike
- Gold drawdown

###  Global Diversification
- Expand asset universe:
- Add Nikkei (^N225), Brazil (EWZ), Bitcoin (BTC-USD), and Gold (GLD)
- Assess diversification benefits across geographies

###  Visual and UX Enhancements
- Improve visual aesthetics with:
- Custom color palettes
- `Plotly` for interactivity
- Clean axis formatting and layout control

---

##  Deliverables

-  `Portfolio_Management.ipynb`: Main analysis notebook
-  `PortfolioAnalysis_Report.ipynb`: (Upcoming) Research & explanation notebook
-   Visual plots (PNG/interactive) embedded throughout
-   Excel files used for variance drain visualization

---

##  Learning Outcomes

- Strong understanding of portfolio theory and financial modeling
- Hands-on application of Python in finance
- Ability to communicate investment insights clearly and effectively

