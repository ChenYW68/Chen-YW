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
      <p>Focusing on developing Bayesian statistical methods for inference and causal effect estimation in complex dependent data, particularly those exhibiting spatial, temporal, and spatiotemporal dependence. The overarching goal is to characterize dependence structures, quantify uncertainty, and estimate direct and indirect effects while accounting for heterogeneity and potential interference across observational units.</p>
      <p><strong>Example:</strong> Identifying effective schistosomiasis treatment sequences for mass drug administration in spatiotemporal trials, early detection of disease hotspots, and characterization of their spatiotemporal evolution.</p>
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
      <h3>Development of predictive models for longitudinal, spatial, and spatiotemporal data</h3>
      <p> Focusing on developing advanced Gaussian process inference methods for modeling complex longitudinal, spatial, and spatiotemporal data, with an emphasis on capturing complex dependence structures, nonlinear interactions, and individual heterogeneity. The overarching goal is to improve predictive accuracy, robustness, and uncertainty quantification, with applications in public health, environmental sciences, and precision medicine. </p>
      <p><strong>Example:</strong> Air pollution concentration calibration and prediction, and individualized prediction of influenza vaccine responses.</p>
      <p><strong>Collaborators:</strong> Biostatistics and epidemiology researchers studying influenza vaccines.</p>
      <p><a href="{{ base_path }}/publication/2025-11-01-JMDF-number-3" rel="permalink">Continue reading</a></p>
    </div>
  </article>

  <article class="research-project">
    <div class="research-project__image">
      <img src="{{ base_path }}/images/Papers/GeoMap_lc.png" alt="Geographic variation in Long COVID risk assessment">
    </div>
    <div class="research-project__content">
      <h3>Risk assessments and multidimensional heterogeneities</h3>
      <p>Focusing on developing advanced ensemble double/debiased machine learning methods for risk assessment and disease burden quantification, with an emphasis on defining and optimizing exposure windows, estimating attributable risks, and characterizing complex interactions and population heterogeneity. The overarching goal is to improve the identification of high-risk populations, quantify the contributions of multiple risk factors, and characterize geographic and social disparities to inform targeted prevention strategies.</p>
      <p><strong>Example:</strong> Comorbidity exposure windows and multidimensional disparities in long COVID risk in a US national cohort.</p>
      <p><strong>Collaborators:</strong> Statistics, public health, epidemiology, and clinical research collaborators using large electronic health record cohorts.</p>
      <p><a href="{{ base_path }}/publication/2027-01-01-LongCOVID-comorbidity" rel="permalink">Continue reading</a></p>
    </div>
  </article>

  <article class="research-project">
    <div class="research-project__image research-project__image--multiple">
      <img src="{{ base_path }}/images/Research/cellular_neighborhood.png" alt="Cellular neighborhoods in spatial transcriptomics data">
      <img src="{{ base_path }}/images/Research/S2-Bottom%20(HER2%203%2B)_sample.png" alt="Sample spatial transcriptomics image from a HER2 3+ tumor section">
      <img src="{{ base_path }}/images/Research/S2-Bottom%20(HER2%203%2B).png" alt="Spatial transcriptomics image from a HER2 3+ tumor section">
    </div>
    <div class="research-project__content">
      <h3>Single-cell and spatial transcriptomics data analysis</h3>
      <p>I develop spatially varying coefficient methods for single-cell and spatial transcriptomics data to connect local cellular neighborhoods with gene expression and tumor microenvironment biology.</p>
      <p><strong>Research questions:</strong></p>
      <ul>
        <li>Do macrophage-rich neighborhoods correspond to localized ERBB2-high or ERBB2-low tumor subpopulations?</li>
        <li>Does the direction and magnitude of spatially heterogeneous associations vary systematically across biologically distinct tissue compartments, and are these patterns reproducible?</li>
        <li>How do local biological features contribute to spatial confounding and affect inference on spatially varying coefficients?</li>
      </ul>
      <p><strong>Interpretation:</strong></p>
      <ul>
        <li>The estimated coefficients identify locations within the tumor microenvironment where local macrophage abundance is associated with ERBB2 expression and quantify the magnitude of that association.</li>
        <li>Higher ERBB2 transcript counts alone do not necessarily indicate increased tumor aggressiveness.</li>
        <li>Regions with positive coefficients exhibit HER2-related tumor biological characteristics, where HER2 plays a role in regulating cell growth and proliferation.</li>
      </ul>
      <p><strong>Methodological contributions:</strong></p>
      <ul>
        <li><strong>Computational efficiency:</strong> SEVI provides a scalable framework for modeling spatially varying coefficients through multi-stage estimation for large-scale datasets.</li>
        <li><strong>Spatial confounding:</strong> Multi-stage estimation can mitigate spatial confounding and improve estimation of spatially heterogeneous associations.</li>
        <li><strong>Biological applications:</strong> The method provides high-resolution spatial surfaces for investigating where and under what tumor microenvironment conditions macrophage abundance is associated with ERBB2 expression.</li>
        <li><strong>Biological insights:</strong> The analysis characterizes spatial heterogeneity in macrophage–tumor associations and may reveal tissue-dependent relationships across distinct tumor microenvironments.</li>
      </ul>
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
