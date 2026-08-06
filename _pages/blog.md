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
      {% if post.categories %}
        · {{ post.categories | join: ", " }}
      {% endif %}
    </p>

    {% if post.excerpt %}
      <p>{{ post.excerpt | strip_html | truncate: 180 }}</p>
    {% endif %}

    {% if post.tags %}
      <p>
        {% for tag in post.tags %}
          <span class="page__meta">#{{ tag }}</span>{% unless forloop.last %} &nbsp; {% endunless %}
        {% endfor %}
      </p>
    {% endif %}

  </article>
{% endfor %}
