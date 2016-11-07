---
layout: page
title: gks
---

<ul>
{% for item in site.data.gks %}
<li style="{%if item.pozycja %} color: red {% endif %}">
{{ item.name}} (<em>)
  {{ item }}
</li>
{% endfor %}
</el>
