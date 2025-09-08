Monte Carlo Sampling Library for Probabilistic Inference
Overview

This project implements a mini-library of advanced MCMC algorithms for sampling from high-dimensional probability distributions, with a focus on Bayesian inference in machine learning.

Implemented algorithms:

Metropolis–Hastings (MH)

Gibbs Sampling

Hamiltonian Monte Carlo (HMC)

Metropolis-Adjusted Langevin Algorithm (MALA)

Stochastic Gradient Langevin Dynamics (SGLD)

Stochastic Gradient Hamiltonian Monte Carlo (SGHMC)

These methods are implemented from scratch in Python with modular design, allowing users to plug in arbitrary target distributions and gradients.

⚡ Motivation

Traditional MCMC methods like MH and Gibbs struggle in high-dimensional parameter spaces.
This project explores gradient-based and stochastic-gradient MCMC (SGLD, SGHMC), which:

Scale better to large datasets via minibatching

Exploit gradient information for efficient exploration

Are widely used in Bayesian deep learning and probabilistic ML

🛠️ Features

Modular design for arbitrary target distributions

Gradient-based samplers (MALA, HMC, SGHMC) for efficient high-d sampling

Minibatch-based SGLD / SGHMC for scalability to large datasets

Convergence diagnostics:

Trace plots

Autocorrelation

Effective Sample Size (ESS)

Example applications on:

Multimodal distributions

High-dimensional Bayesian Logistic Regression
