---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download my full CV [here]({{ base_path }}/files/CV_YifanZhang.pdf).

Education
======
* Ph.D. in Computer Science, University of Texas at Dallas, Aug. 2024 - Present
  * Advisor: Prof. Feng Chen
* M.S. in Computer Science, University of Virginia, Aug. 2022 - Dec. 2023
  * GPA: 3.936/4.0
* B.S. in Computer Science and Technology, Xidian University, Sep. 2018 - Jun. 2022
  * GPA: 3.7/4.0

Research Experience
======
* Research Assistant, AI Safety Lab, UT Dallas, Aug. 2024 - Present
  * Supervisor: Prof. Feng Chen
  * Developed Conditional Contrastive Confidence (C3), a sampling-free uncertainty quantification method for LLMs.
  * Led research conception, method development, experimental design, implementation, analysis, and initial manuscript writing for the C3 project.
  * Took ownership of uncertainty-related experiments for a project on parameter-efficient fine-tuning and hallucination detection in LLMs.

* Master's Student Researcher, University of Virginia, Feb. 2023 - Dec. 2023
  * Supervisor: Prof. Aidong Zhang
  * Studied gradient noise distribution and gradient clipping in federated learning.
  * Validated behavior across ViT, ResNet, heterogeneity levels, participation regimes, and FL algorithms including FedAvg, FedNova, FedProx, and Scaffold.

Skills
======
* Programming: Python, C, SQL; familiar with C++, C#, Java, HTML
* Areas: Machine Learning, Deep Learning, Natural Language Processing, Computer Vision, Convex Optimization
* Languages: Chinese (Native), English (Fluent)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
