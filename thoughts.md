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
          {% assign source_protocol = post.source | split: ":" | first %}
          {% if source_protocol == 'http' or source_protocol == 'https' %}
            <small>- <a href="{{ post.source }}">source</a></small>
          {% else %}
            <small>- source: {{ post.source }}</small>
          {% endif %}
        {% endif %}
      </h3>
    {% endif %}

    {{ post.content }}
  </div>
{% endfor %}
