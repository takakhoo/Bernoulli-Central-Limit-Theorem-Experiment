# Bernoulli CLT Experiment: Empirical Verification of the Central Limit Theorem

## Overview
This project is a deep dive into the Central Limit Theorem (CLT) using Bernoulli random variables. I simulated large numbers of Bernoulli trials to demonstrate how the distribution of sample means converges to a normal distribution. The project combines rigorous mathematical analysis with extensive simulation, offering insights into the probabilistic underpinnings of convergence.

## Mathematical Framework
Let \(X\) be a Bernoulli random variable with parameter \(p\):
\[
P(X = 1) = p \quad \text{and} \quad P(X = 0) = 1 - p.
\]
For \(n\) independent trials, the sample mean is:
\[
\bar{X}_n = \frac{1}{n}\sum_{i=1}^{n} X_i.
\]
By the CLT, as \(n \to \infty\),
\[
\sqrt{n}(\bar{X}_n - p) \xrightarrow{d} \mathcal{N}(0,\, p(1-p)).
\]
This project empirically validates this convergence through simulation and visual analysis.

## Implementation & Experimentation
- **Simulation:** I used NumPy to generate large samples of Bernoulli trials across different sample sizes.
- **Visualization:** Histograms of the sample means are compared with the theoretical Gaussian curve derived from \(\mathcal{N}(0, p(1-p))\).
- **Analysis:** The convergence of empirical means and variances to their theoretical values is examined in detail.

## Usage
- **Prerequisites:** Python, NumPy, Matplotlib, SciPy.
- **Run the Notebook:** Open `Bernoulli_CLT_Experiment.ipynb` and execute the cells sequentially.
- **Customization:** Adjust \(p\) and sample sizes to explore convergence under different conditions.

---
