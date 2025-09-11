---
layout: page
title: Arquivo
permalink: /archive/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      - {{ post.date | date: site.minima.date_format: "%d-%m-%Y" }}
    </li>
  {% endfor %}
</ul>
