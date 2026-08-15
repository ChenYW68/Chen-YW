---
title: "Estimating direct and indirect treatment effects and ranking treatment regimens in spacetime-dependent cluster randomized trials: a Schistosomiasis case study"
collection: publications
category: conferences
permalink: /publication/2025-10-01-JSTVC-number-11
excerpt: 'This paper investigated direct and indirect treatment effects and ranked treatment regimens in spacetime-dependent cluster randomized trials'
date: 2025-10-01
venue: 'XXX'
slidesurl: 
paperurl: 
bibtexurl: 
citation: '<strong>Chen Y</strong>, Wen X, Luo F, Yang Y, and Shen Y. (2025). &quot;Estimating direct and indirect treatment effects and ranking treatment regimens in spacetime-dependent cluster randomized trials: a Schistosomiasis case study.&quot; <i>Revised</i>.'
---

To identify the most effective treatment sequences for schistosomiasis, cluster randomized trials were conducted over five years across multiple countries. 
Accurate and reliable sequence ranking is essential for informing mass drug administration strategies. However, these efforts are often hindered by bias and large variance in treatment effect estimation. Bias may arise from inadequate accounting for Indirect Effects (IEs) and time-varying Direct Effects (DEs), while large variance may result from insufficient consideration of intrinsic dependence structures. To address these challenges, we decompose the effects into DEs from the most recent intervention and IEs driven primarily by historical treatment trajectories. To estimate DEs and IEs, we develop a joint varying coefficient model that accounts for spatiotemporal dependence induced by the transmission dynamics of schistosomiasis. To facilitate both statistical inference and rigorous comparisons across sequences under complex spatiotemporal dependence, we develop a scalable variational Bayes algorithm with an ensemble-based correction to improve uncertainty quantification. Simulations and real-data analyses show that explicitly quantifying DEs, IEs, and spacetime-dependent effects improves the accuracy of treatment effect estimation and the reliability of treatment sequence ranking. Most importantly, switching from Community-Wide Treatment (CWT) to school-based treatment in years 3-4 showed no clear evidence of a difference in average treatment effect compared with maintaining CWT throughout, with an estimated difference of -0.027 (95% credible interval: [-0.117, 0.065]). This finding suggests that reducing reliance on resource-intensive CWT may preserve comparable population-level benefits.

<figure id="Figure1">
  <table align="center">
    <tr>
      <td><img src="https://chenyw68.github.io/Chen-YW/images/Papers/JSTVC-Fig4_Ranks.jpg" width="500px"></td>
    </tr>
  </table>
  <figcaption align="center">
    <strong>Figure 1:</strong> Ranking treatment sequences across methods: (A) The proposed JSTVC; (B) JSTVC without the spatiotemporal random effect; (C) JSTVC which mixed DEs and IEs and did not decompose the ATE; and (D) Ranking based on the average
reduction in outcomes from Year 1 to Year 5. 
  </figcaption>
</figure>

<figure id="Figure2">
  <table align="center">
    <tr>
      <td><img src="https://chenyw68.github.io/Chen-YW/images/Papers/JSTVC-Fig6_Kenya_Wts.jpg" width="500px"></td>
    </tr>
  </table>
  <figcaption align="center">
    <strong>Figure 2:</strong> Spatiotemporal patterns of the different components.
  </figcaption>
</figure>
