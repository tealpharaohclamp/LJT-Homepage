---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Science** (2024–Present) — Hong Kong University of Science and Technology (HKUST), HKUST NLP Group. *Supervisor: Professor Junxian He.*
* **B.Eng. in Computer Science** (2020–2024) — Shanghai Jiao Tong University (SJTU). *Zhiyuan Honor Scholarship.*

Work experience
======
* **Research Intern** (Feb 2025 – Present) — MINIMAX.
* **Research Intern** (Jun 2024 – Sep 2024) — Tencent WXG. *Advisor: Zifei Shan.*
* **Research Intern** (Jun 2023 – Dec 2023) — Shanghai AI Lab. *Advisor: Prof. Yu Cheng.*

Skills
======
* Programming & Deep Learning: Python, PyTorch
* Machine Learning & NLP: Natural Language Processing, Large Language Models, Reinforcement Learning, Vision-Language Models, Interpretability

Publications
======
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}

Talks
======
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}

Teaching
======
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
