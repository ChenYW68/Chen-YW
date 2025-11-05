---
title: "Additive dynamic models for correcting numerical model outputs"
collection: publications
category: manuscripts
permalink: /publication/2023-06-01-paper-title-number-2
excerpt: 'This paper developed additive dynamic models with high efficient algorithms for statistical bias-correction.'
date: 2023-06-01
venue: 'Computational Statistics & Data Analysis'
slidesurl: 'https://chenyw68.github.io/Chen-YW/files/Additive dynamic models for correcting numerical model outputs.pdf'
paperurl: 'https://chenyw68.github.io/Chen-YW/files/Additive dynamic models for correcting numerical model outputs.pdf'
bibtexurl: 'https://chenyw68.github.io/Chen-YW/files/Chen2023Correction.bib'
citation: 'Chen Y, Chang X, Luo F, Huang H (2023). &quot;Additive dynamic models for correcting numerical model outputs.&quot; <i>Computational Statistics & Data Analysis</i>. 107799.'
---
Numerical air quality models are pivotal for the prediction and assessment of air pollution, but numerical model outputs may be systematically biased. An additive dynamic model is proposed to correct large-scale raw model outputs using data from other sources, including readings collected at ground monitoring networks and weather outputs from other numerical models. An additive partially linear model specification is employed for the nonlinear relationships between air pollutants and covariates. In addition, a multi-resolution basis function approximate is proposed to capture the different small-scale variations of biases, and a discretized stochastic integro-differential equation is constructed to characterize the dynamic evolution of the random coefficients at each spatial resolution. An expectation-maximization algorithm is developed for parameter estimation and a multi-resolution ensemble-based scheme is embedded to accelerate the computation. For statistical inference, a conditional simulation technique is applied to quantify the uncertainty of parameter estimates and bias correction results. The proposed approach is used to correct the biased raw outputs of PM2.5 from the Community Multiscale Air Quality (CMAQ) system for China's Beijing-Tianjin-Hebei region. Our method improves the root mean squared error and continuous rank probability score by 43.70% and 34.76%, respectively. Compared to other statistical methods under different metrics, our model has advantages in both correction accuracy  and computational efficiency.

