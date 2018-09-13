---
title: Publication
date: 2018-09-13 12:14:20 Z
layout: archive
modified: 2018-09-13 12:14:20 Z
excerpt: Publication
image:
  feature:
  teaser:
  thumb:
share: false
ads: false
---

<div class="tiles">
{% for post in site.categories.publication %}
  {% include post-list.html %}
{% endfor %}
</div><!-- /.tiles -->