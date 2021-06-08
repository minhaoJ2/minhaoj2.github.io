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

# 2021

* Huajie Shao, Tarek Abdelzaher, Sam Cohen, James Flamino, Jiawei Han, **Minhao Jiang**, et al. 2021. ”SimulatingOnlineSocialResponse:a Stimulus/response Perspective”. In 2021 Winter Simulation Conference (*WSC'2021*). 
