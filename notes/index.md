---
layout: page
title: "Operating Notes"
description: "Pattern observations, structural insights, and lessons from practice — by Eric de Morgoli."
permalink: /notes/
hide_cta: true
timestamp: [2026-05-04 12:29]
---

Short-form observations from practice. Each note answers one question: *what was there to notice that had been missed?*

{% comment %} 
  Filter by 'path', which looks at the actual file location on disk.
  This is much more reliable than checking the generated URL.
{% endcomment %}

{% assign notes = site.pages | where_exp: "p", "p.path contains 'notes/'" | where_exp: "p", "p.path != 'notes/index.md'" | sort: "date" | reverse %}

<div class="case-cards">
{% for note in notes %}
  <a href="{{ note.url | relative_url }}">
    {% comment %} Ensure a fallback date exists if 'date' is missing {% endcomment %}
    {{ note.date | default: 'n/a' | date: "%B %d, %Y" }}
    <h3>{{ note.title }}</h3>
    {% if note.description %}<p>{{ note.description }}</p>{% endif %}
    <hr>
  </a>
{% endfor %}
</div>
