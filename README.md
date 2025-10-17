# Kişisel Portföy ve Blog Sitesi

Jekyll ve GitHub Pages kullanılarak oluşturulmuş minimal kişisel web sitesi.

## Özellikler

- 📄 Portföy sayfası
- ✍️ Blog desteği
- 🎨 Minimal ve temiz tasarım
- 🚀 GitHub Pages ile ücretsiz hosting

## Nasıl Kullanılır?

### Kişisel Bilgilerinizi Güncelleyin

1. `_config.yml` dosyasını açın
2. `title`, `description`, `author`, `email` alanlarını kendi bilgilerinizle güncelleyin
3. Sosyal medya kullanıcı adlarınızı ekleyin

### Portföy Sayfasını Düzenleyin

`about.md` dosyasını düzenleyerek:
- Yeteneklerinizi ekleyin/çıkarın
- Projelerinizi ekleyin
- Eğitim ve iş deneyimlerinizi güncelleyin

### Blog Yazısı Ekleme

`_posts` klasöründe yeni bir dosya oluşturun:
- Dosya adı formatı: `YYYY-MM-DD-baslik.md`
- Örnek: `2025-10-17-yeni-yazim.md`

Dosya içeriği:
```markdown
---
layout: post
title: "Yazı Başlığı"
date: 2025-10-17
categories: kategori
---

Yazı içeriği buraya...
```

## GitHub Pages'e Deploy Etme

1. GitHub'da yeni bir repository oluşturun (adı: `username.github.io`)
2. Bu projeyi repository'ye push edin:
   ```bash
   git init
   git add .
   git commit -m "İlk commit"
   git branch -M main
   git remote add origin https://github.com/username/username.github.io.git
   git push -u origin main
   ```
3. Repository Settings > Pages bölümünden GitHub Pages'i aktifleştirin
4. Siteniz `https://username.github.io` adresinde yayında olacak!

## Yerel Geliştirme (Opsiyonel)

Jekyll'i yerel olarak çalıştırmak için:

```bash
bundle install
bundle exec jekyll serve
```

Tarayıcıda `http://localhost:4000` adresini açın.

## Lisans

MIT
