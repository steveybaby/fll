---
layout: default
title: Home
---

# Welcome to My Website

This is a simple website built with Jekyll and hosted on GitHub Pages. Here you'll find my blog posts, photos, and more about me.

## Recent Posts

<ul>
{% for post in site.posts limit:5 %}
  <li>
    <span>{{ post.date | date: "%B %d, %Y" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

[View all posts →](/blog/)

## Featured Photos

Check out some of my latest photos in the [photo gallery](/photos/).