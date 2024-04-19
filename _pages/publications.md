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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


## Journal Paper
1. [Wang, P., Wang, J., Jin, R., Li, G., Zhou, M., & Xia, Q. (2022). Integrating biogas in regional energy systems to achieve near-zero carbon emissions. Applied Energy, 322, 119515.](https://www.sciencedirect.com/science/article/abs/pii/S0306261922008364)
