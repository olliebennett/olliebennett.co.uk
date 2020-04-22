---
layout: default
title: Thoughts
description: Ollie's posts
categories: none
---

## Thoughts

{% for post in site.posts %}
  <div class="post">
    {% if post.title %}
      <h3>
        {{ post.title }}
        {% if post.source %}
          <small>- <a href="{{ post.source }}">source</a></small>
        {% endif %}
      </h3>
    {% endif %}

    {{ post.content }}
  </div>
{% endfor %}
