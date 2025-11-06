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
* **M.Sc in Computer Vision**, 2021-2024
  * Technion, Israel Institute of Technology
  * Thesis: "[Estimation of relative position between objects for robotic insertion of LDOs using classification learning methods](/publication/Msc_thesis)"
  * Roland Weil Memorial Prize: for excellence in graduate studies in robotics.
  * Faculty excellence scholarship.
  * Course Average: 91.6, Thesis Grade: 94
  
* **B.Sc in Mechanical Engineering**, 2017-2021
  * Technion, Israel Institute of Technology
  * Specialization: mechanical design and CAD systems.
  * Dean's List for Academic Excellence (Twice).
  * Average: 85.5

Work experience
======
* **Postgraduate Research Intern, Bosch AI**, 2024-2025
  * Research, develop and implement of state of the art algorithms for real-time robotic industrial assembly.
  * Embedding state of the art algorithms on UR5E robotic arms.
  * Development and training of machine learning architectures.
  * Real-time 6D pose estimation for precise robotic manipulation.
  * Behavioral cloning methods for advanced robotic control.

* **Research, Technion Institute of Technology**, 2021-2023
  * Researcher in the ART (assembly by robotic technology) - Israel Innovations Authority program.
  * Implementation of machine learning vision algorithm for flexible objects.
  * Object classification from RGB-D images.
  * Data-set acquiring and labeling process design.
  * Implementing the developed tools in the robotic cell at Polygon.

* **Research and Development, Rafael**, 2019-2021
  * Research and development of defense systems.
  * Development and design of mechanical components.
  * Troubleshooting and providing solutions.
  * Production planning with CNC, tin bending, laser cutting, and 3D printing.

* **Mandatory Service, IDF Air Force**, 2012-2015
  * Full-service, Active reserve duty
  
Skills
======
* **Professional Knowledge**
  * Computer vision
  * Deep learning
  * Robotics
  * Machine learning
  * CAD systems
  * 3D printing
* **Software Knowledge**
  * **Computer Vision:** OpenCV, Open3D
  * **Machine Learning:** Pytorch, TensorFlow
  * **Programming:** Python, Matlab, C
* **Languages**
  * Hebrew - Native Language
  * English - Proficient

Publications
======
* **Papers**
  <ul>
  {% for post in site.publications reversed %}
    {% if post.type == "Paper" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
  </ul>

* **Patents**
  <ul>
  {% for post in site.publications reversed %}
    {% if post.type == "Patent" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
  </ul>

* **Posters & Presentations**
  <ul>
  {% for post in site.publications reversed %}
    {% if post.type == "Poster" or post.type == "Demo" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
  </ul>