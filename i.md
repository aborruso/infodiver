---
layout: page
title: Список озарений
permalink: /insights/
---

{% for insight in site.insights limit:3 %}
      <li>

        <a href="{{ insight.url }}">{{ insight.title }}</a>
        <p>{{ insight.short-description }}</p>
      </li>
{% endfor %}
