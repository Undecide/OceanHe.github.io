---
layout: archive
permalink: /publications/
title: "Publications"
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">1my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-new.html %}
{% endfor %}

<sup>**</sup> Equal authorship