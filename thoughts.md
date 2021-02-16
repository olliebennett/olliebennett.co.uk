---
layout: default
title: Thoughts
description: Ollie's thoughts
categories: none
---

## Thoughts

{% assign thoughts = site.thoughts | reverse %}
{% for thought in thoughts %}
  <div class="thought">
    <h3>
      {{ thought.title }}
      {% for cat in thought.categories %}
        <span class="skill skill-expert">{{ cat }}</span>
      {% endfor %}
    </h3>

    {{ thought.content }}

    {% if thought.source_url and thought.source_title %}
      <p>Source: <a href="{{ thought.source_url }}">{{ thought.source_title }}</a></p>
    {% elsif thought.source_url %}
      <p><a href="{{ thought.source_url }}">Source</a></p>
    {% elsif thought.source_title %}
      <p>Source: {{ thought.source_title }}</p>
    {% endif %}
  </div>
{% endfor %}
