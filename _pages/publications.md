---
layout: archive
title: 
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Conference Papers
======

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Journal Papers
======

{% for post in site.posts reversed %}
  {% include archive-single.html %}
{% endfor %}
