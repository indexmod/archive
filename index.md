---
layout: default
---

<ul>
 
 <li class="intro">
  {% assign mypages = site.pages | sort: "order" %}
  {% for page in mypages %}
  <a href="{{ page.url | absolute_url }}">{{ page.title }}</a>
  {% endfor %}
  </li>

</ul>
