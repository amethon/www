---
title: gallery
layout: default
nav: /
tweets:
  - https://twitter.com/amethon/status/1565251475676463104
---

# twitter
{% for tweet in page.tweets %}
  {% twitter tweet align=right maxwidth=800 %}
{% endfor %}