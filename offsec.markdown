---
layout: page
title: Offsec
permalink: /offsec/
---

<ul>
  {% for post in site.categories.offsec %}
    <li>
      <span>{{ post.date | date: "%b %-d, %Y" }}</span> — 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

