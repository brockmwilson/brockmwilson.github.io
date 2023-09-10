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

<p style="font-size: 22.5px; text-decoration: underline; font-weight: bold"> Measuring anticipatory behavior of pension policy</p>

<p style="font-size: 1.25em;"> Affirmative action for people with disabilities: who gets hired?</p>

