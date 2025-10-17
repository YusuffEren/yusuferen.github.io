---
layout: home
title: Ana Sayfa
---

# Merhaba! Ben [İsminiz]

Yazılım geliştirici, problem çözücü ve teknoloji meraklısı.

## Ne Yapıyorum?

- 💻 Full-stack web geliştirme
- 🎨 Kullanıcı deneyimi ve arayüz tasarımı
- 📱 Mobil uygulama geliştirme
- ✍️ Teknik yazılar ve blog yazıları

## Son Blog Yazılarım

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d %B %Y" }}
{% endfor %}

[Tüm blog yazılarını gör →](/blog)

---

## İletişim

Benimle [email@example.com](mailto:email@example.com) üzerinden iletişime geçebilirsiniz.
