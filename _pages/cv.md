---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/Ejike_CV.pdf" class="btn" download>Download CV (PDF)</a>

Honors and awards
======
* BIO5 Institute Graduate Fellowship in Transdisciplinary Science (inaugural cohort), University of Arizona, 2026
* Zuckerman Family Foundation Scholarship Endowment, 2026
* SER Travel Scholarship, Society for Epidemiologic Research Annual Meeting, 2026
* AZHEC Scholarship Award, Arizona Health Equity Conference, 2025
* Roots for Resilience Fellowship, CyVerse and Data Science Institute, University of Arizona, 2025
* College of Public Health Advisory Board Scholarship, 2025
* College of Public Health General Scholarship, 2022
* Graduate College Award for academic excellence and dedication, University of Arizona, 2022
* Best Graduating Student Award, Biotechnology Program, Godfrey Okoye University, 2019

Research and professional experience
======
* **Clinical Research Coordinator I** - Department of Epidemiology and Biostatistics, University of Arizona, 2025-present
  * Lead research coordination and study operations for the CoVHORT-GI R01 project
  * Participant engagement, data management and quality control, and biospecimen preparation, tracking and shipment
  * Contribute to analyses of PASC-related GI symptoms, post-infectious IBS, and Rome IV vs self-reported outcome ascertainment
* **Research Support (part-time)** - Fred Hutchinson Cancer Center, 2026-present
  * Qualitative implementation study at the Uganda Cancer Institute on timely antibiotics for neutropenic fever (Theoretical Domains Framework)
  * Analysis of barriers to infection diagnosis and treatment among patients with cancer living with HIV
* **Volunteer Researcher** - Southwest Center on Resilience for Climate & Health (SCORCH), University of Arizona, 2025-present
  * Lead community-engaged photovoice and scoping-review research on greenspaces and health in Southern Arizona
* **Contract STI Epidemiologist** - Pima County Department of Public Health, 2026
  * Built a data dictionary and reproducible R workflows for the congenital syphilis registry; descriptive and trend analyses
* **Research Program Administration Officer I** - Department of Epidemiology and Biostatistics, University of Arizona, 2024-2025
  * Coordinated a virtual public health surveillance laboratory; supervised and trained student case investigators
* **Graduate Research Assistant** - Student Aid for Epidemiology Response Team, University of Arizona, 2023-2024
  * Case investigation and contact tracing using REDCap, Qualtrics and Trellis
* **Graduate Research Assistant** - CoVHORT-GI Project, University of Arizona, 2023-2024
* **Research Intern** - Laboratory of Pathogenesis of Clinical Drug Resistance and Persistence, San Diego State University, 2022-2023
  * Pyrazinamide-resistant tuberculosis analyses leading to a peer-reviewed publication
* **Research Coordinator** - DNA Learning Center Nigeria, Godfrey Okoye University, 2021-2022
  * Coordinated DNA barcoding, metagenomics and bioinformatics research and training
  * Led the Back-to-Science Initiative (BATOSCIN), training about 200 secondary-school students
  * Supported the Nigerian ant barcode project with Cold Spring Harbor Laboratory DNA Learning Center
* **Intern, National Youth Service Corps** - Ministry of Science and Technology, Bayelsa State, 2019-2021
* **Undergraduate Intern** - National Center for Genetic Resources and Biotechnology (NACGRAB), 2018

Skills
======
* **Research methods:** longitudinal and cohort study design; quantitative data management and analysis; biospecimen-based research coordination; community-engaged and qualitative methods (photovoice); scoping reviews
* **Software:** R and RStudio (cleaning, analysis, visualization, reproducible workflows); REDCap, Qualtrics, MEDSIS, Trellis; Microsoft Office; Canva
* **Laboratory:** PCR and primer optimization; agarose gel electrophoresis; DNA barcoding; biospecimen preparation, tracking and shipment; plant tissue culture
* **Certifications:** CITI Biomedical Research Investigators training (2023-2027); Applied AI in Public Health Practice, University of Arizona (2026)

Leadership and service
======
* Officer, AI and Public Health Student Club, University of Arizona, 2026-present
* Invited Peer Reviewer, *BMJ Public Health*, 2026
* Peer Reviewer, Arizona Investigator Grant Program (RFGA2024-022), Arizona Biomedical Research Centre, 2024
* Public Health Navigator (volunteer), Health Companions Clinics, Pima County Health, 2024-present
* Graduate Student Ambassador, Mel and Enid Zuckerman College of Public Health, 2023-present
* Graduate Student Representative, Epidemiology Program, University of Arizona, 2023-2024

Publications
======
{% for post in site.publications reversed %}
  {% include publication-item.html %}
{% endfor %}
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
