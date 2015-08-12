---
layout: default
title: Озарения
permalink: /insights/
---

{% for insight in site.insights %}
  <li>

    <a href="{{ insight.url }}">{{ insight.title }}</a>
      <p>{{ insight.short-description }}</p> 
  </li>
{% endfor %}

