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
      <h3>Causal inference in dependent data</h3>
      <p>I develop causal inference methods for dependent and spatiotemporal data, where treatment effects may propagate through networks and across geographic regions. An example is schistosomiasis research, where direct and indirect effects of mass drug administration inform treatment sequences and elimination strategies.</p>
      <p><strong>Example:</strong> Identifying optimal schistosomiasis treatment sequences for mass drug administration using direct and indirect effects in spatiotemporal trials.</p>
      <p><strong>Collaborators:</strong> Public health and epidemiology researchers working on schistosomiasis control.</p>
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
      <p>I develop practical predictive models that combine longitudinal trajectories, ensemble forecasting, and interpretable risk scores. These methods support individualized prediction of influenza vaccine responses and help translate complex repeated measurements into useful clinical tools.</p>
      <p><strong>Example:</strong> Joint modeling and dynamic ensemble forecasting of influenza vaccine responses from complex longitudinal trajectories.</p>
      <p><strong>Collaborators:</strong> Epidemiology and biostatistics researchers studying influenza vaccines.</p>
      <p><a href="{{ base_path }}/publication/2025-11-01-JMDF-number-3" rel="permalink">Continue reading</a></p>
    </div>
  </article>

  <article class="research-project">
    <div class="research-project__image">
      <img src="{{ base_path }}/images/Papers/GeoMap_lc.png" alt="Geographic variation in Long COVID risk assessment">
    </div>
    <div class="research-project__content">
      <h3>Risk assessments</h3>
      <p>I develop risk assessment methods to quantify disease burden, identify high-risk populations, and characterize geographic and social disparities. Long COVID research provides an example of how comorbidities and social determinants can be integrated to estimate attributable burden and guide prevention priorities.</p>
      <p><strong>Example:</strong> Long COVID burden attributable to preexisting comorbidity: a retrospective cohort study.</p>
      <p><strong>Collaborators:</strong> Public health, epidemiology, and clinical research collaborators using large electronic health record cohorts.</p>
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

.research-project__image img {
  display: block;
  width: 100%;
  height: auto;
}

.research-project__image--multiple {
  display: grid;
  gap: 0.75em;
}

.research-project__content h3 {
  margin-top: 0;
  margin-bottom: 0.5em;
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
