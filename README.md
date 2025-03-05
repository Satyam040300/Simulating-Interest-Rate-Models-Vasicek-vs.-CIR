# Simulating Interest Rate Models: Vasicek vs. CIR

## Project Overview
This project compares the behavior of interest rate paths simulated under two popular stochastic processes in finance: the **Vasicek model** and the **Cox-Ingersoll-Ross (CIR) model**. Both models are used for modeling the evolution of interest rates over time, with the Vasicek model assuming mean reversion with constant volatility and the CIR model incorporating volatility that depends on the interest rate, ensuring non-negative values. The project implements both models using Python, simulating multiple interest rate paths and visualizing the results.

## Models Overview

### Vasicek Model
The Vasicek model describes the evolution of interest rates as a mean-reverting process with constant volatility. It is widely used in fixed-income modeling and risk management.

### CIR Model
The CIR model is similar to the Vasicek model but with volatility that depends on the current interest rate level, ensuring that interest rates remain non-negative. This makes the CIR model more realistic in modeling interest rates over time.

## Key Features

- **Interest Rate Simulations**: Simulate multiple paths for interest rates based on the Vasicek and CIR models.
- **Monte Carlo Simulation**: Uses Monte Carlo methods to simulate interest rate paths under stochastic conditions.
- **Data Visualization**: Visualize the simulated interest rate paths using `matplotlib`, comparing the dynamics of the Vasicek and CIR models.

## Requirements

- Python 3.x
- NumPy
- Matplotlib


## Skills Learned

- **Stochastic Process Modeling**: Implemented and analyzed mean-reverting processes in financial modeling.
- **Monte Carlo Simulation**: Applied Monte Carlo methods to simulate multiple interest rate paths.
- **Numerical Methods**: Used the Euler-Maruyama method to discretize and simulate stochastic differential equations (SDEs).
- **Python Programming**: Gained proficiency with Python libraries like `numpy` for numerical computations and `matplotlib` for data visualization.
- **Financial Modeling**: Developed a deeper understanding of how different models of interest rates can impact financial forecasting and risk management.

## Usage

This project provides a comprehensive comparison of two key interest rate models. The results can be visualized as graphs showing the simulated interest rate paths for both models, allowing for a deeper understanding of their behavior over time.



