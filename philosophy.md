---
layout: single
title: "Silent Warrior Philosophy"
permalink: /philosophy/
author_profile: false
---

                                  ════════ ⚔️ Silent Warrior ⚔️ ════════


This page collects all reflections written along the Path of the Silent Warrior.

---

## Reflections

<ul>
{% for post in site.posts %}
  {% if post.categories contains "philosophy" %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <span> — {{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endif %}
{% endfor %}
</ul>

---
