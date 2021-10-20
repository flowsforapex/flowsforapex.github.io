---
title: "Blog"
permalink: /blog/
layout: archive
author_profile: true
---
{% for post in site.posts %}
  {% include post-list.html %}
{% endfor %}