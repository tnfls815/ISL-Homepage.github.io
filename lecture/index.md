---
title: Lecture
date: 2018-09-13 15:31:00 Z
layout: archive
modified: 2018-09-13 15:31:00 Z
excerpt: 
image:
  feature:
  teaser:
  thumb:
share: false
ads: false
---

<div class="tiles">
{% for post in site.categories.lecture.fall %}
  {% include post-grid.html %}
{% endfor %}
</div>