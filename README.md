# Bernoulli Central Limit Theorem (CLT) Experiment

This project explores and visualizes the Central Limit Theorem in the context of Bernoulli random variables. I simulate multiple Bernoulli trials, aggregate sample means, and empirically demonstrate convergence toward the normal distribution. This notebook builds foundational intuition for how and why the CLT holds, even in binary, discrete spaces.

## 🧠 Objectives

- Simulate Bernoulli trials with varying probabilities.
- Visualize sample mean distributions and compare them to the theoretical Gaussian.
- Understand the role of sample size in convergence.
- Evaluate empirical vs theoretical mean and variance.

## 🧪 Methods

- Used NumPy to simulate thousands of Bernoulli experiments.
- Compared empirical histogram results with `scipy.stats.norm.pdf` to overlay the ideal Gaussian.
- Visualized the CLT effect at multiple sample sizes (e.g. n = 10, 30, 100).

## 🔍 Key Takeaways

- The distribution of sample means for Bernoulli trials converges remarkably quickly to a normal shape.
- Sample size dramatically impacts convergence; even n=30 yields impressive results.
- Empirical variance and theoretical variance converge closely as n grows.

## 🚀 Technologies

- Python
- NumPy
- Matplotlib
- SciPy
