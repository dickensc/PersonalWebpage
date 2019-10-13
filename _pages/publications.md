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

Currently I don't have any publications, so instead I will share with you my favorite paper at the moment!

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
