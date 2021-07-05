---
lang-ref: events
title: <!-- optional metadata -->
description: <!-- optional metadata -->
headline: <!-- optional display text -->
subhead: <!-- optional display text -->
---

<ul>
  {% for event in site.events %}
    <li>
      <a href="{{ event.url }}">{{ event.title }}</a>
    </li>
  {% endfor %}
</ul>
