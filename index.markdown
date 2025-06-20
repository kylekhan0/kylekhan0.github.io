---
layout: default
title: Welcome to Kyle Khan's Site
---
# Kyle Khan's Website

Welcome to my personal site at [kylekhan.ca](https://kylekhan.ca)! This is a work in progress. kylekhan.com has a certain kind of ring to it so I secured that too :]

## Recent Posts
{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y %H:%M %Z" }}
{% endfor %}