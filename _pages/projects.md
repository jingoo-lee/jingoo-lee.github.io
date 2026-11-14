---
layout: page
title_ko: 연구과제
title: Projects
permalink: /projects/
description: Funded research projects I work on.
nav: true
nav_order: 3
description_ko: 참여 중인 연구과제
---

{% assign sorted_projects = site.projects | sort: "importance" %}
<ul class="project-list">
{% for project in sorted_projects %}
  <li>
    <a class="project-title" href="{{ project.url | relative_url }}"><span class="lang-en">{{ project.title }}</span><span class="lang-ko">{{ project.title_ko | default: project.title }}</span></a>
    <p class="project-summary"><span class="lang-en">{{ project.summary_en }}</span><span class="lang-ko">{{ project.description }}</span></p>
    <p class="project-meta">{{ project.funding }} <span class="nowrap">· {{ project.period }}</span></p>
  </li>
{% endfor %}
</ul>
