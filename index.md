---
layout: default
---

<ul class="intro">
 

  {% assign mypages = site.pages | sort: "order" %}
  {% for page in mypages %}
   <li>
  <a href="{{ page.url | absolute_url }}">{{ page.title }}</a>
   </li>
  {% endfor %}
  

</ul>
