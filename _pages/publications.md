---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Download paper here](http://waqar54.github.io/respiromics/files/Volatilomes of human infection 2023.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
