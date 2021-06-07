---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
My research interest is the economics of intellectual property and innovation, corporate innovation strategy, and digitization and digital platform strategy. My research falls into two main areas: exploring the impact of patent enforcement on invention and innovation activity, and developing new method to measure innovation and examine the heterogenous impact of innovation on firm performance.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
  <ul>
      {% for post in site.research | sort:"order_number" %}
    {% include archive-single.html %}
  {% endfor %}</ul>
