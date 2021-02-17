---
layout: default
title: Notes
description: Ollie's Notes
categories: none
---

## Notes

{% assign notes = site.notes | reverse %}
{% for note in notes %}
  <div class="note">
    <h3>
      <a href="{{ note.url }}">{{ note.title }}</a>
      {% for cat in note.categories %}
        <span class="skill skill-expert">{{ cat }}</span>
      {% endfor %}
    </h3>

    {{ note.excerpt }}
  </div>
{% endfor %}
