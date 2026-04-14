---
layout: page
title: Writing
permalink: /posts/
---

Research notes, whitepapers, and half-baked ideas that made it out of the notebook.

{% assign writing_posts = "" | split: "" %}
{% if site.categories.writing %}
  {% assign writing_posts = site.categories.writing | sort: 'date' | reverse %}
{% endif %}
{% for post in writing_posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.description }}

---
{% endfor %}