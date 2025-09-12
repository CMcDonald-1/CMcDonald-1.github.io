---
title: "Sampling Algorithms for Machine Learning with Auxiliary Random Variables and Diffusion Models"
collection: talks
type: "Talk"
permalink: /talks/isit_2024-talk
venue: "Simons Institute, UC Berkeley"
date: 2025-09-12
location: "Berkeley, California, USA"
---

**Abstract:**

The vast majority of training for supervised learning algorithms today is done via optimization, due to the maturity and speed of efficient gradient-based algorithms for implementation. 
A Bayesian approach to machine learning has been largely abandoned due to the failure of traditional Markov Chain Monte Carlo (MCMC) algorithms to sample from complex posterior distributions in a reasonable amount of time.

At the same time, in recent years diffusion models have proven to be a remarkably effective generative algorithm for sampling from complex and high dimensional target densities in examples such as Stable Diffusion and DALL-E. 
Additionally, many of the best MCMC algorithms we have today make use of auxiliary random variables, creating joint distributions between “target” variables we want to be sampling and “auxiliary” variables that are designed by the practitioner to facilitate sampling the target variable. 
Examples include Hamiltonian Monte Carlo with a “momentum” variable, simulated tempering with a “temperature” variable, and proximal sampling.

Combining these two ideas, diffusion models can be viewed as a mathematical object defining a series of auxiliary random variables coupled with the target variable that can facilitate sampling. 
Under certain conditions, we can demonstrate a mixture representation of the target density where the mixture components are well suited to traditional MCMC sampling. 
This structure has been named a “Log-Concave Coupling” in past research by this author. 
Under such a structure, a sample of the auxiliary random variable from its marginal density, followed by a sample of the target random variable from its conditional density can be accomplished 
efficiently by traditional MCMC methods such as Langevin Diffusion. This produces an equivalent sample of the target variable from its original target density, while only having to sample from 
log-concave densities in each step.

Slideshow: [More information here](/assets/pdf/meet_the_fellows_c_mcdonald.pdf)
