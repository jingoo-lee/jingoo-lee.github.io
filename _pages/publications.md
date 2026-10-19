---
layout: page
permalink: /publications/
title: publications
description: Journal articles, international and domestic conference papers, and patents, in reverse chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography-section">Journal Articles</h2>
{% bibliography --query @article %}

<h2 class="bibliography-section">International Conferences</h2>
{% bibliography --query @inproceedings[keywords=international] %}

<h2 class="bibliography-section">Domestic Conferences (Korea)</h2>
{% bibliography --query @inproceedings[keywords=domestic] %}

<h2 class="bibliography-section">Patents</h2>
{% bibliography --query @misc[keywords=patent] %}

</div>
