# finstats_campbell

# Probability, Statistics, Econometrics, and Finance with Python

This repository contains a sequence of Jupyter notebook lectures for a course in probability, statistics, econometrics, finance, and modern machine learning. The notebooks are designed for students in finance, accounting, economics, and business analytics who want to learn statistical and financial modeling through both theory and Python implementation.

The course begins with probability distributions and statistical inference, moves through regression, time series, asset pricing, valuation, causal inference, and machine learning, and then extends into neural networks and derivatives pricing.

Each notebook includes lecture notes, mathematical formulas written in LaTeX, worked examples, simulations, and Python code.

---

## Table of Contents

### Lecture 1: Probability Distributions and Descriptive Statistics

**File:** `MBA708-Lecture1.ipynb`

This lecture introduces probability, descriptive statistics, and the basic logic of random variables. Topics include mean, variance, skewness, kurtosis, quantiles, the Gini coefficient, normal, uniform, exponential, binomial, Poisson, gamma, and log-normal distributions. The lecture also introduces convergence, the Law of Large Numbers, and the Central Limit Theorem through simulation.

---

### Lecture 2: Hypothesis Testing and Experimental Design

**File:** `MBA708-Lecture2.ipynb`

This lecture introduces hypothesis testing, test statistics, standard errors, p-values, statistical significance, Type I and Type II errors, power analysis, ANOVA, non-parametric tests, Bayesian hypothesis testing, and experimental design. The notebook emphasizes both the logic of inference and the practical design of statistical tests.

---

### Lecture 3: Relationships Between Variables, Regression, Correlation, and Copulas

**File:** `MBA708-Lecture3.ipynb`

This lecture covers covariance, correlation, conditional covariance, partial correlation, grouped relationships, and basic econometric regression. It also introduces copulas as tools for modeling dependence structures beyond linear correlation, especially in financial applications where tail dependence matters.

---

### Lecture 4: Simulation, Time Series, Forecasting, and Risk

**File:** `MBA708-Lecture4.ipynb`

This lecture covers simulation and time-series analysis. Topics include Brownian motion, binomial distributions, Monte Carlo simulation, mean reversion, stationarity, ADF and KPSS tests, autocorrelation, AR, ARIMA, SARIMA-style ideas, GARCH intuition, value at risk, conditional value at risk, VAR models, impulse response functions, and macro-financial time-series applications.

---

### Lecture 5A: Portfolio Theory, Markowitz, Diversification, and CAPM

**File:** `MBA708-Lecture5A.ipynb`

This lecture provides a thorough treatment of portfolio theory. Topics include the Markowitz mean-variance framework, gains to diversification, portfolio standard deviation as assets are added, systematic and unsystematic risk, expected and unexpected returns, beta, the one-factor CAPM, the two-fund theorem, the risk-free asset, leverage, the Sharpe ratio, Treynor ratio, Jensen’s alpha, information ratio, the Security Market Line, and the Capital Market Line.

---

### Lecture 5B-1: Time Value of Money, Interest Rates, and Bonds

**File:** `MBA708-Lecture5B1.ipynb`

This lecture covers time value of money and fixed-income valuation in depth. Topics include present value logic, non-constant cash flows, constant cash flows, annuities, perpetuities, internal rates of return, modified IRR, crossover rates, bond pricing, coupon frequency, discount and premium bonds, nominal and real interest rates, the Fisher equation, credit spreads, default risk, duration, convexity, yield curves, forward rates, term-structure models, and bond arbitrage examples.

---

### Lecture 5B-2: Stock Valuation, WACC, and Capital Structure

**File:** `MBA708-Lecture5B2.ipynb`

This lecture covers stock valuation and capital structure. Topics include dividend discount models, dividend yield, capital gains yield, constant-growth and multi-stage dividend models, free cash flow valuation, the cost of equity, CAPM-based discount rates, WACC, debt, preferred stock, common equity, tax shields, bankruptcy and distress costs, leverage, and the Modigliani-Miller theorem.

---

### Lecture 5C: Consumption-Based and Production-Based Asset Pricing

**File:** `MBA708-Lecture5C.ipynb`

This lecture connects asset pricing to macroeconomics and price theory. Topics include the stochastic discount factor, consumption-based asset pricing, the Lucas tree model, indifference curves, budget constraints, optimality conditions, the Hansen-Jagannathan bound, the equity premium puzzle, the risk-free rate puzzle, production-based asset pricing, Cobb-Douglas production, isoquants, isocost curves, supply and demand, cost curves, marginal revenue, operating leverage, and the link between firm profits and expected returns.

---

### Lecture 5D: Options Pricing Models

**File:** `MBA708-Lecture5D.ipynb`

This lecture introduces options and derivatives pricing. Topics include calls, puts, payoff diagrams, option strategies, put-call parity, dynamic hedging, the binomial option pricing model, Brownian motion, geometric Brownian motion, stochastic calculus, Itô’s lemma, the Black-Scholes PDE, risk-neutral pricing, the Black-Scholes formula, implied volatility, the Greeks, implied volatility smiles and surfaces, Heston stochastic volatility, Merton jump diffusion, Monte Carlo option pricing, path-dependent options, and model calibration.

---

### Lecture 6: Games of Chance, Betting Markets, and the Kelly Criterion

**File:** `MBA708-Lecture6.ipynb`

This lecture uses gambling and games of chance to teach probability, expected value, conditional probability, simulation, betting odds, bookmaker margins, parlay bets, Bayesian updating, and risk management. It concludes with a detailed treatment of the Kelly Criterion and wealth-growth simulations.

---

### Lecture 7: Linear Algebra, Regression, and Regularization

**File:** `MBA708-Lecture7.ipynb`

This lecture introduces linear algebra as the foundation of regression and machine learning. Topics include vectors, matrices, matrix multiplication, inverses, determinants, rank, eigenvalues, systems of equations, OLS as projection, multiple regression, polynomial regression, overfitting, Ridge regression, LASSO, Elastic Net, coefficient paths, and cross-validation.

---

### Lecture 8: Endogeneity and Causal Inference

**File:** `MBA708-Lecture8.ipynb`

This lecture covers the central problems of causal inference in econometrics. Topics include exogeneity, omitted variable bias, measurement error, simultaneity, selection bias, dynamic endogeneity, autocorrelation, heteroskedasticity, biased and inconsistent estimators, instrumental variables, two-stage least squares, weak instruments, fixed effects, random effects, clustered standard errors, HAC/Newey-West standard errors, difference-in-differences, regression discontinuity, propensity scores, and control-function methods.

---

### Lecture 9: Difference-in-Differences, Synthetic Control, LDV Models, and Staggered Adoption

**File:** `MBA708-Lecture9.ipynb`

This lecture goes deeper into panel-data causal inference. Topics include two-period DiD, multi-period DiD, event studies, non-parallel trends, anticipation effects, spillovers, SUTVA violations, clustered standard errors, lagged dependent variable regressions, staggered adoption, dynamic treatment effects, group-time average treatment effects, and synthetic control methods.

---

### Lecture 10: Modern Machine Learning Techniques

**File:** `MBA708-Lecture10.ipynb`

This lecture introduces modern machine learning for prediction and classification. Topics include training/testing splits, out-of-sample evaluation, bias-variance tradeoff, overfitting, cross-validation, linear regression, Ridge, LASSO, Elastic Net, logistic regression, decision trees, support vector machines, k-nearest neighbors, naive Bayes, k-means clustering, PCA, gradient descent, neural networks, backpropagation, and practical machine-learning workflows.

---

### Lecture 11: Neural Networks and Deep Learning

**File:** `MBA708-Lecture11.ipynb`

This lecture provides a deeper treatment of neural networks. Topics include artificial neural networks, perceptrons, weights, biases, activation functions, nonlinear learning, input layers, hidden layers, output layers, forward propagation, loss functions, gradient descent, backpropagation, initialization, learning rates, dropout, regularization, feedforward networks, convolutional neural networks, recurrent neural networks, feature learning, computer vision, natural language processing, finance applications, and generative AI.

---

## Suggested Course Flow

A natural course sequence is:

1. Probability and descriptive statistics  
2. Hypothesis testing and experimental design  
3. Relationships between variables and regression foundations  
4. Simulation and time series  
5. Portfolio theory and CAPM  
6. Time value of money and bonds  
7. Stock valuation, WACC, and capital structure  
8. Consumption-based and production-based asset pricing  
9. Options pricing models  
10. Games of chance, betting, and Kelly criterion  
11. Linear algebra and regularized regression  
12. Endogeneity and causal inference  
13. Difference-in-differences and synthetic control  
14. Modern machine learning  
15. Neural networks and deep learning  

Depending on the course length, Lectures 5A through 5D can be treated as a finance module, while Lectures 8 through 11 can be treated as an econometrics and machine-learning module.

---

## Software Requirements

The notebooks use standard Python scientific computing libraries, including:

- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `statsmodels`
- `scikit-learn`
- `nbformat`

Some notebooks may use more specialized packages if available, but the core sequence is designed to rely primarily on standard scientific Python tools.

---

## How to Use These Notebooks

Each notebook is designed to be read and run sequentially. Students should:

1. Read the lecture text.
2. Run each code cell.
3. Modify parameters in simulations.
4. Re-run figures and tables.
5. Interpret how changes in assumptions affect the results.
6. Use the notebooks as templates for assignments, projects, and empirical research.

The notebooks are intentionally simulation-heavy. The goal is not only to state formulas, but to show how statistical and financial models behave under controlled conditions.

---

## Pedagogical Philosophy

The course emphasizes the connection between:

- mathematical theory,
- economic intuition,
- statistical inference,
- financial modeling,
- causal identification,
- and computational implementation.

The central idea is that students should learn models by deriving them, coding them, simulating them, visualizing them, and testing their limits.

Rather than treating Python as a calculator, the notebooks use Python as a laboratory for economic and financial reasoning.

---

## Author

**Matthew L. Kelly, PhD**  
Assistant Professor of Finance  
Campbell University  
Lundy-Fetterman School of Business
