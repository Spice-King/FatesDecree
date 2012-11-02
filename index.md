---
layout: page
title: Home
tagline: Where the cool kids hang out
---
{% include JB/setup %}

Put content here. Lots of it, please?

News:
{% assign posts = site.posts %}
{% assign listing_limit = 5 %}
{% include post-listing.html %}