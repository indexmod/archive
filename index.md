---
title: Index
permalink: index
position: 0
layout: default
---

<ul>

  {% assign mypages = site.pages | sort: "order" %}
  {% for page in mypages %}
  <a href="{{ page.url | absolute_url }}">{{ page.title }}</a>
  {% endfor %}

</ul>
