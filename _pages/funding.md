---
layout: archive
title: "Funding"
permalink: /funding/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.funding reversed %}
  {% include archive-single.html %}
{% endfor %}
