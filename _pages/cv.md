---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My research expertise lies in developing advanced statistical methodologies and computationally efficient algorithms for modeling and analyzing complex dependent data, with a particular emphasis on interdisciplinary applications in public health, environmental science, biological sciences, and related fields.

Education and Professional Experience
======

**November 2026 – Present**<br>
Assistant Research Scientist<br>
Department of Epidemiology and Biostatistics, University of Georgia, USA

**December 2023 – November 2026**<br>
Postdoctoral Research Associate<br>
Department of Epidemiology and Biostatistics, University of Georgia, USA

**September 2018 – August 2023**<br>
Ph.D. in Statistics<br>
School of Mathematics, Sun Yat-sen University, China

<!--
Education
======
* **09/2018 – 08/2023:** Ph.D. in Statistics, Sun Yat-sen University, China  
  Advisor: <a href="https://www.researchgate.net/profile/Hui-Huang-92" target="_blank">Prof. Hui Huang</a><br>
  Dissertation: *Several Problems in Modeling Complex SpatioTemporal Data*

Experience
======
* **12/2023 – present:** Postdoctoral Associate
  * Epidemiology and Biostatistics, University of Georgia, USA
  * Supervisor: <a href='https://www.researchgate.net/profile/Ye-Shen-2' target='_blank'> Prof. Ye Shen</a>

* **07/2016 – 07/2018:** Faculty
  * Guizhou Minzu University, China
  * Achievement: In November 2017, a team under my guidance won the second prize in the National College Student Mathematical Modeling Competition

* **10/2015 – 01/2016:** Internship
  * SAS Institute Inc., Guangzhou, China
  * Developing prediction models of Biostime infant milk

Award
======
* The second prize (Outstanding paper): 6th National Forum for Statistics Ph.D. Candidate (11-2022)
* The third Prize (National Statistics Modeling Competition): Big Data Modeling Group  (11-2015)
* The first prize (Mathematical Modeling Competition): 4th Shenzhen Cup for Forecasting Potential Flood Losses in Shenzhen (08-2014)
-->

Academic Interest
======
* Bayesian predictive modeling, particularly for influenza vaccine antibody responses and air pollution concentration prediction and calibration
* Development of computationally efficient algorithms, including variational Bayes and ensemble learning methods
* Semiparametric and nonparametric statistical modeling, including kernel regression and double/debiased machine learning
* Change-point detection and spatiotemporal modeling, with applications to DNA copy number variation and spatial transcriptomics data
* Disease risk assessment associated with preexisting health conditions and socioenvironmental factors, with a particular focus on Long COVID
* Interdisciplinary applications in infectious and chronic diseases, including schistosomiasis, influenza, and dementia

Review Activity 
======
* Applied Soft Computing
* PLOS Neglected Tropical Diseases
* Computational Statistics & Data Analysis
* Aerosol and Air Quality Research
* Biostatistics & Epidemiology
* BMC Public Health
* Public Policy Journal
* ...

<!--
Skills
======
R, C++, SQL, Matlab, SAS
-->

Research Paper
======
<p><em>* denotes corresponding author</em></p>
<h3 class="cv-subsection-title cv-subsection-title--first">First-author publications &amp; Manuscripts under review</h3>
  {% assign selected_papers = site.publications | where: "cv_selected", true %}
  {% assign counter = selected_papers | size %}
  {% assign status_order = "peer_review,third_round_revision,second_round_revision,first_round_revision,accepted,published" | split: "," %}
  <ul class="cv-publications">{% for status in status_order %}{% assign status_papers = selected_papers | where: "cv_status", status %}{% for post in status_papers reversed %}
    <div class="publication-item">
      <span class="publication-number">({{ counter }})</span>
      {% include archive-single-cv-citation.html %}
    </div>
    {% assign counter = counter | minus: 1 %}
  {% endfor %}{% endfor %}</ul>

<h3 class="cv-subsection-title">Statistics &amp; Methodology (Co-authored)</h3>
  {% assign methodology_papers = site.publications | where: "cv_section", "methodology" | where_exp: "post", "post.cv_selected != true" %}
  {% assign counter = methodology_papers | size %}
  {% assign status_order = "peer_review,third_round_revision,second_round_revision,first_round_revision,accepted,published" | split: "," %}
  <ul class="cv-publications">{% for status in status_order %}{% assign status_papers = methodology_papers | where: "cv_status", status %}{% for post in status_papers reversed %}
    <div class="publication-item">
      <span class="publication-number">({{ counter }})</span>
      {% include archive-single-cv-citation.html %}
    </div>
    {% assign counter = counter | minus: 1 %}
  {% endfor %}{% endfor %}</ul>

<h3 class="cv-subsection-title">Public Health &amp; Epidemiology (Co-authored)</h3>
  {% assign collaboration_papers = site.publications | where: "cv_section", "collaboration" | where_exp: "post", "post.cv_selected != true" %}
  {% assign counter = collaboration_papers | size %}
  <ul class="cv-publications">{% for status in status_order %}{% assign status_papers = collaboration_papers | where: "cv_status", status %}{% for post in status_papers reversed %}
    <div class="publication-item">
      <span class="publication-number">({{ counter }})</span>
      {% include archive-single-cv-citation.html %}
    </div>
    {% assign counter = counter | minus: 1 %}
  {% endfor %}{% endfor %}</ul>

<style>
.cv-subsection-title {
  margin-top: 3em !important;
  margin-bottom: 0em !important;
}

.cv-subsection-title--first {
  margin-top: 0.5em !important;
}

.cv-publications {
  margin-top: 0 !important;
  padding-top: 0 !important;
}

.publication-item {
  display: flex;
  align-items: baseline;
  margin-bottom: -1em !important;
  padding-bottom: 0 !important;
}

.publication-number {
  font-weight: bold;
  margin-right: 5px;
  flex-shrink: 0;
  min-width: 25px;
}

.publication-item li {
  list-style: none;
}
</style>
  
<!--Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
