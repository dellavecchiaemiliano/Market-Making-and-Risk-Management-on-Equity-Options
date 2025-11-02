# Market-Making-and-Risk-Management-on-Equity-Options
This project was developed as part of the Market Risk Management course in the MAFINRISK master’s program (Bocconi University, 2024/25).
It simulates the risk management framework of a market-making desk trading equity options, with a focus on delta-hedging, second-order risk exposure, and regulatory-style risk controls.

Overview

The assignment consisted in designing, pricing, and risk-managing a market-making portfolio based on Charter Communications (CHTR) stock.
The strategy involved:

Structuring a bull spread OTC option trade for a client.

Building a delta-neutral, gamma- and vega-sensitive portfolio using listed options and the underlying stock.

Managing exposure under hard and soft limits through Value-at-Risk (VaR) and stress test metrics.

Quantitative Framework

Volatility Modeling: Forecasted implied volatility using a GARCH(4,1) model with generalized error distribution.

Risk Metrics:

Sensitivity analysis (Delta, Gamma, Vega)

95% Value-at-Risk (VaR) with a 5-day horizon

Stress tests under historical and hypothetical market scenarios

Limit Structure:

Global VaR limit: $10,000

Measured VaR: $9,794 → 97.9% utilization

Additional granular limits for volatility and market shifts

Key Results

The delta-neutral strategy ensured exposure control while profiting from volatility fluctuations.

Stress test scenarios (e.g., 2022 Rate Hikes, Post-COVID Shock) validated portfolio resilience.

The model replicated real trading desk practices in risk steering and portfolio optimization.
