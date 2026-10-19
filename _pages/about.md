---
layout: about
title: about
permalink: /
subtitle: Ph.D. Candidate, <a href='https://www.unist.ac.kr/'>UNIST</a> · Deep Learning × Structural &amp; Seismic Engineering

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

<section class="hero-card">
  <div class="hero-text">
    <div class="hero-eyebrow">
      <span class="lang-en">Ph.D. Candidate · UNIST</span>
      <span class="lang-ko">UNIST 박사과정</span>
    </div>
    <h1 class="hero-name">Jingoo Lee <span class="hero-name-ko">이진구</span></h1>
    <p class="hero-role">
      <span class="lang-en">Deep learning × Structural &amp; seismic engineering</span>
      <span class="lang-ko">딥러닝 × 구조·지진공학</span>
    </p>
    <div class="hero-tags">
      <span class="tag t-npp"><span class="lang-en">Nuclear power plants</span><span class="lang-ko">원자력 발전소</span></span>
      <span class="tag t-bridge"><span class="lang-en">Bridges &amp; SHM</span><span class="lang-ko">교량 · 구조 모니터링</span></span>
      <span class="tag t-ml"><span class="lang-en">Interpretable DL</span><span class="lang-ko">해석 가능한 딥러닝</span></span>
      <span class="tag t-uq"><span class="lang-en">Uncertainty</span><span class="lang-ko">불확실성 정량화</span></span>
    </div>
    <div class="hero-typed"><span id="typed"></span></div>
    <div class="hero-buttons">
      <a class="hero-btn primary" href="{{ '/assets/pdf/cv.pdf' | relative_url }}" target="_blank" rel="noopener"><i class="fa-solid fa-file-lines"></i> CV</a>
      <a class="hero-btn" href="https://scholar.google.com/citations?user=y-QWOo0AAAAJ" target="_blank" rel="noopener"><i class="ai ai-google-scholar"></i> Scholar</a>
      <a class="hero-btn" href="https://github.com/jingoo-lee" target="_blank" rel="noopener"><i class="fa-brands fa-github"></i> GitHub</a>
      <a class="hero-btn" href="mailto:jingoolee@unist.ac.kr"><i class="fa-solid fa-envelope"></i> Email</a>
    </div>
  </div>
  <div class="hero-photo">
    <img src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Jingoo Lee" loading="eager">
  </div>
</section>

<div id="typed-strings-en" style="display:none;">
  <p>Deep learning surrogate models for seismic response.</p>
  <p>Virtual sensing from a single seismometer.</p>
  <p>Physics-informed &amp; interpretable neural networks.</p>
  <p>Uncertainty quantification for reliable predictions.</p>
  <p>Fourier neural operators for engineering PDEs.</p>
</div>
<div id="typed-strings-ko" style="display:none;">
  <p>지진 응답을 예측하는 딥러닝 대리모델.</p>
  <p>지진계 하나로 건물 전체를 읽는 가상 센싱.</p>
  <p>물리 기반 · 해석 가능한 신경망.</p>
  <p>믿을 수 있는 예측을 위한 불확실성 정량화.</p>
  <p>공학 문제를 위한 푸리에 신경 연산자.</p>
</div>
<script src="https://cdn.jsdelivr.net/npm/typed.js@2.1.0/dist/typed.umd.js"></script>
<script>
  (function () {
    var t = null;
    function start() {
      if (!window.Typed) return;
      if (t) { t.destroy(); }
      var ko = document.documentElement.getAttribute('data-lang') === 'ko';
      t = new Typed('#typed', { stringsElement: ko ? '#typed-strings-ko' : '#typed-strings-en', typeSpeed: 45, backSpeed: 18, backDelay: 1700, startDelay: 300, loop: true, smartBackspace: true });
    }
    document.addEventListener('DOMContentLoaded', start);
    window.addEventListener('langchange', start);
  })();
</script>

<section class="home-section intro">
  <div class="lang-en">
    <p>I am a Ph.D. candidate at the <a href="https://www.unist.ac.kr/"><b>Ulsan National Institute of Science and Technology (UNIST)</b></a>, advised by <a href="https://ylee.unist.ac.kr/"><b>Prof. Young-Joo Lee</b></a> in the <a href="https://ylee.unist.ac.kr/">Structural Reliability &amp; Disaster Risk Lab</a>. I expect to receive my Ph.D. in February 2027. I hold a B.S. in Mechanical Engineering, also from UNIST.</p>
    <p>My research develops <b>deep learning surrogate models for the seismic response analysis of structures</b>, with a focus on <b>nuclear power plant (NPP) safety</b>. I aim to make these models both <i>reliable</i> and <i>interpretable</i> — combining physics-informed and physically interpretable neural networks, probabilistic uncertainty quantification, virtual sensing for structural health monitoring, and Fourier neural operators for PDE-based engineering problems.</p>
  </div>
  <div class="lang-ko">
    <p><a href="https://www.unist.ac.kr/"><b>울산과학기술원(UNIST)</b></a> 박사과정이며, <a href="https://ylee.unist.ac.kr/"><b>이영주 교수님</b></a>의 <a href="https://ylee.unist.ac.kr/">구조신뢰성 및 재난위험 연구실(SRDR Lab)</a>에서 연구하고 있습니다. 2027년 2월 박사학위 취득 예정이며, UNIST에서 기계공학 학사를 받았습니다.</p>
    <p>구조물의 <b>지진 응답을 빠르고 정확하게 예측하는 딥러닝 대리모델</b>을 연구하며, 특히 <b>원자력 발전소의 지진 안전성</b>에 집중하고 있습니다. 모델이 <i>믿을 수 있고</i>, <i>왜 그렇게 예측하는지 설명할 수 있도록</i> 물리 기반·해석 가능 신경망, 확률적 불확실성 정량화, 구조 건전성 모니터링을 위한 가상 센싱, 그리고 공학 편미분방정식 문제를 위한 푸리에 신경 연산자를 함께 다룹니다.</p>
  </div>
</section>

<section class="home-section">
  <div class="section-eyebrow"><span class="lang-en">Overview</span><span class="lang-ko">한눈에 보기</span></div>
  <h2 class="section-title"><span class="lang-en">Research at a glance</span><span class="lang-ko">연구 분야</span></h2>
  <div class="glance-card">
    {% include figure.liquid loading="eager" path="assets/img/research_interests.png" class="img-fluid" zoomable=true %}
  </div>
  <p class="glance-caption">
    <span class="lang-en">At the intersection of <b>deep learning</b>, <b>structural engineering</b>, and <b>reliability &amp; uncertainty quantification</b> — toward <b>trustworthy AI for structures</b>.</span>
    <span class="lang-ko"><b>딥러닝</b>, <b>구조공학</b>, <b>신뢰성·불확실성 정량화</b>가 만나는 지점에서 <b>구조물을 위한 믿을 수 있는 AI</b>를 만듭니다.</span>
  </p>
</section>

<section class="home-section">
  <div class="section-eyebrow"><span class="lang-en">Highlights · Nuclear safety</span><span class="lang-ko">주요 연구 · 원전 안전</span></div>
  <h2 class="section-title"><span class="lang-en">Featured research</span><span class="lang-ko">대표 연구</span></h2>
  <div class="feature-grid">

    <article class="feature-card wide th-npp">
      <div class="feature-media">{% include figure.liquid loading="lazy" path="assets/img/npp_aux_building.png" class="img-fluid" zoomable=true %}</div>
      <div class="feature-body">
        <div class="card-theme"><span class="lang-en">Nuclear power plants</span><span class="lang-ko">원자력 발전소</span></div>
        <h3><span class="lang-en">The structures I model</span><span class="lang-ko">연구 대상 구조물</span></h3>
        <p class="lang-en">A high-fidelity finite element model of an NPP auxiliary building (monitored equipment in red) and its part-by-part decomposition. It generates the seismic response data my surrogates learn to reproduce.</p>
        <p class="lang-ko">원전 보조건물의 고정밀 유한요소 모델(빨간 점은 감시 대상 기기)과 층별 분해도입니다. 이 모델로 만든 지진 응답 데이터를 딥러닝 대리모델이 학습합니다.</p>
      </div>
    </article>

    <article class="feature-card th-npp">
      <div class="feature-media">{% include figure.liquid loading="lazy" path="assets/img/cacaie_virtual_sensing.png" class="img-fluid" zoomable=true %}</div>
      <div class="feature-body">
        <div class="card-theme"><span class="lang-en">Nuclear power plants</span><span class="lang-ko">원자력 발전소</span></div>
        <h3><span class="lang-en">Virtual sensing for NPPs</span><span class="lang-ko">원전 가상 센싱</span></h3>
        <p class="lang-en">A pretrained deep-learning model reconstructs seismic floor responses from a single seismometer, replacing dozens of physical accelerometers.</p>
        <p class="lang-ko">사전학습된 딥러닝 모델이 지진계 하나의 기록만으로 건물 곳곳의 층 응답을 복원해, 수십 개의 가속도계를 대신합니다.</p>
        <a class="venue-chip" href="https://doi.org/10.1111/mice.70051" target="_blank" rel="noopener">CACAIE 2025</a>
      </div>
    </article>

    <article class="feature-card th-npp">
      <div class="feature-media">{% include figure.liquid loading="lazy" path="assets/img/cacaie_equipment_inspection.png" class="img-fluid" zoomable=true %}</div>
      <div class="feature-body">
        <div class="card-theme"><span class="lang-en">Nuclear power plants</span><span class="lang-ko">원자력 발전소</span></div>
        <h3><span class="lang-en">Rapid equipment inspection</span><span class="lang-ko">지진 후 신속 기기 점검</span></h3>
        <p class="lang-en">Reconstructed floor responses flag which critical equipment exceeded safety thresholds, prioritizing what to inspect first after an earthquake.</p>
        <p class="lang-ko">복원한 층 응답으로 안전 기준을 넘은 핵심 기기를 찾아, 지진 직후 무엇부터 점검할지 우선순위를 정합니다.</p>
        <a class="venue-chip" href="https://doi.org/10.1111/mice.70051" target="_blank" rel="noopener">CACAIE 2025</a>
      </div>
    </article>

    <article class="feature-card th-ml">
      <div class="feature-media"><video src="{{ '/assets/video/ned_cnn_reconstruction.mp4' | relative_url }}" autoplay loop muted playsinline></video></div>
      <div class="feature-body">
        <div class="card-theme"><span class="lang-en">Interpretable DL</span><span class="lang-ko">해석 가능한 딥러닝</span></div>
        <h3><span class="lang-en">Physically interpretable 1D CNN</span><span class="lang-ko">물리적으로 해석 가능한 1D CNN</span></h3>
        <p class="lang-en">Learned filters accumulate to reconstruct the structural response, revealing which frequency band each kernel captures.</p>
        <p class="lang-ko">학습된 필터들이 쌓여 구조 응답을 재구성하는 과정을 보여주며, 각 커널이 어떤 주파수 대역을 담당하는지 드러냅니다.</p>
        <a class="venue-chip" href="https://doi.org/10.1016/j.nucengdes.2026.115114" target="_blank" rel="noopener">NED 2026</a>
      </div>
    </article>

    <article class="feature-card th-uq">
      <div class="feature-media">{% include figure.liquid loading="lazy" path="assets/img/ress_attmmdl.png" class="img-fluid" zoomable=true %}</div>
      <div class="feature-body">
        <div class="card-theme"><span class="lang-en">Uncertainty</span><span class="lang-ko">불확실성 정량화</span></div>
        <h3><span class="lang-en">Attention-enhanced multimodal DL</span><span class="lang-ko">어텐션 기반 멀티모달 딥러닝</span></h3>
        <p class="lang-en">Fuses ground motion and structural parameters through multi-head attention for probabilistic seismic response prediction.</p>
        <p class="lang-ko">지반운동과 구조 물성을 멀티헤드 어텐션으로 결합해 지진 응답을 확률적으로 예측합니다.</p>
        <a class="venue-chip" href="https://doi.org/10.1016/j.ress.2026.112582" target="_blank" rel="noopener">RESS 2026</a>
      </div>
    </article>

  </div>
</section>


<section class="home-section">
  <div class="section-eyebrow th-bridge-text"><span class="lang-en">Bridges &amp; structural health monitoring</span><span class="lang-ko">교량 · 구조 건전성 모니터링</span></div>
  <h2 class="section-title"><span class="lang-en">From nuclear plants to bridges</span><span class="lang-ko">원전에서 교량까지</span></h2>
  <div class="feature-grid">
    <article class="feature-card wide th-bridge">
      <div class="feature-media">{% include figure.liquid loading="lazy" path="assets/img/proj_bridge_dt.jpg" class="img-fluid" zoomable=true %}</div>
      <div class="feature-body">
        <div class="card-theme"><span class="lang-en">Bridges · Digital twin</span><span class="lang-ko">교량 · 디지털트윈</span></div>
        <h3><span class="lang-en">Digital twin &amp; vision AI for bridge disaster response</span><span class="lang-ko">디지털트윈·비전 AI 기반 교량 재난대응 상황실</span></h3>
        <p class="lang-en">An NRF mid-career project (2024–2029) building a command center that fuses physics-based models, sensor data, and vision AI. I develop the data-driven surrogates and probabilistic response predictions that keep the digital twin in sync with monitoring data.</p>
        <p class="lang-ko">물리 모델·센서 데이터·비전 AI를 결합해 교량 재난대응 상황실을 만드는 한국연구재단 중견연구(2024–2029)입니다. 디지털트윈이 계측 데이터와 맞물려 돌아가도록 데이터 기반 대리모델과 확률적 응답 예측을 맡고 있습니다.</p>
        <a class="venue-chip" href="{{ '/projects/2_digital_twin_bridge/' | relative_url }}"><span class="lang-en">Project page →</span><span class="lang-ko">과제 페이지 →</span></a>
      </div>
    </article>
    <article class="feature-card th-bridge">
      <div class="feature-media">{% include figure.liquid loading="lazy" path="assets/img/bridge_kibse23_arch.png" class="img-fluid" zoomable=true %}</div>
      <div class="feature-body">
        <div class="card-theme"><span class="lang-en">Cable-stayed bridges</span><span class="lang-ko">사장교</span></div>
        <h3><span class="lang-en">Multi-kernel 1D CNN for cable tension</span><span class="lang-ko">다중 커널 1D CNN 케이블 장력 예측</span></h3>
        <p class="lang-en">One-step-ahead prediction of 17 stay-cable tensions on the 2nd Jindo Bridge (344 m main span) from temperature, wind, and tension monitoring data. Parallel kernels of size 4 and 32 beat an LSTM on all four overall metrics (RMSE 4.87 vs 7.32; peak RMSE 121.9 vs 197.0).</p>
        <p class="lang-ko">제2진도대교(주경간 344 m)의 온도·풍속·장력 계측 데이터로 케이블 17개의 장력을 한 스텝 앞서 예측합니다. 크기 4와 32인 커널을 나란히 쓴 1D CNN이 모든 지표에서 LSTM보다 정확했습니다(RMSE 4.87 대 7.32, 피크 RMSE 121.9 대 197.0).</p>
        <span class="venue-chip">KIBSE 2023</span>
      </div>
    </article>
    <article class="feature-card th-bridge">
      <div class="feature-media">{% include figure.liquid loading="lazy" path="assets/img/bridge_tension_band.png" class="img-fluid" zoomable=true %}</div>
      <div class="feature-body">
        <div class="card-theme"><span class="lang-en">Cable-stayed bridges · Uncertainty</span><span class="lang-ko">사장교 · 불확실성</span></div>
        <h3><span class="lang-en">Probabilistic cable tension from environment</span><span class="lang-ko">환경조건 기반 케이블 장력 확률 예측</span></h3>
        <p class="lang-en">Fourteen probabilistic models predict 90 % bands of 17 cable tensions from 29 environmental variables such as temperature, wind, and traffic. Quantile models draw sharp bands that cover only 60–76 %, while GPR and a GRU with Gaussian likelihood reach the nominal 90 % at about 40 kN width.</p>
        <p class="lang-ko">온도·풍속·교통량 등 환경변수 29개로 케이블 17개 장력의 90 % 예측 구간을 그리는 확률 모델 14종을 비교했습니다. 분위수 모델은 구간이 좁지만 60–76 %만 덮고, GPR과 가우시안 우도 GRU는 약 40 kN 폭으로 공칭 90 %를 달성했습니다.</p>
        <span class="venue-chip">KIBSE 2026</span>
      </div>
    </article>
    <article class="feature-card wide th-bridge text-only">
      <div class="feature-body">
        <div class="card-theme"><span class="lang-en">Cable-stayed bridges</span><span class="lang-ko">사장교</span></div>
        <h3><span class="lang-en">Time-series response prediction with multi-kernel deep learning</span><span class="lang-ko">다중 커널 딥러닝 교량 시계열 응답 예측</span></h3>
        <p class="lang-en">Time-series structural response prediction of cable-stayed bridges using a multi-kernel deep learning model.</p>
        <p class="lang-ko">다중 커널 딥러닝 모델로 사장교의 시계열 구조 응답을 예측합니다.</p>
        <span class="venue-chip">KSMI 2024</span>
      </div>
    </article>
  </div>
</section>

<section class="home-section">
  <div class="section-eyebrow"><span class="lang-en">Contributions</span><span class="lang-ko">핵심 기여</span></div>
  <h2 class="section-title"><span class="lang-en">What I have built</span><span class="lang-ko">지금까지 만든 것</span></h2>
  <div class="contrib-grid">
    <div class="contrib-card c-npp"><span class="contrib-num">01</span>
      <p class="lang-en">A <b>virtual sensing</b> framework (Res-1D CNN) that predicts seismic floor responses at 139 locations from a single seismometer.</p>
      <p class="lang-ko">지진계 하나로 139개 지점의 층 응답을 예측하는 <b>가상 센싱</b> 프레임워크(Res-1D CNN).</p></div>
    <div class="contrib-card c-uq"><span class="contrib-num">02</span>
      <p class="lang-en">An <b>attention-enhanced multimodal</b> model (Att-MMDL) for probabilistic prediction with structural uncertainty propagation.</p>
      <p class="lang-ko">구조 불확실성 전파를 고려해 확률적으로 예측하는 <b>어텐션 기반 멀티모달</b> 모델(Att-MMDL).</p></div>
    <div class="contrib-card c-ml"><span class="contrib-num">03</span>
      <p class="lang-en">A <b>physically interpretable 1D CNN</b> built on an FIR-filter ↔ structural transfer-function analogy for principled kernel design.</p>
      <p class="lang-ko">FIR 필터와 구조 전달함수의 유사성에 기반해 커널 크기를 원리적으로 설계하는 <b>해석 가능한 1D CNN</b>.</p></div>
    <div class="contrib-card c-ml2"><span class="contrib-num">04</span>
      <p class="lang-en">A <b>Windowed Recurrent Fourier Neural Operator</b> (WR-FNO) for nonlinear seismic response of multi-DOF systems.</p>
      <p class="lang-ko">다자유도 시스템의 비선형 지진 응답을 예측하는 <b>윈도우 순환 푸리에 신경 연산자</b>(WR-FNO).</p></div>
  </div>
</section>
