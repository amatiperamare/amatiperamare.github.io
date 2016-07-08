---
title: Blog
date: 2016-07-08 23:42:00 +02:00
permalink: blog
summary: Amati per amare :D
---

<section class="post-index">
  {% for article in site.posts %}
    {% include index-article.html %}
  {% endfor %}
</section>      