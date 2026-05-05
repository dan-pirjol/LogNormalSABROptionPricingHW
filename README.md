# LogNormalSABROptionPricingHW
This repository contains code for option pricing in the log-normal SABR model using an approximation for the joint distribution of the time-integral of a geometric Brownian motion and its terminal value from an asymptotic expansion of the Hartman-Watson integral obtained in [this paper](https://arxiv.org/abs/2001.09579).
The option prices are expressed as 2-dim integrals over a function known in closed form. 

Numerical illustration showing the implied volatility for several benchmark cases with maturities up to 5 years. 

<img width="614" height="456" alt="4benchmarks" src="https://github.com/user-attachments/assets/85ff3873-f9b9-43ab-a92d-384dff563dab" />

The red dots are benchmark values from Table 8.7 of [A.Lewis, Option valuation under stochastic volatility 2.](https://www.amazon.com/Option-Valuation-under-Stochastic-Volatility/dp/096763721X)
