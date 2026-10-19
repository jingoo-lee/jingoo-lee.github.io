---
layout: page
title: Deep Learning for Seismic Assessment of Nuclear Power Plants
description: 원전 구조물·기기 지진응답 및 손상평가를 위한 딥러닝 기술개발
img: assets/img/proj_npp_ml.jpg
importance: 1
category: work
related_publications: true
title_ko: 원전 지진 안전성 평가를 위한 딥러닝
---

**원전 구조물/기기 지진응답 및 손상평가를 위한 딥러닝 기술개발**
*Deep learning technologies for assessment of seismic responses and damage of nuclear power plant structures and equipment.*

- **Funding:** National Research Foundation of Korea (NRF) / Ministry of Science and ICT
- **Period:** Apr. 2022 – Dec. 2026
- <span class="lang-en">**Role:** Lead graduate researcher — deep learning surrogate models, virtual sensing, and uncertainty quantification for the seismic response of NPP structures.</span><span class="lang-ko">**역할:** 주관 대학원 연구원 — 원전 구조물 지진 응답을 위한 딥러닝 대리모델, 가상 센싱, 불확실성 정량화</span>

{% include figure.liquid loading="eager" path="assets/img/npp_aux_building.png" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">
    Finite element model of the target nuclear power plant auxiliary building (left; monitored equipment locations in red) and its part-by-part structural decomposition (right). This high-fidelity model generates the seismic response data that the deep-learning surrogates are trained to reproduce.
</div>

<div class="lang-en" markdown="1">
This project develops deep-learning surrogate models that predict the seismic response of nuclear power plant structures and equipment, replacing expensive finite-element simulations. My work covers a virtual-sensing framework that reconstructs floor responses at many locations from a single seismometer, attention-based multimodal models for probabilistic prediction with uncertainty propagation, and physically interpretable 1D CNNs for principled model design.
</div>
<div class="lang-ko" markdown="1">
이 과제는 값비싼 유한요소 해석을 대신해 원전 구조물과 기기의 지진 응답을 예측하는 딥러닝 대리모델을 개발합니다. 저는 지진계 하나로 여러 지점의 층 응답을 복원하는 가상 센싱 프레임워크, 불확실성 전파를 고려한 어텐션 기반 멀티모달 확률 예측 모델, 그리고 원리적인 모델 설계를 위한 물리적으로 해석 가능한 1D CNN을 맡고 있습니다.
</div>

<span class="lang-en">Representative outcomes from this project include</span><span class="lang-ko">이 과제의 대표 성과:</span> {% cite lee2025virtual lee2026attmmdl lee2026interpretable1dcnn %}.
