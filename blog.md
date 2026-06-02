---
layout: page
title: Blog
permalink: /blog/
---

# Blog Insights

Welcome to my technical journal. Here you'll find papers, guides, and thoughts on automated compliance and engineering governance.

## Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%b %d, %Y" }}</span> — 
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
