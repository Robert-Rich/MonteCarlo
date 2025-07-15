# MonteCarlo Portfolio Simulation
This project implements a basic Monte Carlo simulation to model the future price paths of financial assets and estimate the potential distribution of a portfolio's value over time.
- Daily expected returns (`μ`)
- Daily volatility (`σ`)
- Correlated asset behavior via a **Cholesky-decomposed covariance matrix**

# Measures 
- Simulated asset values over time
- Computes portfolio value at each timestep
- Visualises distribution of possible outcomes
- Approximates risk under uncertainty.

# Mathematical Model 
Asset prices  $$S_t$$  are modeled using the GBM formula:

$$ S_t = S_0 \cdot \exp \left( \left( \mu - \frac{1}{2} \sigma^2 \right)t + \sigma W_t \right) $$

Where:
- `μ` is the expected return
- `σ` is the volatility
-  `Wₜ` is Brownian motion

# Requirements 
- Python 3.7+
- numpy
- matplotlib
- yfinance, you can adjust which tickers to be modelled manually. 


