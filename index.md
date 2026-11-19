# Probability & Statistics with NumPy

A short course on probability and statistics, built from the ground up in Python.

The course doesn't treat statistical methods as black boxes. Each notebook builds its idea with simulation and a few lines of [NumPy](https://numpy.org): we draw samples, count outcomes, update beliefs and plot the results. This keeps the maths concrete and lets you check it against data.

## How to use these notes

- **Read online.** Every page is a notebook that was executed when the site was built, so the code, numbers and plots match.
- **Run it yourself.** Clone the [repository](https://github.com/jimnel/stats-notes), `pip install -r requirements.txt` and open the notebooks in Jupyter. Change the parameters and see what happens.

## Prerequisites

- Basic Python
- Familiarity with NumPy arrays and matplotlib is helpful, but not required
- High-school algebra. Calculus is mentioned occasionally, but the code carries the argument.

## Contents

1. [Probability basics](./notebooks/01-probability-basics.ipynb): events, conditional probability, independence and Bayes' rule
2. [Random variables, expectation and variance](./notebooks/02-random-variables.ipynb): means, variances and linearity of expectation
3. [Sampling](./notebooks/03-sampling.ipynb): drawing random samples and how sample statistics behave
4. [Common distributions](./notebooks/04-common-distributions.ipynb): Bernoulli, binomial, normal, Poisson and others, explored by simulation
5. [The law of large numbers and the central limit theorem](./notebooks/05-law-of-large-numbers-and-clt.ipynb): why averages converge and why the normal distribution is everywhere
6. [Correlation](./notebooks/06-correlation.ipynb): measuring how two variables move together
7. [Estimators](./notebooks/07-estimators.ipynb): bias, variance and standard error
8. [Most likely estimate](./notebooks/08-most-likely-estimate.ipynb): maximum likelihood estimation
9. [Confidence intervals and the bootstrap](./notebooks/09-confidence-intervals-and-bootstrap.ipynb): quantifying uncertainty by resampling
10. [Hypothesis testing](./notebooks/10-hypothesis-testing.ipynb): p-values and permutation tests
11. [Linear regression](./notebooks/11-linear-regression.ipynb): least squares as maximum likelihood
12. [Bayes estimation](./notebooks/12-bayes-estimation.ipynb): updating beliefs about a parameter with Bayes' rule
13. [Markov chain Monte Carlo](./notebooks/13-mcmc.ipynb): sampling from a posterior with a Metropolis sampler

Each chapter builds on the ones before it, so they're best read in order.
