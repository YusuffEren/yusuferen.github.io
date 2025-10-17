---
layout: page
title: Blog
permalink: /blog/
---

# Blog Yazıları

Yazılım geliştirme, teknoloji ve öğrendiklerimi paylaştığım alan.

---

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})

**Tarih:** {{ post.date | date: "%d %B %Y" }}

{{ post.excerpt }}

[Devamını oku →]({{ post.url }})

---
{% endfor %}

{% if site.posts.size == 0 %}
*Henüz blog yazısı eklenmemiş. İlk yazıyı paylaşmak için `_posts` klasörüne Markdown dosyası ekleyin.*
{% endif %}
