---
title: sample post
author: dave
layout: page
---

{% assign author = site.data.members[0] %}
<a rel="author"
  href="{{ author.name }}"
  title="{{ author.name }}">
    {{ author.name }}
</a>