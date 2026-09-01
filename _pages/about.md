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
    <div style="text-align: center;">
      <p style="margin-bottom: 0.15rem;"><a href="https://www.unist.ac.kr/" target="_blank" rel="noopener">UNIST</a>, Republic of Korea</p>
      <p><a href="mailto:jingoolee@unist.ac.kr">jingoolee@unist.ac.kr</a></p>
    </div>

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

<div id="typed-strings" style="display:none;">
  <p>Deep learning surrogate models for seismic response.</p>
  <p>Virtual sensing from a single seismometer.</p>
  <p>Physics-informed &amp; interpretable neural networks.</p>
  <p>Uncertainty quantification for reliable predictions.</p>
  <p>Machine learning for natural-hazard risk.</p>
  <p>Fourier neural operators for engineering PDEs.</p>
</div>
<div style="font-size:1.18rem;font-weight:500;color:var(--global-theme-color);min-height:1.7em;margin:0.1rem 0 1.3rem;">
  <span id="typed"></span>
</div>
<script src="https://cdn.jsdelivr.net/npm/typed.js@2.1.0/dist/typed.umd.js"></script>
<script>
  document.addEventListener('DOMContentLoaded', function () {
    if (window.Typed) {
      new Typed('#typed', { stringsElement: '#typed-strings', typeSpeed: 45, backSpeed: 18, backDelay: 1700, startDelay: 350, loop: true, smartBackspace: true });
    }
  });
</script>

I am a Ph.D. candidate in the Department of Civil, Urban, Earth and Environmental Engineering at the [**Ulsan National Institute of Science and Technology (UNIST)**](https://www.unist.ac.kr/), advised by [**Prof. Young-Joo Lee**](https://ylee.unist.ac.kr/) in the [Structural Reliability &amp; Disaster Risk Lab](https://ylee.unist.ac.kr/). I expect to receive my Ph.D. in February 2027. I hold a B.S. in Mechanical Engineering, also from UNIST.

My research develops **deep learning surrogate models for the seismic response analysis of structures**, with a focus on **nuclear power plant (NPP) safety**. I am interested in making these models both *reliable* and *interpretable* — combining physics-informed and physically interpretable neural networks, probabilistic uncertainty quantification, virtual sensing for structural health monitoring, and Fourier neural operators for PDE-based engineering problems.

{% include figure.liquid loading="eager" path="assets/img/research_overview.png" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">
    My research at a glance: learning a fast, reliable surrogate that maps ground motion to structural responses — with virtual sensing, physical interpretability, and uncertainty quantification.
</div>

#### Featured research

<video src="{{ '/assets/video/ned_cnn_reconstruction.mp4' | relative_url }}" class="rounded z-depth-1" style="width:100%;height:auto;display:block;" autoplay loop muted playsinline></video>
<div class="caption">
    <b>Physically interpretable 1D CNN</b> — learned filters accumulate to reconstruct the structural response, revealing which frequency bands each kernel captures (<i>Nuclear Engineering &amp; Design</i>, 2026).
</div>

{% include figure.liquid loading="eager" path="assets/img/ress_attmmdl.png" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">
    <b>Attention-enhanced multimodal deep learning (Att-MMDL)</b> — fuses ground motion and structural parameters through multi-head attention for probabilistic seismic response prediction (<i>Reliability Engineering &amp; System Safety</i>, 2026).
</div>

**Selected contributions:**

- A **virtual sensing** framework (Res-1D CNN) that predicts seismic floor responses at 139 locations from a single seismometer.
- An **attention-enhanced multimodal** deep learning model (Att-MMDL) for probabilistic seismic response prediction with structural uncertainty propagation.
- A **physically interpretable 1D CNN** that draws an FIR-filter ↔ structural transfer-function analogy, enabling principled kernel-size design.
- A **Windowed Recurrent Fourier Neural Operator (WR-FNO)** for nonlinear seismic response prediction of multi-DOF systems.

Feel free to reach out — I am always happy to discuss deep learning for structural and earthquake engineering.
