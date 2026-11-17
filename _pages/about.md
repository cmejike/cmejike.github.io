---
permalink: /
title: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}
{% assign author = site.author %}

<div class="home-wrap">

<h1 class="home-name">Chidera M. Ejike</h1>

<div class="home-intro">
  <div class="home-profile">
    <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="Chidera M. Ejike">
    <ul class="home-links">
      {% if author.location %}<li><i class="fas fa-fw fa-location-dot" aria-hidden="true"></i>{{ author.location }}</li>{% endif %}
      {% if author.employer %}<li><i class="fas fa-fw fa-building-columns" aria-hidden="true"></i>{{ author.employer }}</li>{% endif %}
      {% if author.email %}<li><a href="mailto:{{ author.email }}"><i class="fas fa-fw fa-envelope" aria-hidden="true"></i>Email</a></li>{% endif %}
      {% if author.orcid %}<li><a href="{{ author.orcid }}"><i class="ai ai-orcid ai-fw" aria-hidden="true"></i>ORCID</a></li>{% endif %}
      {% if author.pubmed %}<li><a href="{{ author.pubmed }}"><i class="ai ai-pubmed ai-fw" aria-hidden="true"></i>PubMed</a></li>{% endif %}
      {% if author.github %}<li><a href="https://github.com/{{ author.github }}"><i class="fab fa-fw fa-github" aria-hidden="true"></i>GitHub</a></li>{% endif %}
      {% if author.linkedin %}<li><a href="https://www.linkedin.com/in/{{ author.linkedin }}"><i class="fab fa-fw fa-linkedin" aria-hidden="true"></i>LinkedIn</a></li>{% endif %}
    </ul>
  </div>
  <div class="home-about">
    <h2>About me</h2>
    <p>I'm <strong>Chidera M. Ejike</strong>, a PhD student in <strong>Epidemiology</strong> (minor in Biostatistics, graduate certificate in Foundations of Data Science in progress) at the University of Arizona's Mel and Enid Zuckerman College of Public Health, where I also work as a Clinical Research Coordinator in the Department of Epidemiology and Biostatistics. I trained in biotechnology before earning my MPH in Epidemiology at the University of Arizona.</p>
    <p>My work brings together molecular biology and population health. I study post-acute sequelae of SARS-CoV-2 infection (long COVID), especially gastrointestinal outcomes, in the Arizona CoVHORT cohort.</p>
  </div>
</div>

<h2>News</h2>
<ul>
  <li><strong>Nov 2026</strong> – Co-authored two abstracts presented at APHA 2026, on greenspaces and health and on timely antibiotic care for neutropenic fever in Uganda.</li>
  <li><strong>Sep 2026</strong> – Named to the inaugural cohort of the BIO5 Institute Graduate Fellowship in Transdisciplinary Science.</li>
  <li><strong>Aug 2026</strong> – Scoping review protocol on photovoice studies concerning greenspaces and health published in <em>PLOS ONE</em>.</li>
  <li><strong>Jun 2026</strong> – Presented a poster on social support and resilience in long COVID at the SER Annual Meeting (SPC Travel Scholarship).</li>
</ul>

<h2>Education</h2>
{% include education.html %}

<h2>Research Interests</h2>
<ul>
  <li>Long COVID research</li>
  <li>Molecular and microbiome epidemiology</li>
  <li>Food insecurity</li>
  <li>Infectious disease epidemiology</li>
  <li>Social and structural determinants of health</li>
</ul>

<div class="home-footer">
  Department of Epidemiology and Biostatistics<br>
  University of Arizona<br>
  1295 N. Martin Ave.<br>
  Tucson, AZ 85724
</div>

</div>
