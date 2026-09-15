# Probability Experiments: Bernoulli Estimation and the Central Limit Theorem

A compact, executable study of discrete and continuous random variables,
Bernoulli parameter estimation, and the Central Limit Theorem (CLT). The
notebook connects each mathematical result to a NumPy/SciPy experiment and a
visual check.

## What this demonstrates

- Expected value and variance for a discrete distribution
- Numerical integration for a continuous probability density
- Maximum-likelihood and Bayesian estimates for a Bernoulli parameter
- Convergence of sample means toward a Gaussian distribution as sample size
  increases

## Quick start

```bash
git clone https://github.com/takakhoo/Bernoulli-Central-Limit-Theorem-Experiment.git
cd Bernoulli-Central-Limit-Theorem-Experiment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
python -m pip install -r requirements.txt
jupyter lab "Bernoulli CLT Experiment.ipynb"
```

[Open the executed notebook](Bernoulli%20CLT%20Experiment.ipynb)

## Mathematical focus

For independent Bernoulli trials with success probability \(p\), the notebook
compares the empirical sampling distribution with

\[
\sqrt{n}(\bar X_n-p) \xrightarrow{d} \mathcal{N}(0,p(1-p)).
\]

The cells are arranged as an exploratory lab: change the prior, success
probability, sample size, or number of simulations and rerun from top to bottom.

## Scope

This is an educational experiment, not a general-purpose statistics package.
It is useful as a transparent reference for the assumptions and mechanics
behind common estimators and asymptotic approximations.
