---
layout: page
title: "Trang chủ"
permalink: /
---

## Tin mới
<ul>
{% for post in site.posts limit:10 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small>— {{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
{% endfor %}
</ul>

## Danh mục
- [Nhân vật]({{ "/characters.html" | relative_url }})
- [Vật phẩm]({{ "/items.html" | relative_url }})
- [Tìm kiếm]({{ "/search.html" | relative_url }})
