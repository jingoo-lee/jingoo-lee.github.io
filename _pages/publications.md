---
layout: page
permalink: /publications/
title_ko: 논문
title: Publications
description: Journal articles, international and domestic conference papers, and patents, in reverse chronological order.
nav: true
nav_order: 2
description_ko: 저널 논문, 국제·국내 학술대회 발표, 특허를 최신순으로 정리했습니다.
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->


<div class="publications">

<h2 class="bibliography-section pub-journal-h"><span class="lang-en">Journal Articles</span><span class="lang-ko">저널 논문</span></h2>
<div class="pub-sec pub-journal" markdown="0">
{% bibliography --query @article[note!=In preparation] %}
</div>

<h2 class="bibliography-section"><span class="lang-en">Manuscripts in Preparation</span><span class="lang-ko">준비 중인 원고</span></h2>
<div class="pub-sec pub-prep" markdown="0">
{% bibliography --query @article[note=In preparation] %}
</div>

<h2 class="bibliography-section pub-intl-h"><span class="lang-en">International Conferences</span><span class="lang-ko">국제 학술대회</span></h2>
<div class="pub-sec pub-intl" markdown="0">
{% bibliography --query @inproceedings[keywords=international] %}
</div>

<h2 class="bibliography-section pub-domestic-h"><span class="lang-en">Domestic Conferences (Korea)</span><span class="lang-ko">국내 학술대회</span></h2>
<div class="pub-sec pub-domestic" markdown="0">
{% bibliography --query @inproceedings[keywords=domestic] %}
</div>

<h2 class="bibliography-section pub-patent-h"><span class="lang-en">Patents</span><span class="lang-ko">특허</span></h2>
<div class="pub-sec pub-patent" markdown="0">
{% bibliography --query @misc[keywords=patent] %}
</div>

</div>
