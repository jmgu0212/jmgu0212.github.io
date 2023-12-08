---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my full paper list on <u><a href="https://scholar.google.com/citations?user=j1Xe9OIAAAAJ&hl=zh-CN">my Google Scholar profile</a>.</u>

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- {% include base_path %}


{% assign lastYear = '' %}

{% for post in site.publications reversed %}

  {% assign paperYear = post.paperYear %}

  {% if paperYear != lastYear %}
    {% include year.html %}
    {% assign lastYear = paperYear %}
  {% endif %}

  {% include archive-single.html %}

{% endfor %} -->