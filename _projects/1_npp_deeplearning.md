---
layout: page
title: Deep Learning for Seismic Assessment of Nuclear Power Plants
description: 원전 구조물·기기 지진응답 및 손상평가를 위한 딥러닝 기술개발
img: assets/img/npp_aux_building.png
importance: 1
category: work
related_publications: true
---

**원전 구조물/기기 지진응답 및 손상평가를 위한 딥러닝 기술개발**
*Deep learning technologies for assessment of seismic responses and damage of nuclear power plant structures and equipment.*

- **Funding:** National Research Foundation of Korea (NRF) / Ministry of Science and ICT
- **Period:** Apr. 2022 – Dec. 2026
- **Role:** Lead graduate researcher — deep learning surrogate models, virtual sensing, and uncertainty quantification for the seismic response of NPP structures.

{% include figure.liquid loading="eager" path="assets/img/npp_aux_building.png" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">
    Finite element model of the target nuclear power plant auxiliary building (left; monitored equipment locations in red) and its part-by-part structural decomposition (right). This high-fidelity model generates the seismic response data that the deep-learning surrogates are trained to reproduce.
</div>

This project develops deep-learning surrogate models that predict the seismic response of nuclear power plant structures and equipment, replacing expensive finite-element simulations. My work covers a virtual-sensing framework that reconstructs floor responses at many locations from a single seismometer, attention-based multimodal models for probabilistic prediction with uncertainty propagation, and physically interpretable 1D CNNs for principled model design.

Representative outcomes from this project include {% cite lee2025virtual lee2026attmmdl lee2026interpretable1dcnn %}.
