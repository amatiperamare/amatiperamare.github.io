---
title: Blog
date: 2016-07-03 11:55:00 Z
permalink: blog
summary: Amati per amare!
layout: page
---

<section class="post-index">
  {% for article in site.posts %}
    {% include index-article.html %}
  {% endfor %}
</section>      
