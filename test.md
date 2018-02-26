---
layout: cover
published: true
title: Index
---
<!--- Do not change the "index.md" --->


# Index

<ul>

  {% assign mypages = site.pages | sort: "order" %}
  {% for page in mypages %}
   <li class="intro">
  <a href="{{ site.pages | sample }}">{{ page.title }}</a>
  </li>
  {% endfor %}


</ul>



