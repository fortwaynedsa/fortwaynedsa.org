---
lang-ref: events
title: Events
---

{% for event in site.events %}
      <h2><a href="{{ event.url }}">{{ event.title }}</a><h2>
      <a href="{{ event.url }}"><img src="{{ event.image }}" style="width: 100%" /></a>
{% endfor %}
