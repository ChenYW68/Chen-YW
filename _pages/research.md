---
layout: archive
title: "Research projects"
permalink: /research/
author_profile: true
---

{% include base_path %}

<div class="research-projects">
  <article class="research-project">
    <div class="research-project__image">
      <img src="{{ base_path }}/images/Research/R1.png" alt="Bayesian inference for schistosomiasis treatment effects">
    </div>
    <div class="research-project__content">
      <h3>Bayesian inference for complex dependent data</h3>
      <p>Focusing on developing Bayesian statistical methods for inference and causal effect estimation in complex dependent data, particularly those exhibiting spatial, temporal, and spatiotemporal dependence. The overarching goal is to characterize dependence structures, quantify uncertainty, and estimate direct and indirect effects while accounting for heterogeneity and potential interference across observational units.</p>
      <p><strong>Example:</strong> Identifying effective schistosomiasis treatment sequences for mass drug administration in spatiotemporal trials, early detection of disease hotspots, and characterization of their spatiotemporal evolution.</p>
      <p><strong>Collaborators:</strong> Biostatistics, public health, and epidemiology researchers working on schistosomiasis control.</p>
      <p><a href="{{ base_path }}/publication/2025-10-01-JSTVC-number-2" rel="permalink">Continue reading</a></p>
    </div>
  </article>

  <article class="research-project">
    <div class="research-project__image">
      <img src="{{ base_path }}/images/Research/R2.png" alt="Predictive models for influenza vaccine response prediction">
    </div>
    <div class="research-project__content">
      <h3>Development of predictive models for longitudinal, spatial, and spatiotemporal data</h3>
      <p> Focusing on developing advanced Gaussian process inference methods for modeling complex longitudinal, spatial, and spatiotemporal data, with an emphasis on capturing complex dependence structures, nonlinear interactions, and individual heterogeneity. The overarching goal is to improve predictive accuracy, robustness, and uncertainty quantification, with applications in public health, environmental sciences, and precision medicine. </p>
      <p><strong>Example:</strong> Air pollution concentration calibration and prediction, and individualized prediction of influenza vaccine responses.</p>
      <p><strong>Collaborators:</strong> Biostatistics and epidemiology researchers studying influenza vaccines.</p>
      <p><a href="{{ base_path }}/publication/2025-11-01-JMDF-number-3" rel="permalink">Continue reading</a></p>
    </div>
  </article>

  <article class="research-project">
    <div class="research-project__image">
      <img src="{{ base_path }}/images/Research/R3.png" alt="Geographic variation in Long COVID risk assessment">
    </div>
    <div class="research-project__content">
      <h3>Risk assessment and multidimensional heterogeneity in chronic diseases</h3>
      <p>Focusing on developing advanced ensemble double/debiased machine learning methods for risk assessment and disease burden quantification, with an emphasis on defining and optimizing exposure windows, estimating attributable risks, and characterizing complex interactions and population heterogeneity. The overarching goal is to improve the identification of high-risk populations, quantify the contributions of multiple risk factors, and characterize geographic and social disparities to inform targeted prevention strategies.</p>
      <p><strong>Example:</strong> Comorbidity exposure windows and multidimensional disparities in long COVID risk in a US national cohort.</p>
      <p><strong>Collaborators:</strong> Statistics, public health, epidemiology, and clinical research collaborators using large electronic health record cohorts.</p>
      <p><a href="{{ base_path }}/publication/" rel="permalink">Continue reading</a></p>
    </div>
  </article>

  <article class="research-project">
    <div class="research-project__image">
      <img src="{{ base_path }}/images/Research/R4.png" alt="Single-cell and spatial transcriptomics analysis">
    </div>
    <div class="research-project__content">
      <h3>Single-cell and spatial transcriptomics data analysis</h3>
      <p>Focusing on developing scalable spatially varying coefficient methods and multi-stage estimation algorithms for single-cell and spatial transcriptomics data, with an emphasis on characterizing localized associations between macrophage abundance and ERBB2 expression, accounting for spatial confounding, and quantifying heterogeneity across biologically distinct tissue compartments. The overarching goal is to identify reproducible tumor microenvironment patterns, improve inference on spatially heterogeneous associations, and generate high-resolution spatial surfaces that reveal where local biological features are associated with tumor-related gene expression.</p>
      <p><strong>Example:</strong> Characterizing spatially varying associations between macrophage abundance and ERBB2 expression, identifying localized tumor microenvironment patterns, and quantifying cellular heterogeneity across distinct tissue compartments, etc.</p>
      <p><strong>Collaborators:</strong> Biostatistics, computational biology, bioinformatics, cancer biology, pathology, and oncology using Xenium or CosMx datasets.</p>
      <p><a href="#" rel="permalink">Continue reading</a></p>
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
