---
layout: archive
title: "Tin tức"
permalink: /news/
---

{% assign posts = site.categories.news | default: site.posts %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
