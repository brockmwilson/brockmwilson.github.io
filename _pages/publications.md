---
layout: archive
title: "Research"
permalink: /publications/
header:
  image: teton-pano-small.jpg
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Measuring anticipatory behavior of pension policy

Affirmative action for people with disabilities: who gets hired?
