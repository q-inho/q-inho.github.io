---
title: "General"
layout: archive
permalink: categories/general
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.['General'] %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}