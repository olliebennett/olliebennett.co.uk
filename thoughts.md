---
layout: default
title: Thoughts
description: Ollie's thoughts
categories: none
---

## Thoughts

{% for thought in site.thoughts %}
  <div class="thought">
    {% if thought.title %}
      <h3>
        {{ thought.title }}
        {% if thought.source %}
          {% if thought.source contains 'http://' or thought.source contains 'https://' %}
            <small>- <a href="{{ thought.source }}">source</a></small>
          {% else %}
            <small>- source: {{ thought.source }}</small>
          {% endif %}
        {% endif %}
      </h3>
    {% endif %}

    {{ thought.content }}
  </div>
{% endfor %}
