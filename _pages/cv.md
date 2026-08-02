---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF version]({{ base_path }}/files/CV.pdf)

Education
======
* M.S. in Agricultural and Biological Engineering, University of Florida, 2025 - 2027 (Expected)
* B.S. in Biosystems Engineering, Chonnam National University, 2021 - 2025

Experience
======
* May 2025 - Present: Graduate Research Assistant
  * University of Florida
  * USDA Robotics Strawberry Harvesting Project, Precision Agriculture Lab, in collaboration with Purdue University
  * Advisor: [Prof. Won Suk Lee](https://abe.ufl.edu/people/faculty/wonsuk-lee/)
  * Collected the first real-world 6D pose ground truth dataset of strawberries in agricultural fields and constructed a scene-level realistic synthetic dataset using NVIDIA Isaac Sim
  * Evaluated baseline 6D pose estimation models and analyzed the sim-to-real gap in agricultural field conditions

* Spring 2024: Teaching Assistant, Computer Programming
  * Chonnam National University
  * Assisted undergraduate students in C++, MATLAB, and Simulink

Skills
======
* Programming: Python, C++
* Libraries: PyTorch, OpenCV, Open3D, Hugging Face Transformers
* Tools: Git, SLURM, LaTeX, NVIDIA Isaac Sim, COLMAP

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Presentations
======
* Woojung Son et al., "Geometry-Grounded Transformer-Based Monocular 6D Pose Estimation for Robotic Strawberry Harvesting via Sim-to-Real Transfer," American Society of Agricultural and Biological Engineers (ASABE) Annual International Meeting, Indianapolis, IN, 2026. (Oral)

Honors and Awards
======
* Graduate Assistantship (Full Funding), University of Florida, 2025 - 2027
* 1st Place, AKABFE Student Paper Competition, ASABE Annual International Meeting, 2026
