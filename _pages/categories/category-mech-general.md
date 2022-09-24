---
title: "General"
layout: archive
permalink: categories/mech-general
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.['mech-general'] %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}