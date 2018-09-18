---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a full list of my articles and preprints on <ins>[my Google Scholar profile](https://scholar.google.com/citations?user=qETQrrkAAAAJ&hl=en)</ins>.

{% if author.googlescholar %}
 You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
