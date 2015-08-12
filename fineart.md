---
layout: default
title: fineArt
permalink: /fineart/
---

{% for piece in site.fineart %}
  <li>

    <a href="{{ piece.url }}">{{ piece.title }}</a>
      <p>{{ piece.short-description }}</p> 
  </li>
{% endfor %}

