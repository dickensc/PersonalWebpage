---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

For the most up to date reference of publications see the [LINQS publications webpage](https://linqs.github.io/linqs-website/publications/).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
