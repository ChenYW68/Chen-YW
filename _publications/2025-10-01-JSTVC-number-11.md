---
title: "[1] Estimating direct and indirect treatment effects and ranking treatment regimens in spacetime-dependent cluster randomized trials: a Schistosomiasis case study"
collection: publications
category: conferences
permalink: /publication/2025-10-01-JSTVC-number-11
excerpt: 'This paper investigated direct and indirect treatment effects and ranked treatment regimens in spacetime-dependent cluster randomized trials'
date: 2025-10-01
venue: 'Peer review'
slidesurl: 'https://chenyw68.github.io/Chen-YW/files/Predicting influenza vaccine-elicited antibody responses with practical point system.pdf'
paperurl: 'https://chenyw68.github.io/Chen-YW/files/Predicting influenza vaccine-elicited antibody responses with practical point system.pdf'
bibtexurl: 'https://chenyw68.github.io/Chen-YW/files/Shen2025predicting.bib'
citation: 'Chen Y, Wen X, Luo F, Yang Y, and Shen Y. (2025). &quot;Estimating direct and indirect treatment effects and ranking treatment regimens in spacetime-dependent cluster randomized trials: a Schistosomiasis case study.&quot; <i>Peer review</i>.'
---

Accurate estimation of treatment effects and reliable ranking of treatment regimens are essential to guide optimal treatment assignments in cluster randomized trials (CRTs). However, these efforts are often hindered by high bias and large variance. The high bias can arise from indirect effects (IEs) or time-varying direct effects (DEs), while the large variance results primarily from inadequate consideration of intrinsic dependencies. Motivated by the need to identify optimal treatment regimens in the Schistosomiasis CRT, this study addresses the methodological challenges introduced by sequential treatments and spatiotemporal dependencies. We identify optimal treatment regimens by evaluating differences through two components: DEs from the most recent treatment and IEs from historical treatment trajectories. To efficiently estimate DEs and IEs, we develop a Joint Spatiotemporal Varying Coefficient (JSTVC) model. JSTVC accounts for spatiotemporal dependencies and regional heterogeneities, while also capturing spatial anisotropic patterns in schistosomiasis transmission. To support scalable inference under complex dependent structures, we extend a hybrid computational method that integrates Variational Bayes with ensemble-based techniques. This  facilitates both statistical inference and rigorous comparisons across regimens. Numerical and graphical comparisons demonstrate that JSTVC accurately captures random effects and outperforms competing methods that ignore IEs or spatiotemporal dependencies in estimating treatment effects and ranking regimens. The proposed methodology provides a broadly applicable framework for modeling complex dependencies in randomized experiments, especially in those involving multiple sequential interventions.
![Figure 1: Ranking treatment strategies for six arms. Left panel: Average Treatment Effect (ATE) calculated as the sum of Direct Effects (DEs) and Indirect Effects (IEs) from the proposed JSTVC. Right panel: Average relative reduction of observed outcomes from Year 1 to Year 5.](/images/profile.png)
<img src="{{ site.baseurl }}/images/profile.png" alt="Figure 1" width="600">

![Figure 2: Spatiotemporal patterns of schistosomiasis prevalence based on the recovered random effects.](/images/Papers/JSTVC-Fig6_Kenya_Wts.jpg)