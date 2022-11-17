---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please see also my [Google Scholar profile](https://scholar.google.de/citations?user=s21cwpsAAAAJ&hl=de).


<h2>Conference Papers</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Academic</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'academic' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
