---
layout: single
title: "Silent Warrior Journal"
permalink: /journal/
author_profile: false
---

[← Back to Silent Warrior Home]({{ site.baseurl }}/)

════════ ⚔️ Silent Warrior ⚔️ ════════

# Silent Warrior Journal

This page collects perosnal notes. life experiences and thoughts written along the Path of the Silent Warrior.

---

## Journal

<ul>
{% for post in site.posts %}
  {% if post.categories contains "journal" %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <span> — {{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endif %}
{% endfor %}
</ul>

---

[← Back to Silent Warrior Home]({{ site.baseurl }}/)
