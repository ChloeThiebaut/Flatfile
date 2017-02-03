---
title: Cours
layout: default
---

{% for post in site.cour limit:5 %}
<h2>{{ cour.title }}</h2>
<p>{{ cour.content }}</p>
{% endfor %}
 
{{ site.collections }}
