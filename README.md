# FSM Watermakers — Marine Watermaker Sistemleri

[FSM Watermakers](FSM_Watermakers_Logo)

**Made in Türkiye — Ümraniye / İstanbul merkezli profesyonel deniz suyu arıtma (watermaker) sistemleri için tek sayfalık kurumsal web sitesi.**

🔗 **Canlı Site:** https://bymehmetkurudev.github.io/fsmwatermakers/  
🌐 **Domain:** https://fsmwatermakers.com.tr (CNAME ile bağlı)

> Bu proje `aquawera.com` sitesindeki kategori ve ürün yapısı incelenerek, FSM markasına özel sıfırdan tasarlanmıştır. Kod içinde hiçbir Aquawera / Wera referansı bulunmaz.

---

## 📸 Önizleme

Tek sayfa (one-page) — Hero, Ürünler, Teknoloji, Hizmetler, SSS, İletişim

- Responsive: Mobil, tablet, desktop uyumlu
- Logo sadece görsel olarak kullanılır, yanında metin yok (performans ve minimal tasarım için)
- Tüm içerik `index.html` içinde, harici bağımlılık yok

---

## 🚤 Ürünler

| Model | Kapasite | Hedef Tekne | Güç |
|-------|----------|-------------|-----|
| **FSM 80** | 80 L/h | 32-40 ft yelkenli | 0.9 kW - 62 kg |
| **FSM 150** | 150 L/h | 40-50 ft yat (En popüler) | 1.1 kW - 78 kg |
| **FSM 200** | 200 L/h | 45-60 ft motoryat | 1.5 kW - 92 kg |
| **FSM 350** | 350 L/h | 60ft+ & ticari (Pro-Flow) | 2.2 kW - 128 kg |

Her ürün modalında teknik paket detayı:

- Yüksek basınç pompası Annovi Reverberi - Made in Italy
- Alçak basınç pompası FSM Türkiye Üretimi
- Membran Filmtec - Made in USA (%99.2 tuz giderim)
- SS316 paslanmaz sensör & valf
- GEWISS kontrol paneli - Made in Italy
- Otomatik ters yıkama + uzaktan kumanda kiti
- 230V 50Hz / 12V-24V opsiyon

---

## ✨ Özellikler

- **Tam Otomatik & Uzaktan Kontrollü** - Tek tuşla başlatma
- **Düşük Enerji** - 0.9 - 2.2 kW aralığı
- **Sessiz Çalışma** - < 58 dB
- **60 Bar Test** - Ümraniye atölyede test sertifikalı teslim
- **Marmara Bölgesi Aynı Gün Servis**

---

## ⚡ Performans — 100/100/100/100

Bu site PageSpeed Insights'ta 4 kategoride 100 puan alacak şekilde optimize edildi:

- **Performans 100:** Tailwind CDN kaldırıldı, inline kritik CSS (12KB), 0 render-blocking, logo base64 gömülü, `width/height` + `decoding=async`
- **Erişilebilirlik 100:** Skip link, `aria-label`, `aria-expanded`, `role=dialog`, form `label`, klavye navigasyonu
- **En İyi Uygulamalar 100:** `rel=noopener`, HTTPS, hatasız JS
- **SEO 100:** `canonical`, `theme-color`, Open Graph, Twitter Card, `JSON-LD LocalBusiness`, doğru heading hiyerarşisi

Test edin:
```
https://pagespeed.web.dev/analysis?url=https://bymehmetkurudev.github.io/fsmwatermakers/
```

---

## 🛠️ Teknoloji Stack

- **Pure HTML / CSS / JS** — Framework yok, tek dosya `index.html`
- **No Build Step** — `npm` yok, derleme yok
- **System Font Stack** — Google Fonts isteği yok (Inter/Manrope fallback → system-ui)
- **Base64 Logo** — Harici görsel isteği yok

### Dosya Yapısı
```
/ (root)
├── index.html          # Tam site - tek dosya (optimize 100 puan)
├── index-100.html       # Aynı sitenin PageSpeed 100 versiyonu (logo büyük, yazısız)
├── FSM_Watermakers_Logo # Orijinal logo (JPEG)
├── CNAME               # fsmwatermakers.com.tr (custom domain için)
└── README.md           # Bu dosya
```

---

## 🚀 Kurulum & Çalıştırma

```bash
# 1. Repoyu klonla
git clone https://github.com/ByMehmetKURUDev/fsmwatermakers.git
cd fsmwatermakers

# 2. Lokal önizleme (herhangi bir http server)
python -m http.server 8000
# veya
npx serve .
```

Tarayıcıda `http://localhost:8000` aç.

---

## 🌍 GitHub Pages Deployment

Repo zaten GitHub Pages için hazır:

1. GitHub → **Settings → Pages**
2. **Source:** `Deploy from a branch` → Branch: `main` / `/ (root)` → Save
3. Site 1 dk içinde yayında: `https://bymehmetkurudev.github.io/fsmwatermakers/`

**Custom Domain (fsmwatermakers.com.tr):**
- Pages → Custom domain: `fsmwatermakers.com.tr` yaz
- DNS sağlayıcıda (Natro, GoDaddy vb.):
  - A kayıtları `@` için:
    ```
    185.199.108.153
    185.199.109.153
    185.199.110.153
    185.199.111.153
    ```
  - CNAME `www` → `bymehmetkurudev.github.io`

---

## 📬 İletişim

**FSM Watermakers**

- **Adres:** Natoyolu Caddesi, 236 — ÜMRANİYE / İSTANBUL / Türkiye
- **E-posta:** nurivatankulu@gmail.com
- **Telefon / WhatsApp:** +90 541 501 42 37 — [WhatsApp'a yaz](https://wa.me/905415014237)
- **GitHub:** [@ByMehmetKURUDev](https://github.com/ByMehmetKURUDev)

Teklif formu doldurulduğunda alert ile dönüş mesajı gösterir — backend bağlamak için Formspree / Netlify Forms veya kendi mail API'nizi ekleyebilirsiniz.

---

## 📄 Lisans

Bu tasarım ve kod FSM Watermakers için özel üretilmiştir. Ticari kullanım için izin alın.

© 2026 FSM Watermakers - Tüm Hakları Saklıdır.

---

### English Summary

Single-page corporate site for marine watermaker systems (80-350 L/h). Made in Türkiye, assembled in Ümraniye/Istanbul. Fully optimized for Lighthouse 100/100/100/100, no external dependencies, single `index.html`. Live on GitHub Pages with custom domain `fsmwatermakers.com.tr`.
