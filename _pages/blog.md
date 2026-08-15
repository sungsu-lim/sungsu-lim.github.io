---
permalink: /blog/
title: "Blog"
author_profile: true
layout: default
---

# 📝 Blog

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %-d, %Y" }}*

{% if post.excerpt %}
{{ post.excerpt | strip_html | truncate: 180 }}
{% endif %}

---
{% endfor %}
