---
layout: page
title: "Archive"
---

## Blog Posts

{% for post in posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}

