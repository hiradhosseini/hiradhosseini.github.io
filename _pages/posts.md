---
permalink: /posts/
title: "Page not in menu"
excerpt: "This is a page not in th emain menu"
author_profile: true
redirect_from: 
  - "/posts.html"
---

{% include base_path %}

{% for post in site.posts reversed %}
  {% include archive-single.html %}
{% endfor %}
