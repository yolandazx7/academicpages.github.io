---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
My research interest is the economics of intellectual property and innovation, corporate innovation strategy, and digitization and digital platform strategy. My research develops novel methods to measure innovation, explores the fundamental forces that drives firms' decision on public disclosure of innovation activities, and investigates how patent right enforcement impacts innovation disclosure.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
  <ul>
      {% for post in site.research | sort:"order_number" %}
    {% include archive-single.html %}
  {% endfor %}</ul>
