---
layout: default
title: Blog
description: Ollie's posts
categories: none
---

# Blog Posts

<div id="posts">
  <ul>
    {% for post in site.posts %}
      {% if post.title %}
        <li><a href="{{ post.url | remove:'index.html' }}">{{ post.title }} <small>[{{ post.date | date_to_string }}]</small></a></li>
      {% endif %}
    {% endfor %}
  </ul>
</div>
