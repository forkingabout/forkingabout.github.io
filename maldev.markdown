---
layout: page
title: Mal Dev 
permalink: /maldev/
---

<ul>
  {% for post in site.categories.maldev %}
    <li>
      <span>{{ post.date | date: "%b %-d, %Y" }}</span> — 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

