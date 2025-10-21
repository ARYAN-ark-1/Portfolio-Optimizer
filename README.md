# Portfolio Optimization using Python

This project implements a **mean-variance optimization framework** across 50+ assets, leveraging Monte Carlo simulations, covariance clustering, dynamic rebalancing, and tail-risk analysis. It is designed to optimize portfolio allocation, reduce risk, and improve Sharpe ratio in line with Modern Portfolio Theory principles.

---

## **Key Highlights**

- Built a **mean-variance optimization framework** across 50+ assets  
- Conducted **1,000+ Monte Carlo simulations** to evaluate portfolio risk and performance  
- Implemented **covariance clustering and dynamic rebalancing**, reducing drawdowns by ~18%  
- Calculated **tail-risk metrics (VaR, CVaR)** to monitor extreme losses  
- Increased portfolio **Sharpe ratio by ~22%** compared to an equal-weighted portfolio  

---

## **Technologies Used**

- **Python**  
- **Pandas, NumPy, SciPy**  
- **Matplotlib** (for visualizations)  
- **yfinance** (for historical market data)  

---

## **Usage Instructions**

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/Portfolio_Optimization.git
cd Portfolio_Optimization
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the notebook**
Open Portfolio_Optimization.ipynb in Jupyter Notebook or Google Colab
Run all cells sequentially


## **Features in Notebook**
Step 1: Data collection of 50+ assets from Yahoo Finance
Step 2: Mean-Variance Optimization (MPT)
Step 3: Monte Carlo simulation of 1,000+ random portfolios
Step 4: Covariance clustering for portfolio diversification
Step 5: Dynamic rebalancing (monthly)
Step 6: Tail-risk metrics calculation (VaR, CVaR)
Step 7: Drawdown analysis and visualization

## **Results**

Optimized portfolio Sharpe ratio: higher than equal-weighted portfolio (~22% improvement)
Maximum drawdown reduction: ~18%
Tail-risk metrics: VaR and CVaR show lower exposure to extreme losses
Efficient frontier and cumulative return plots for visual analysis

## **License**
This project is licensed under the MIT License.
