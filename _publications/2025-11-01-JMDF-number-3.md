---
title: "Joint modeling and dynamic ensemble forecasting of influenza vaccine responses from complex longitudinal trajectories"
collection: publications
category: conferences
permalink: /publication/2025-11-01-JMDF-number-12
excerpt: 'This paper developed a novel joint modeling and dynamic ensemble forecasting method.'
date: 2025-11-01
venue: 'Peer review'
slidesurl: 'https://chenyw68.github.io/Chen-YW/files/Predicting influenza vaccine-elicited antibody responses with practical point system.pdf'
paperurl: 'https://chenyw68.github.io/Chen-YW/files/Predicting influenza vaccine-elicited antibody responses with practical point system.pdf'
bibtexurl: 'https://chenyw68.github.io/Chen-YW/files/Shen2025predicting.bib'
citation: 'Chen Y, Zhang Y, and Shen Y. (2025). &quot;Joint modeling and dynamic ensemble forecasting of influenza vaccine responses from complex longitudinal trajectories.&quot; <i>Peer review</i>.'
---

Longitudinal measurement trajectories have become increasingly valuable for deepening the predictive understanding of vaccine-induced immunity. However, the complexity of immune interaction patterns inherent in these trajectories, along with their incompleteness and high heterogeneity, introduces methodological challenges for predictive modeling. To this end, we introduce the Joint Modeling and Dynamic Forecasting (JMDF) framework to enhance influenza vaccine response prediction. JMDF provides four key advances. First, it adaptively incorporates non-missing trajectories as covariates without requiring imputation. Second, it applies Gaussian Markov Random Fields (GMRFs) to enable information sharing across individuals, achieving efficient modeling and interpretation of complex interactions. Third, it achieves joint forecasting by leveraging deep within-individual dependencies across viral subtypes. Fourth, it facilitates robust ensemble forecasting by integrating vaccination trajectory patterns. To support scalable inference with large and complex datasets, we develop an ensemble algorithm based on Integrated Nested Laplace Approximation. Simulations demonstrate JMDF's efficiency in estimation and prediction, even under model misspecifications. Applied to an eleven-year influenza vaccine cohort (2013–2023), JMDF improves predictive performance while uncovering interpretable links between vaccination histories and immune responses. These insights support data-driven vaccine formulation. Overall, JMDF provides an adaptable, generalizable predictive modeling framework for real-world applications, particularly with incomplete trajectories and heterogeneous interactions.

<figure id="Figure1">
  <table align="center">
    <tr>
      <td><img src="https://chenyw68.github.io/Chen-YW/images/Papers/JMDF-Fig0.jpg" width="500px"></td>
    </tr>
  </table>
  <figcaption align="center">
    <strong>Figure 1:</strong> Incomplete longitudinal trajectories of pre- and post-vaccination HAI titers collected from 30 randomly selected participants over eleven years.
  </figcaption>
</figure>

<figure id="Figure2">
  <table align="center">
    <tr>
      <td><img src="https://chenyw68.github.io/Chen-YW/images/Papers/Fig5_1.jpg" width="500px"></td>
      <td><img src="https://chenyw68.github.io/Chen-YW/images/Papers/Fig5_2.jpg" width="500px"></td>
    </tr>
    <tr>
      <td><img src="https://chenyw68.github.io/Chen-YW/images/Papers/Fig5_3.jpg" width="500px"></td>
      <td><img src="https://chenyw68.github.io/Chen-YW/images/Papers/Fig5_4.jpg" width="500px"></td>
    </tr>
  </table>
  <figcaption align="center">
    <strong>Figure 2:</strong> The interaction effects between human age and historical longitudinal pre-vaccination HAI titers on future vaccination responses.
  </figcaption>
</figure>