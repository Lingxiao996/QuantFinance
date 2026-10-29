# Quantitative Finance Projects

**Lingxiao Li**

Projects from my Certificate in Quantitative Finance (CQF) studies, covering portfolio optimisation, market risk, numerical option pricing and financial machine learning.

## Exam 1 — Portfolio Optimisation and VaR Backtesting

Derives the global minimum-variance portfolio for four asset classes, explores feasible risk–return combinations using random portfolio allocations, and backtests a 99% ten-day Normal Value at Risk (VaR) measure using NASDAQ-100 data.

- [Analysis and report](CQF_Exam1_Portfolio_Optimisation_and_VaR_Report.pdf)
- [VaR backtesting notebook](CQF_Exam1_VaR_Backtesting.ipynb)
- [Portfolio Monte Carlo spreadsheet](CQF_Exam1_Portfolio_Monte_Carlo.xlsx)

## Exam 2 — Monte Carlo Option Pricing

Prices European call and put options using Euler–Maruyama, Milstein and exact geometric Brownian motion simulation, with Black–Scholes prices as analytical benchmarks. The analysis examines sampling error, time-discretisation error, antithetic variates and option Greeks.

- [Option pricing notebook](CQF_Exam2_Monte_Carlo_Option_Pricing.ipynb)

## Exam 3 — SPY Machine Learning

Develops a binary classification workflow for meaningful positive next-day SPY returns. The workflow constructs 54 candidate features, retains 12 through feature selection, and compares XGBoost, LightGBM and CatBoost using chronological validation and a final test period.

The notebook discusses weak predictive evidence, differences between validation and later-period results, and a subsequent exploratory comparison of seven versus twelve features.

- [SPY machine learning notebook](CQF_Exam3_SPY_Machine_Learning.ipynb)

## Viewing and Running

The notebooks contain code, explanations and saved outputs. Open them in Jupyter Notebook or Google Colab, follow their setup cells and imports, and run the cells in order.

The VaR notebook expects an input file named `E1_NASDAQ100_mid2019_2021.csv` in its working directory. The SPY notebook retrieves market data and uses Weights & Biases for experiment tracking. The notebooks specify their data inputs and package requirements.
