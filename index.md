---
layout: default
title: Home
---

# Of Course It Went Wrong

This site is a set of observations about how people and organisations behave under pressure.
Some patterns reliably pull things off course.
Others reliably pull things back into shape.

Use it as a library of short principles, grouped by theme, with chapters that are either complete, in draft, or marked as coming soon.

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 1.25rem; margin-top: 1.5rem;">

  <section style="border: 1px solid #e6e6e6; border-radius: 12px; padding: 1.25rem;">
    <h2 style="margin-top: 0;">Of Course It Went Wrong</h2>
    <p style="opacity: 0.85; max-width: 55ch;">
      The failure patterns: drift, avoidance, hidden costs, and the quiet forces that make good intentions fail.
    </p>
    <p style="margin: 0.75rem 0 0 0;">
      <a href="{{ '/categories/' | relative_url }}#wrong-capacity-and-structure">Browse categories</a>
      · <a href="{{ '/chapters/' | relative_url }}?book=wrong">Browse chapters</a>
    </p>
  </section>

  <section style="border: 1px solid #e6e6e6; border-radius: 12px; padding: 1.25rem;">
    <h2 style="margin-top: 0;">Of Course It Went Right</h2>
    <p style="opacity: 0.85; max-width: 55ch;">
      The success patterns: what good looks like, why it works, and how to make it repeatable.
    </p>
    <p style="margin: 0.75rem 0 0 0;">
      <a href="{{ '/categories/' | relative_url }}">Browse categories</a>
      · <a href="{{ '/chapters/' | relative_url }}?book=right">Browse chapters</a>
    </p>
  </section>

  <section style="border: 1px solid #e6e6e6; border-radius: 12px; padding: 1.25rem;">
    <h2 style="margin-top: 0;">Everything so far</h2>
    <p style="opacity: 0.85; max-width: 55ch;">
      The full list, in reading order, with draft and coming-soon flags.
    </p>
    <p style="margin: 0.75rem 0 0 0;">
      <a href="{{ '/chapters/' | relative_url }}">All chapters</a>
      · <a href="{{ '/categories/' | relative_url }}">All categories</a>
    </p>
  </section>

</div>

## Latest chapters

{% assign latest = site.chapters | sort: "date" | reverse %}
<ul>
{% for c in latest limit:7 %}
  <li>
    <a href="{{ c.url | relative_url }}">{{ c.title }}</a>
    {% if c.book %} ({{ c.book }}){% endif %}
    {% if c.category %} · {{ c.category }}{% endif %}
  </li>
{% endfor %}
</ul>
