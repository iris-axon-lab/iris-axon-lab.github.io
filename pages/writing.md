---
layout: page
title: Writing
permalink: /posts/
---

Research notes, whitepapers, and half-baked ideas that made it out of the notebook.

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endfor %}