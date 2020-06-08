---
layout: default
title: Writeups
---
<span class="desc">Figured it's good practice to write about my progress and solves.</span>

<ul class="list">
    {% for w in site.writeups %}
    <li>{{ w.date | date: "%Y-%m-%d" }} <a href="{{ w.url }}">{{ w.title }}</a> </li>
    {% endfor %}
</ul>