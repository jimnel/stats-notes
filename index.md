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

1. [Sampling](./notebooks/01-sampling.ipynb): drawing random samples and how sample statistics behave
2. [Common distributions](./notebooks/02-common-distributions.ipynb): Bernoulli, binomial, normal, Poisson and others, explored by simulation
3. [Correlation](./notebooks/03-correlation.ipynb): measuring how two variables move together
4. [Most likely estimate](./notebooks/04-most-likely-estimate.ipynb): maximum likelihood estimation
5. [Bayes estimation](./notebooks/05-bayes-estimation.ipynb): updating beliefs about a parameter with Bayes' rule

Each chapter builds on the ones before it, so they're best read in order.
