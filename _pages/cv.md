---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p style="text-align:center; margin: 1rem 0 2rem;">
  <a class="btn btn--primary btn--large"
     href="https://www.overleaf.com/read/mxhvvwvrkrsn?pdf=1"
     target="_blank" rel="noopener">
    📄 Download Full CV (PDF)
  </a>
</p>

Education
======
* **Ph.D. in Electrical and Computer Engineering**, Sungkyunkwan University (SKKU), Korea — *Expected 2026*  
  Advisor: Prof. Kim | Research: Distributed RIS-MIMO, Adversarial Attacks & Defenses, 6G ISAC  
* **M.S. in Electronics & Telecommunications**, Hanoi University of Science and Technology (HUST), Vietnam — *2022*  
  Thesis: Intelligent reflecting surfaces for wireless security  
* **B.S. in Electronics & Telecommunications**, HUST — *2020*

Work Experience
======
* **Research Assistant**, SKKU, 2023–Present  
  * Conducting research on RIS-assisted MIMO systems, federated learning, and adversarial training  
  * Developing large-scale MATLAB/PyTorch simulation pipelines for double-scattering channels  
  * Co-authoring IEEE TCOM and TWC submissions  
* **Research Assistant**, HUST, 2020–2022  
  * Assisted in national research project on 5G/6G intelligent surfaces  
  * Designed experiments, supervised undergraduate projects  

Skills
======
* **Wireless Communication:** RIS, MIMO, ISAC, CDL/Rician channel modeling  
* **Machine Learning:** PyTorch, Federated Learning, Adversarial Training (FGM, PGD, UAP)  
* **Programming:** MATLAB (5G Toolbox), Python, Git/GitHub  
* **Technical Writing:** IEEE papers, LaTeX (Overleaf), academic responses to reviewers  

Publications
======
<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

Talks
======
<ul>
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
</ul>

Teaching
======
<ul>
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

Service & Leadership
======
* Reviewer for IEEE Transactions on Communications, IEEE Internet of Things Journal  
* Mentor for undergraduate research assistants at SKKU  
* Member of multiple academic Slack/Discord research communities
