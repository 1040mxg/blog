---
layout: default
title: Index
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.permalink }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
