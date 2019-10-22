---
layout: archive
permalink: /capstone-project/
title: "IMA Capstone Posts by tags"
author_profile: true
header:
    image: "/images/min/mapping-manhattan.jpg"
---
{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}