# Financial Risk Analytics Suite
A personal project that demonstrates the core risk modeling concepts used in banking
and finance. Built using real market data across 3 modules: Credit Risk, Market Risk, and Portfolio Optimization.
## Motivation
Risk modeling and analytics are core functions of every major bank and financial institution. This project was built to develop  hands-on experience with the same fundamental models used by risk analysts — including probability of default modeling, Value at Risk calculation, and portfolio optimization. All models are built using real market data and publicly available datasets. 
## Project Structure

financial-risk-analytics/
- data/
- notebooks/
    - 01_credit_risk.ipynb
    - 02_market_risk.ipynb
    - 03_portfolio_optimization.ipynb
- outputs/
- README.md

## Modules

### 1. Credit Risk
Built a logistic regression model to predict the probability of loan default using 30,000 real borrowers from the UCI Credit Cart Default dataset. Model achieved 80.85% accuracy on unseen test data.

### 2. Market Risk 
Calculated Value at Risk (VaR) on a 5-stock banking portfolio using 2 methods: Historical Simulation and Monte Carlo Simulation (10,000 scenarios). Applied  to a $1,000,000 portfolio. 

### 3. Portfolio Optimization
Simulation 5,000 randomly weighted portfolios using Modern Portfolio Theory. Identified the optimal portfolio allocation using the Sharpe Ratio, achieving an expected annual return of 34.74% with a Sharpe Ratio of 2.14.

## Key Results

| Module | Metric | Result | 
|--------|--------|--------|
| Credit Risk | Model Accuracy | 80.85% |
| Credit Risk | Test Borrowers | 6,000 |
| Market Risk | 95% VaR (Historical) | -1.74% |
| Market Risk | 99% VaR (Historical) | -2.72% |
| Market Risk | 95% VaR (Monte Carlo) | -1.79% |
| Market Risk | 99% VaR (Monte Carlo) | -2.68% |
| Portfolio Optimization | Expected Annual Return | 34.74% | 
| Portfolio Optimization | Annual Volatility | 16.21% | 
| Portfolio Optimization | Sharpe Ratio | 2.14 | 

## Tools Used

**Languages**
- Python

**Libraries**
- pandas
- numpy
- matplotlib
- scikit=learn
- yfinance

**Environment**
- Jupyter Notebook
- VS Code
- Anaconda
- Git

## How to Run

1. Clone the repository
2. Open Anaconda Navigator and launch Jupyter Notebook
2. Navigate to the notebooks folder
4. Run the notebooks in order:
   - 01_credit_risk.ipynb
   - 02_market_risk.ipynb
   - 03_portfolio_optimization.ipynb

**Requirements**
- Anaconda
- yfinance

**Data** 
- Download UCI Credit Card Default dataset from Kaggle
- Place the CSV file in the data folder