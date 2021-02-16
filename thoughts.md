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
      <a href="{{ thought.url }}">{{ thought.title }}</a>
      {% for cat in thought.categories %}
        <span class="skill skill-expert">{{ cat }}</span>
      {% endfor %}
    </h3>

    {{ thought.excerpt }}
  </div>
{% endfor %}
