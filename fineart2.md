---
layout: default
title: fineArt2
permalink: /fineart2/
---

{% for piece in site.fineart %}
  <li>

    <a href="{{ piece.url }}">{{ piece.title }}</a>
      <p>{{ piece.short-description }}</p> 
  </li>
{% endfor %}

