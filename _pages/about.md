---
layout: about
title: about
permalink: /
subtitle: Ph.D. Candidate, <a href='https://www.unist.ac.kr/'>UNIST</a> · Deep Learning × Structural &amp; Seismic Engineering

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Dept. of Civil, Urban, Earth &amp; Environmental Engineering</p>
    <p>Advisor: Prof. Young-Joo Lee</p>
    <p>Ulsan, Republic of Korea</p>
    <p>jingoo0223@gmail.com</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I am a Ph.D. candidate in the Department of Civil, Urban, Earth and Environmental Engineering at the **Ulsan National Institute of Science and Technology (UNIST)**, advised by **Prof. Young-Joo Lee**. I expect to receive my Ph.D. in February 2027. I hold a B.S. in Mechanical Engineering, also from UNIST.

My research develops **deep learning surrogate models for the seismic response analysis of structures**, with a focus on **nuclear power plant (NPP) safety**. I am interested in making these models both *reliable* and *interpretable* — combining physics-informed and physically interpretable neural networks, probabilistic uncertainty quantification, virtual sensing for structural health monitoring, and Fourier neural operators for PDE-based engineering problems.

<div class="row justify-content-center mt-4 mb-2">
    <div class="col-lg-11">
        {% include figure.liquid loading="eager" path="assets/img/research_overview.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    My research at a glance: learning a fast, reliable surrogate that maps ground motion to structural responses — with virtual sensing, physical interpretability, and uncertainty quantification.
</div>

**Selected contributions:**

- A **virtual sensing** framework (Res-1D CNN) that predicts seismic floor responses at 139 locations from a single seismometer.
- An **attention-enhanced multimodal** deep learning model (Att-MMDL) for probabilistic seismic response prediction with structural uncertainty propagation.
- A **physically interpretable 1D CNN** that draws an FIR-filter ↔ structural transfer-function analogy, enabling principled kernel-size design.
- A **Windowed Recurrent Fourier Neural Operator (WR-FNO)** for nonlinear seismic response prediction of multi-DOF systems.

Feel free to reach out — I am always happy to discuss deep learning for structural and earthquake engineering.
