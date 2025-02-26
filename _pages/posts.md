---
layout: default
title: "Blog Posts"
permalink: /posts/
---

# 📚 Blog Posts

<ul style="font-size: 1.4rem;">
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">
      {{ post.title }}
    </a> - {{ post.date | date: "%B %d, %Y" }}
  </li>
  {% endfor %}
</ul>
