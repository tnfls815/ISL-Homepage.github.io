---
title: People
date: 2018-09-12 11:14:20 Z
layout: archive
modified: 2018-09-12 11:14:20 Z
excerpt: People
image:
  feature: People.jpg
  teaser:
  thumb:
share: false
ads: false
---

<div class="tiles">
{% for post in site.categories.people %}
  {% include scroll-cue.html %}
{% endfor %}
</div><!-- /.tiles -->