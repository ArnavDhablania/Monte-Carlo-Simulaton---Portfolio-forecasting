# Monte Carlo Portfolio Simulation

This project uses a Monte Carlo Simulation to model potential future returns of an investment portfolio under uncertainty. The simulation estimates a distribution of outcomes instead of a single prediction, helping evaluate risk, volatility, and likelihood of outperforming benchmark investments.

---

## 📂 Project Contents

| File | Description |
|------|-------------|
| `Workspace.ipynb` | Main Jupyter Notebook containing the full Monte Carlo simulation code, analysis, and visualizations |
| `Observations.ipynb` | Written report discussing findings, insights, and interpretation of the simulation results |
| `Portfolio.xlsx` | Dataset containing initial portfolio allocation/tickers/weights |
| `Portfolio2.xlsx` | Secondary or modified portfolio dataset used for comparison/scenario testing |

---

## 🎯 Objectives

- Simulate possible portfolio performance over a defined time horizon
- Estimate risk and uncertainty using repeated random sampling
- Compare simulated returns to benchmarks (e.g., market index or alternate portfolio)
- Visualize distributions, confidence intervals, and outcome probabilities
- Provide actionable insights about portfolio risk vs reward

---

## 🧠 Methodology (High-Level)

1. Load portfolio data from Excel files
2. Define simulation parameters:
   - Time horizon
   - Number of simulations
   - Expected returns + volatility
3. Randomly generate asset returns using probability distributions
4. Recalculate portfolio value across thousands of trials
5. Analyze results:
   - Expected return
   - Worst-case / best-case outcomes
   - Probability of outperforming the benchmark
   - Sharpe Ratio
6. Visualize results using plots and distributions
