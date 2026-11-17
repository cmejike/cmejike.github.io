---
permalink: /
title: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">

<style>
  .home-wrap { max-width: 1000px; margin: 0 auto; font-family: 'Open Sans', sans-serif; color: #222; }
  .home-name { font-family: 'Playfair Display', serif; font-size: 3rem; text-align: center; margin: 1rem 0 3rem; }
  .home-intro { display: flex; gap: 2.5rem; align-items: flex-start; }
  .home-intro img { width: 260px; height: auto; flex-shrink: 0; }
  .home-section h2 { font-size: 1.1rem; font-weight: 600; border: none; margin: 0.5rem 0 1rem; }
  .home-section p, .home-section li { font-size: 0.95rem; line-height: 1.8; }
  .home-section p { margin: 0 0 0.8rem; }
  .home-section ul { margin: 0 0 0.8rem 1.2rem; padding: 0; }
  .home-section li { margin-bottom: 0.3rem; }
  .edu-item { margin-bottom: 1.2rem; }
  .edu-item p { margin: 0; line-height: 1.6; }
  .edu-head { display: flex; justify-content: space-between; font-weight: 600; }
  .home-wrap hr { border: 0; border-top: 2px solid #ddd; margin: 2rem 0; }
  .home-footer { font-family: 'Playfair Display', serif; font-weight: 400; text-align: center; font-size: 0.8rem; line-height: 1.4; margin-top: 2rem; }
  @media (max-width: 700px) {
    .home-intro { flex-direction: column; align-items: center; }
    .home-intro img { width: 200px; }
    .edu-head { flex-direction: column; }
  }
</style>

<div class="home-wrap">

  <h1 class="home-name">Chidera M. Ejike</h1>

  <div class="home-intro">
    <!-- Uses the same photo as your sidebar (avatar in _config.yml) -->
    <img src="{{ '/images/' | append: site.author.avatar | relative_url }}" alt="Chidera M. Ejike">
    <div class="home-section">
      <h2>About me</h2>
      <p>I'm <strong>Chidera M. Ejike</strong>, a PhD student in <strong>Epidemiology</strong> (minor in Biostatistics, graduate certificate in Foundations of Data Science in progress) at the University of Arizona's Mel and Enid Zuckerman College of Public Health, where I also work as a Clinical Research Coordinator in the Department of Epidemiology and Biostatistics. I trained in biotechnology before earning my MPH in Epidemiology at the University of Arizona.</p>
      <p>My work brings together molecular biology and population health. I study post-acute sequelae of SARS-CoV-2 infection (long COVID), especially gastrointestinal outcomes, in the Arizona CoVHORT cohort.</p>
    </div>
  </div>

  <hr>

  <div class="home-section">
    <h2>News</h2>
    <ul>
      <li><strong>Nov 2026</strong> – Co-authored two abstracts presented at APHA 2026, on greenspaces and health and on timely antibiotic care for neutropenic fever in Uganda.</li>
      <li><strong>Jun 2026</strong> – Presented a poster on social support and resilience in long COVID at the SER Annual Meeting (SER Travel Scholarship).</li>
      <li><strong>2026</strong> – Named to the inaugural cohort of the BIO5 Institute Graduate Fellowship in Transdisciplinary Science.</li>
      <li><strong>2026</strong> – Scoping review protocol on photovoice, greenspaces and health published in <em>PLOS ONE</em>.</li>
    </ul>
  </div>

  <hr>

  <div class="home-section">
    <h2>Contact Info</h2>
    <p>&nbsp;&nbsp;&nbsp;<strong>Email</strong>: cmejike@arizona.edu</p>
    <p>&nbsp;&nbsp;&nbsp;<strong>GitHub</strong>: <a href="https://github.com/cmejike">github.com/cmejike</a></p>
    <p>&nbsp;&nbsp;&nbsp;<strong>LinkedIn</strong>: <a href="https://www.linkedin.com/in/chidera-m-ejike-mph-8a406a181/">Chidera M. Ejike</a></p>
  </div>

  <hr>

  <div class="home-section">
    <h2>Education</h2>

    <div class="edu-item">
      <p class="edu-head"><span>Ph.D., Epidemiology (Minor in Biostatistics), University of Arizona</span><span>2025–Present</span></p>
      <p>Foundations of Data Science Graduate Certificate (in progress)</p>
      <p><em>Advisor:</em> Dr. Kristen Pogreba-Brown</p>
    </div>

    <div class="edu-item">
      <p class="edu-head"><span>M.P.H., Epidemiology, University of Arizona</span><span>2024</span></p>
    </div>

    <div class="edu-item">
      <p class="edu-head"><span>B.Sc., Biotechnology, Godfrey Okoye University, Nigeria</span><span>2019</span></p>
      <p>First Class Honors (Summa cum laude)</p>
    </div>
  </div>

  <hr>

  <div class="home-section">
    <h2>Research Interests</h2>
    <ul>
      <li>Long COVID research</li>
      <li>Molecular and microbiome epidemiology</li>
      <li>Food insecurity</li>
      <li>Infectious disease epidemiology</li>
      <li>Social and structural determinants of health</li>
    </ul>
  </div>

  <hr>

  <div class="home-footer">
    Department of Epidemiology and Biostatistics<br>
    University of Arizona<br>
    1295 N. Martin Ave.<br>
    Tucson, AZ 85724
  </div>

</div>
