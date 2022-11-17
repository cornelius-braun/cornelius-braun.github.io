---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

<p>Please see also my <a href="https://scholar.google.de/citations?user=s21cwpsAAAAJ&hl=de" style="text-decoration: none">Google Scholar profile</a>.</p>

<h2 style="margin-bottom: -20px;">Conference Papers</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2 style="margin-bottom: -20px;">Academic</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'academic' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

