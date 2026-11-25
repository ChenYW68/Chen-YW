---
title: "Identifying optimal schistosomiasis treatment sequences for mass drug administration using direct and indirect effects in spatiotemporal trials"
collection: publications
category: conferences
cv_section: methodology
permalink: /publication/2025-10-01-JSTVC-number-11
excerpt: 'This paper addresses three key scientific questions concerning Mass Drug Administration (MDA) in spatiotemporal cluster-randomized trials: (a) Do the MDA treatment sequences evaluated in the SCORE CRT differ significantly in their treatment effects? (b) To what extent do the benefits of previous MDA treatments persist into untreated years and influence the effectiveness of subsequent treatment sequences? and (c) How does spatiotemporal heterogeneity in schistosomiasis transmission influence the effectiveness and ranking of MDA treatment sequences?'
date: 2025-10-01
venue: 'XXX'
slidesurl: 
paperurl: 
bibtexurl: 
citation: '<strong>Chen Y</strong>, Wen X, Luo F, Yang Y, and Shen Y. (2025). &quot;Identifying Optimal Schistosomiasis Treatment Sequences for Mass Drug Administration Using Direct and Indirect Effects in Spatiotemporal Trials.&quot; <i>Third-round revision</i>.'
---

To identify optimal schistosomiasis treatment sequences for informing mass drug administration strategies, cluster randomized trials were conducted over five years across multiple countries. However, accurate and reliable sequence ranking is often hindered by bias and large variance in treatment effect estimation. Bias may arise from inadequate accounting for Indirect Effects (IEs) and Direct Effects (DEs), while large variance may result from insufficient consideration of intrinsic dependence structures.
To address these challenges, we decompose effects into DEs from the most recent treatment and IEs driven primarily from prior treatment trajectories.
To model DEs and IEs, we propose a joint varying coefficient model that accounts for spatiotemporal dependence induced by the transmission dynamics of schistosomiasis. 
To facilitate scalable inference and improve uncertainty quantification, we develop an ensemble-corrected variational Bayes algorithm for model implementation.
Simulations and real-data analyses show that explicitly quantifying DEs, IEs, and spacetime-dependent effects improves treatment effect estimation and sequence ranking.
Interestingly, switching from Community-Wide Treatment (CWT) to school-based treatment in Years 3--4 showed no significant difference in cumulative treatment effects compared with maintaining CWT throughout (-0.03; 95% credible interval: [-0.16, 0.11]). Reducing reliance on CWT may be promising, but further research is needed to establish comparable population-level benefits.

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
    <strong>Figure 2:</strong> Spatiotemporal patterns of the different components. Top panel: Observed prevalence. Middle panel: Treatment effects. Bottom panel: Recovered spatiotemporal random effects.
  </figcaption>
</figure>
