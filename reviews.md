---
layout: default
title: "Video Game Reviews"
permalink: /reviews/
---

Here are our latest video game reviews:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>