---
title: "CDEs"
permalink: /cdes/
layout: single
---

## Career Development Events

District CDE resources, results, and historical materials will be posted here.

<ul>
{% for file in site.static_files %}
  {% if file.path contains '/documents/cdes/' %}
    <li>
      <a href="{{ file.path }}">{{ file.name }}</a>
    </li>
  {% endif %}
{% endfor %}
</ul>
