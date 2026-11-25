---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<div class="research-projects">
  <article class="research-project">
    <div class="research-project__image">
      <img src="{{ base_path }}/images/Papers/JSTVC-Fig4_Ranks.jpg" alt="Ranks of schistosomiasis treatment effects">
    </div>
    <div class="research-project__content">
      <h3>Bayesian inference for complex dependent data</h3>
      <p>I develop Bayesian causal inference methods for spacetime dependent data, where treatment effects may propagate over time and across geographic regions. An example is schistosomiasis research, where direct and indirect effects of mass drug administration inform treatment sequences and elimination strategies.</p>
      <p><strong>Example:</strong> Identifying optimal schistosomiasis treatment sequences for mass drug administration using direct and indirect effects in spatiotemporal trials.</p>
      <p><strong>Collaborators:</strong> Biostatistics, public health, and epidemiology researchers working on schistosomiasis control.</p>
      <p><a href="{{ base_path }}/publication/2025-10-01-JSTVC-number-2" rel="permalink">Continue reading</a></p>
    </div>
  </article>

  <article class="research-project">
    <div class="research-project__image research-project__image--multiple">
      <img src="{{ base_path }}/images/Research/uga_ens.png" alt="Weighted ensemble mean for influenza vaccine response prediction">
      <img src="{{ base_path }}/images/Research/uga_ens_sd.png" alt="Monte Carlo based ensemble standard deviation for influenza vaccine response prediction">
    </div>
    <div class="research-project__content">
      <h3>Predictions</h3>
      <p>I develop predictive models that integrate sparse longitudinal trajectories, ensemble forecasting using Gaussian Markov Random Fields (GMRFs), and interpretable ensemble modeling of complex interactions between demographic factors and historical vaccine antibody titers. These methods enable individualized prediction of influenza vaccine responses and translate complex longitudinal data into clinically actionable insights.</p>
      <p><strong>Example:</strong> Joint modeling and dynamic ensemble forecasting of influenza vaccine responses from complex longitudinal trajectories.</p>
      <p><strong>Collaborators:</strong> Biostatistics and epidemiology researchers studying influenza vaccines.</p>
      <p><a href="{{ base_path }}/publication/2025-11-01-JMDF-number-3" rel="permalink">Continue reading</a></p>
    </div>
  </article>

  <article class="research-project">
    <div class="research-project__image">
      <img src="{{ base_path }}/images/Papers/GeoMap_lc.png" alt="Geographic variation in Long COVID risk assessment">
    </div>
    <div class="research-project__content">
      <h3>Risk assessments</h3>
      <p>I provide novel insights into defining and optimizing exposure windows for risk assessment, leveraging advanced ensemble cross-fitted double/debiased machine learning approaches to improve the quantification of disease burden, identify high-risk populations, and characterize geographic and social disparities. Long COVID research provides an example of how comorbidities and social determinants can be integrated to estimate attributable burden and guide prevention priorities.</p>
      <p><strong>Example:</strong> Comorbidity exposure windows and multidimensional disparities in long COVID risk in a US national cohort.</p>
      <p><strong>Collaborators:</strong> Statistics, public health, epidemiology, and clinical research collaborators using large electronic health record cohorts.</p>
      <p><a href="{{ base_path }}/publication/2027-01-01-LongCOVID-comorbidity" rel="permalink">Continue reading</a></p>
    </div>
  </article>
</div>

<style>
.research-projects {
  margin-top: 1em;
}

.research-project {
  display: grid;
  grid-template-columns: minmax(180px, 28%) 1fr;
  gap: 2em;
  align-items: start;
  margin: 0 0 2.5em;
}

.research-project__image {
  margin-bottom: 0;
}

.research-project__image img {
  display: block;
  width: 100%;
  height: auto;
}

.research-project__image--multiple {
  display: grid;
  grid-template-columns: 1fr;
  gap: 0.75em;
}

.research-project__content h3 {
  margin-top: 0;
  margin-bottom: 0.5em;
  font-size: 1.5em;
}

.research-project__content p {
  margin: 0 0 0.75em;
}

@media screen and (max-width: 600px) {
  .research-project {
    grid-template-columns: 1fr;
    gap: 1em;
  }

}
</style>
