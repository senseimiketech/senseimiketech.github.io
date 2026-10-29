---
layout: splash
permalink: /
---

## Welcome!

{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}
