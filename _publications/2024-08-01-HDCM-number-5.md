---
title: "Efficient and effective calibration of numerical model outputs using hierarchical dynamic models"
collection: publications
category: manuscripts
permalink: /publication/2024-08-01-HDCM-number-5
excerpt: 'This paper developed hierarchical dynamic models with advanced variational Bayes and ensemble algorithm for addressing bias-correction.'
date: 2024-08-01
venue: 'The Annals of Applied Statistics'
slidesurl: 'https://chenyw68.github.io/Chen-YW/files/Efficient and effective calibration of numerical model outputs using hierarchical dynamic models.pdf'
paperurl: 'https://chenyw68.github.io/Chen-YW/files/HDCM_suppa.pdf'
bibtexurl: 'https://chenyw68.github.io/Chen-YW/files/Chen2024efficient.bib'
citation: '<strong>Chen Y</strong>, Chang X, Zhang B, and Huang H. (2024). &quot;Efficient and effective calibration of numerical model outputs using hierarchical dynamic models.&quot; <i>The Annals of Applied Statistics</i>. 18(2): 1064-1089.'
---

Numerical air quality models, such as the Community Multiscale Air Quality (CMAQ) system, play a critical role in characterizing pollution levels at fine spatial and temporal scales. The model outputs, however, tend to systematically over- or underestimate the real pollutant concentrations. In this study we propose a Bayesian hierarchical dynamic model to calibrate large-scale grid-level CMAQ model outputs using data from other sources, especially point-level observations from sparsely located monitoring stations. In our model a stochastic integro-differential equation (IDE) is implemented to account for space-time interactions of air pollutants. To better approximate the spatial pattern of pollutants, we employ nonregular meshes to discretize IDEs. A spatial partitioning procedure is embedded to improve the scalability of the approach for very large meshes. An algorithm based on variational Bayes and ensemble Kalman smoother is developed to accelerate the parameter estimation and calibration procedure. We apply the proposed approach to calibrate CMAQ outputs for China’s Beijing–Tianjin–Hebei region. In contrast to existing methods, the proposed approach captures space-time interactions, produces more accurate calibration results, and operates at a higher computational efficiency. A reanalysis dataset is also adopted to demonstrate the effectiveness and efficiency of our approach to large spatial data.