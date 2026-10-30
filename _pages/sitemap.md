---
layout: archive
title: Sitemap
permalink: /sitemap/
author_profile: false
---

A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ “sitemap.xml” | relative_url }}) available for digesting as well.

## Pages
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

## Posts
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

