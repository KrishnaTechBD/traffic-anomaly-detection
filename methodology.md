# Methodology

## Problem Formulation
We formulate the central task for **Traffic Anomaly Detection with Classical and Deep Baselines** through the governing equation below.

$$s(x)=\lambda_1 s_{\mathrm{IF}}(x)+\lambda_2 s_{\mathrm{AE}}(x)$$

## Variable Definitions
| Symbol | Definition | Value |
|---|---|---|
| s(x) | Final anomaly score | Derived |
| s_{\mathrm{IF}}(x) | Isolation Forest score | Derived |
| s_{\mathrm{AE}}(x) | Autoencoder reconstruction score | Derived |
| \lambda_1,\lambda_2 | Fusion weights | 0.5, 0.5 |

## Evaluation Logic
The repository is framed around benchmark-aware comparison, reproducible parameterization, and professor-friendly reporting.
