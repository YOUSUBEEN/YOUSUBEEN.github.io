---
title: "Mini Project"
layout: archive
permalink: /miniproject
---


{% assign posts = site.categories.mini-project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}