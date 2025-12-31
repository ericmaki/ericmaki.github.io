---
layout: default
title: Eric Maki
---

# Hello World
This is my new site using a GitHub theme!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
