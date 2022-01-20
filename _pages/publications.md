---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.arXiv %}
  You can also some of my articles on <u><a href="{{author.arXiv}}">my arXiv profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
