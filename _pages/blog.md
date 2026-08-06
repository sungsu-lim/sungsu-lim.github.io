---
permalink: /blog/
title: "Blog"
author_profile: true
layout: archive
---

{% for post in site.posts %}
  <article class="archive__item">
    <h2 class="archive__item-title">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h2>

    <p class="page__meta">
      {{ post.date | date: "%B %-d, %Y" }}
    </p>

    {% if post.excerpt %}
      <p>{{ post.excerpt | strip_html | truncate: 200 }}</p>
    {% endif %}
  </article>
{% endfor %}
