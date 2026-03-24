---
title: "Talks"
permalink: /talks/
layout: archive
author_profile: true
---

{% include base_path %}

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}