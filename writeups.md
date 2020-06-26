---
layout: default
title: Writeups
---
<ul class="list">
    {% assign writeup_items = site.writeups | sort: 'date' | reverse %}
    {% for w in writeup_items %}
    <li>{{ w.date | date: "%Y-%m-%d" }} <a href="{{ w.url }}">{{ w.title }}</a> </li>
    {% endfor %}
</ul>