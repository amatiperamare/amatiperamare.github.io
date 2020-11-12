---
title: LIBRI
date: 2020-11-12 01:20:00 +01:00
permalink: libri
summary: Libri per riflettere su sé, l'altro. Dio
---

<section class="post-index">
{% for article in site.libri %} 
{% include index-article.html %}
{% endfor %}
</section>