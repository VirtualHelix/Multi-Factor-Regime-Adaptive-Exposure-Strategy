# Multi-Factor-Regime-Adaptive-Exposure-Strategy-
A systematic exposure strategy that adapts to market regimes using multi-factor momentum, volatility targeting, and nonlinear signal processing for more stable and risk-aware asset allocation.
Multi-Factor Regime Adaptive Exposure Strategy

# Overview

This project implements a daily exposure strategy that integrates momentum factors, realized volatility, and market regime conditions. The model applies nonlinear transformations and volatility-aware weighting to produce smooth, risk-adjusted exposure values suitable for systematic trading pipelines.

# Methodology
	•	Long-term and short-term momentum factors
	•	Realized volatility with inverse-volatility weighting
	•	Regime filters based on volatility and short-horizon return conditions
	•	Nonlinear activation and smoothing to reduce noise
	•	Exposure clipping to maintain leverage constraints

# Backtesting:
	•	Strategy return
	•	CAGR
	•	Maximum drawdown
	•	Sharpe ratio
	•	Calmar ratio
	•	Benchmark comparison against buy-and-hold
