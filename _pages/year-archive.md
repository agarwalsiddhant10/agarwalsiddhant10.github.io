---
layout: archive
permalink: /blog_posts/
title: "Blog posts"
author_profile: true
---

{% include base_path %}
{% for post in site.blog_posts %}
  {% include archive-single.html %}
{% endfor %}
