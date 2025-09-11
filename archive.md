---
layout: page
title: Arquivo
permalink: /archive/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      - {{ page.date | date: site.minima.date_format }}
    </li>
  {% endfor %}
</ul>
