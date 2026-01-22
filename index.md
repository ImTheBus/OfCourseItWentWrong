---
layout: default
title: Home
---

## Of Course It Went Wrong

This book explains the quiet, predictable forces that shape how people behave at work, at home, and in groups. Using clear, memorable principles that feel as inevitable as physical laws, it helps readers recognise why things so often drift off course, why good intentions fail, and why the same problems keep reappearing in different forms. The aim is not blame or theory, but clarity: once you can see the pattern, you can respond to it deliberately instead of being surprised by it.

### Start here
- [Browse categories]({{ "/categories/" | relative_url }})
- [Browse all chapters]({{ "/chapters/" | relative_url }})

### Latest chapters
{% assign latest = site.chapters | sort: "date" | reverse %}
<ul>
{% for c in latest limit:5 %}
  <li><a href="{{ c.url | relative_url }}">{{ c.title }}</a>{% if c.category %} ({{ c.category }}){% endif %}</li>
{% endfor %}
</ul>
