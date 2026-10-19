---
layout: page
permalink: /publications/
title_ko: 논문
title: publications
description: Journal articles, international and domestic conference papers, and patents, in reverse chronological order.
nav: true
nav_order: 2
description_ko: 저널 논문, 국제·국내 학술대회 발표, 특허를 최신순으로 정리했습니다.
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography-section"><span class="lang-en">Journal Articles</span><span class="lang-ko">저널 논문</span></h2>
{% bibliography --query @article %}

<h2 class="bibliography-section"><span class="lang-en">International Conferences</span><span class="lang-ko">국제 학술대회</span></h2>
{% bibliography --query @inproceedings[keywords=international] %}

<h2 class="bibliography-section"><span class="lang-en">Domestic Conferences (Korea)</span><span class="lang-ko">국내 학술대회</span></h2>
{% bibliography --query @inproceedings[keywords=domestic] %}

<h2 class="bibliography-section"><span class="lang-en">Patents</span><span class="lang-ko">특허</span></h2>
{% bibliography --query @misc[keywords=patent] %}

</div>
