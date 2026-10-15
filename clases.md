---
layout: default
title: "Clases"
permalink: /clases/
---

[← Escuela](../)

# Clases · Catecismo Menor

<ul>
{% assign clases = site.clases | sort: 'orden' %}
{% for c in clases %}
  <li><strong>{{ c.sesion }}</strong>:
  {% if c.ready %}<a href="{{ c.url | relative_url }}">{{ c.title }}</a>{% else %}{{ c.title }} [en diseño]{% endif %}</li>
{% endfor %}
</ul>
