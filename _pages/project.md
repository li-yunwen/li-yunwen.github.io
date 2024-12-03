---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
toc: true
---

{% assign category_order = "Healthcare, Path planning, Robot arm, Virtual reality" | split: ", " %}

{% for category in category_order %}
## {{ category }}

    {% assign projects_in_category = site.projects | where: 'category', category | sort: 'date' | reverse %}

    {% for post in projects_in_category %}
        {% include archive-single.html %}
    {% endfor %}

{% endfor %}
