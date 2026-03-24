---
title: "Publications"
permalink: /publications/
layout: archive
author_profile: true
---

(* Equal contribution; † Corresponding author)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}