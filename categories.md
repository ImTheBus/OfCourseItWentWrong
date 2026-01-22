---
layout: default
title: Categories
permalink: /categories/
---

## Categories

{% assign cats = site.chapters | map: "category" | uniq | sort %}
<ul>
{% for cat in cats %}
  {% if cat %}
    <li><a href="#{{ cat | slugify }}">{{ cat }}</a></li>
  {% endif %}
{% endfor %}
</ul>

{% for cat in cats %}
  {% if cat %}
    <h3 id="{{ cat | slugify }}">{{ cat }}</h3>
    {% assign items = site.chapters | where: "category", cat | sort: "order" %}
    <ul>
      {% for c in items %}
        <li>
          <a href="{{ c.url | relative_url }}">{{ c.order | default: "?" }}. {{ c.title }}</a>
          {% if c.status %} · <em>{{ c.status }}</em>{% endif %}
          {% if c.summary %}<div style="margin:0.15rem 0 0.6rem 0;">{{ c.summary }}</div>{% endif %}
        </li>
      {% endfor %}
    </ul>
  {% endif %}
{% endfor %}
