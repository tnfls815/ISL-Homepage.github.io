---
layout: archive
permalink: /
title: "Welcome to ISL"
#title: "Latest Posts"
image:
  feature: isl_main3.gif

---

<div class="tiles">
<!--lecture-->
{% for post in site.categories.lecture_spring %}
  {% include post-grid.html %}
{% endfor %}

<!--research-->
{% for post in site.categories.research %}
  {% include post-grid.html %}
{% endfor %}

<!--seminar-->
{% for post in site.categories.seminar %}
  {% include post-grid.html %}
{% endfor %}
</div>
