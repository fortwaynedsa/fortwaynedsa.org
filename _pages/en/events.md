---
lang-ref: events
title: Events
---

<ul>
  {% for event in site.events %}
    <li>
      <a href="{{ event.url }}">{{ event.title }}</a>
    </li>
  {% endfor %}
</ul>
