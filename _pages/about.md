---
layout: about
title: about
permalink: /
news_limit: 4
---

<section class="hero">
  <div class="hero-text">
    <h1 class="hero-name">Jingoo Lee<span class="hero-name-ko" lang="ko">이진구</span></h1>
    <p class="hero-line">Trustworthy Scientific AI for Safety-Critical Structures.</p>
    <div class="hero-bio lang-en">
      <p>I am a Ph.D. candidate at <a href="https://www.unist.ac.kr/">UNIST</a>, advised by <a href="https://ylee.unist.ac.kr/">Prof. Young-Joo Lee</a>. I build deep learning models that predict how structures — nuclear power plants in particular — respond to earthquakes, and I design them to be interpretable and uncertainty-aware so that engineers can rely on them.</p>
      <p class="hero-meta">Ph.D. expected February 2027 · B.S. Mechanical Engineering, UNIST</p>
    </div>
    <div class="hero-bio lang-ko">
      <p><a href="https://www.unist.ac.kr/">UNIST</a> 박사과정이며 <a href="https://ylee.unist.ac.kr/">이영주 교수님</a> 지도 아래 연구하고 있습니다. 구조물, 특히 원자력 발전소가 지진에 어떻게 응답하는지 예측하는 딥러닝 모델을 만들고, 엔지니어가 믿고 쓸 수 있도록 해석 가능하고 불확실성을 다루는 모델로 설계합니다.</p>
      <p class="hero-meta">2027년 2월 박사학위 취득 예정 · UNIST 기계공학 학사</p>
    </div>
    <p class="hero-links">
      <a href="mailto:jingoolee@unist.ac.kr">Email</a>
      <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}" target="_blank" rel="noopener">CV</a>
      <a href="https://scholar.google.com/citations?user=y-QWOo0AAAAJ" target="_blank" rel="noopener">Google Scholar</a>
      <a href="https://github.com/jingoo-lee" target="_blank" rel="noopener">GitHub</a>
    </p>
  </div>
  <div class="hero-photo">
    <img src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Portrait of Jingoo Lee" loading="eager" width="220" height="275">
  </div>
</section>

<section class="block">
  <h2 class="block-title"><span class="lang-en">Research</span><span class="lang-ko">연구</span></h2>

  <article class="work">
    <div class="work-media">{% include figure.liquid loading="lazy" path="assets/img/cacaie_virtual_sensing.png" class="img-fluid" zoomable=true alt="Virtual sensing concept for nuclear power plants" %}</div>
    <div class="work-text">
      <p class="work-kicker"><span class="lang-en">Virtual sensing</span><span class="lang-ko">가상 센싱</span></p>
      <h3><span class="lang-en">One seismometer, the whole building.</span><span class="lang-ko">지진계 하나로 건물 전체를.</span></h3>
      <p class="lang-en">A pretrained deep learning model reconstructs seismic floor responses at 139 locations in a nuclear power plant from a single seismometer, then flags which critical equipment to inspect first after an earthquake.</p>
      <p class="lang-ko">사전학습된 딥러닝 모델이 지진계 하나의 기록으로 원전 139개 지점의 층 응답을 복원하고, 지진 직후 어떤 핵심 기기부터 점검해야 할지 알려줍니다.</p>
      <a class="more" href="https://doi.org/10.1111/mice.70051" target="_blank" rel="noopener">Computer-Aided Civil and Infrastructure Engineering, 2025</a>
    </div>
  </article>

  <article class="work">
    <div class="work-media">{% include figure.liquid loading="lazy" path="assets/img/ress_attmmdl.png" class="img-fluid" zoomable=true alt="Attention-enhanced multimodal deep learning architecture" %}</div>
    <div class="work-text">
      <p class="work-kicker"><span class="lang-en">Uncertainty</span><span class="lang-ko">불확실성</span></p>
      <h3><span class="lang-en">Predictions that know their limits.</span><span class="lang-ko">스스로의 한계를 아는 예측.</span></h3>
      <p class="lang-en">An attention-enhanced multimodal model fuses ground motion and structural parameters to predict seismic floor responses probabilistically, propagating structural uncertainty through time.</p>
      <p class="lang-ko">어텐션 기반 멀티모달 모델이 지반운동과 구조 물성을 결합해 층 응답을 확률적으로 예측하고, 구조 불확실성을 시간에 따라 전파합니다.</p>
      <a class="more" href="https://doi.org/10.1016/j.ress.2026.112582" target="_blank" rel="noopener">Reliability Engineering &amp; System Safety, 2026</a>
    </div>
  </article>

  <article class="work">
    <div class="work-media"><video src="{{ '/assets/video/ned_cnn_reconstruction.mp4' | relative_url }}" autoplay loop muted playsinline aria-label="Learned 1D CNN filters accumulating to reconstruct a structural response"></video></div>
    <div class="work-text">
      <p class="work-kicker"><span class="lang-en">Interpretability</span><span class="lang-ko">해석 가능성</span></p>
      <h3><span class="lang-en">Neural networks that read like filters.</span><span class="lang-ko">필터처럼 읽히는 신경망.</span></h3>
      <p class="lang-en">Treating 1D CNN kernels as FIR filters links them to the structure's transfer function, which gives a physics-based rule for choosing kernel size and shows which frequency band each kernel captures.</p>
      <p class="lang-ko">1D CNN 커널을 FIR 필터로 보고 구조물의 전달함수와 연결해, 커널 크기를 물리적으로 정하는 규칙을 얻고 각 커널이 어떤 주파수 대역을 담당하는지 보여줍니다.</p>
      <a class="more" href="https://doi.org/10.1016/j.nucengdes.2026.115114" target="_blank" rel="noopener">Nuclear Engineering and Design, 2026</a>
    </div>
  </article>

  <p class="block-foot">
    <span class="lang-en">Also working on Fourier neural operators for nonlinear seismic response and digital twins for cable-stayed bridges.</span>
    <span class="lang-ko">비선형 지진 응답을 위한 푸리에 신경 연산자와 사장교 디지털트윈도 연구하고 있습니다.</span>
  </p>
  <p class="block-links">
    <a class="more" href="{{ '/publications/' | relative_url }}"><span class="lang-en">All publications</span><span class="lang-ko">전체 논문</span></a>
    <a class="more" href="{{ '/projects/' | relative_url }}"><span class="lang-en">Projects</span><span class="lang-ko">연구과제</span></a>
  </p>
</section>
