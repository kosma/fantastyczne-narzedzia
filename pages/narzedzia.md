---
layout: page
title: "Narzędzia"
permalink: "/narzedzia/"
---

<ul>
{% for item in site.narzedzia %}

<li><a href="{{ item.url }}">{{ item.title }}</a></li>

{% endfor %}
</ul>
