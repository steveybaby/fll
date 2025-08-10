---
layout: default
title: Blog
---

# Blog Posts

<ul>
{% for post in site.posts %}
  <li>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <span>{{ post.date | date: "%B %d, %Y" }}</span>
    {% if post.excerpt %}
      <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    {% endif %}
  </li>
{% endfor %}
</ul>