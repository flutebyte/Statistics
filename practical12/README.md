# Metropolis Algorithm Implementation

A Python implementation of the Metropolis-Hastings algorithm for sampling from probability distributions, with applications to Monte Carlo integration.

## 📋 Project Overview

This project demonstrates:
- **Metropolis-Hastings algorithm** for Markov Chain Monte Carlo (MCMC) sampling
- **Target distribution**: Standard Normal Distribution N(0,1)
- **Comparison** between deterministic grid integration and Monte Carlo methods
- **Expectation calculation** for E[X²] using both approaches

## 🚀 Features

- **Metropolis Sampler**: Custom implementation with configurable parameters
  - Burn-in period
  - Thinning for reducing autocorrelation
  - Adjustable proposal distribution
- **Deterministic Integration**: Grid-based computation for comparison
- **Visualization**: Histograms and density plots
- **Performance Metrics**: Acceptance rate and convergence diagnostics

## 📊 Results

### Metropolis Sampling
- **Acceptance Rate**: ~71%
- **Sample Mean**: ≈ 0.0 (theoretical: 0.0)
- **Sample Variance**: ≈ 1.0 (theoretical: 1.0)

### Expectation E[X²]
- **Deterministic (Grid)**: 0.99999
- **Monte Carlo (Metropolis)**: 1.00067
- **Theoretical Value**: 1.0

## 🛠️ Installation & Usage

```bash
# Clone the repository
git clone https://github.com/yourusername/metropolis-algorithm.git
cd metropolis-algorithm

# Install dependencies
pip install numpy matplotlib
