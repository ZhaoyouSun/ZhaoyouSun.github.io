---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

*A printable PDF version of my CV can be downloaded [here](#).*

---

## 🎓 Education

* **Visiting Scholar**, *Kyoto University* <span style="float: right;">2026 – Present</span>
* **Ph.D. in Mechanics**, *Harbin Institute of Technology (Shenzhen)* <span style="float: right;">2023 – 2027 (Expected)</span>
* **M.S. in Aeronautical Science and Technology**, *Dalian University of Technology* <span style="float: right;">2020 – 2023</span>
* **B.S. in Aircraft Manufacturing Engineering**, *Nanchang Hangkong University* <span style="float: right;">2016 – 2020</span>

## 💼 Work Experience

* **Algorithmic Engineer (Intern)**, *HeyGears Technology Co., Ltd*, Guangzhou <span style="float: right;">Spring 2023</span>
  * Focused on developing and implementing topology optimization algorithms for advanced 3D printing applications.

## 🔬 Research Projects

* **Principal Investigator**, *National Natural Science Foundation of China (NSFC) Student Research Project* * Addressed key scientific problems in structural design and optimization.

## 🛠️ Skills & Expertise

* **Research Domains:** Computational mechanics, topology optimization, multiscale design, and non-linear thermomechanical coupling (e.g., non-linear heat conduction with temperature-dependent properties).
* **Technical Methodologies:** Finite Element Method (FEM) implementations, including applying Saint Venant-Kirchhoff constitutive models under plane strain assumptions.
* **Programming & Tools:** Advanced MATLAB (custom non-linear solvers, sensitivity analysis, and high-resolution 3D voxelization visualizations), LaTeX (professional CMAME-style manuscript preparation).
* **Personal Traits:** Passionate about producing interesting works, and keeping happy every day! 😊

## 📚 Publications

<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>
