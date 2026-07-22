# 📸 Görsel Ekleme Rehberi — Tarihi Çukurova Tantuni Web Sitesi

Tüm görsel dosyaları şu klasörde bulunur:
**`luuma.com.tr/assets/frontend/images/`**

---

## 🖼️ ANASAYFA GÖRSELLERİ (`index.html`)

### Hero (Karşılama) Slider Arkaplanları
Sayfanın en üstündeki büyük tam ekran slayt arka planları.

| Dosya Adı | Nerede Görünür | Önerilen Boyut |
|---|---|---|
| `anasayfa-hero-slider-1.jpg` | 1. slayt arkaplanı (üstte) | 1920x1080 px |
| `anasayfa-hero-slider-2.jpg` | 2. slayt arkaplanı | 1920x1080 px |

### Hakkımızda Bölümü İçerik Fotoğrafları
Sağ tarafta üst üste binen 3 adet fotoğraf.

| Dosya Adı | Nerede Görünür | Önerilen Boyut |
|---|---|---|
| `anasayfa-fotograf-1.jpg` | Hakkımızda bölümü — büyük fotoğraf | 700x800 px |
| `anasayfa-fotograf-2.jpg` | Hakkımızda bölümü — küçük yuvarlak fotoğraf 1 | 300x300 px |
| `anasayfa-fotograf-3.jpg` | Hakkımızda bölümü — küçük yuvarlak fotoğraf 2 | 300x300 px |

---

## 🏛️ KURUMSAL SAYFA GÖRSELLERİ (`kurumsal/index.html`)

| Dosya Adı | Nerede Görünür | Önerilen Boyut |
|---|---|---|
| `kurumsal-fotograf-1.jpg` | "Hikayemiz" bölümü fotoğrafı | 600x700 px |
| `kurumsal-fotograf-2.jpg` | "SSS" bölümü yanındaki fotoğraf | 600x700 px |
| `sayfa-baslik-arkaplan.jpg` | Tüm iç sayfaların üst banner arkaplanı | 1920x600 px |

---

## 🌐 TÜM SAYFALARDA ORTAK ARKAPLANLAR (CSS ile yönetilir)

Bu görseller CSS dosyasında tanımlıdır:
**`luuma.com.tr/assets/frontend/css/custom_v=20260615.css`**

| Dosya Adı | Hangi Bölümde | Not |
|---|---|---|
| `altbilgi-arkaplan.jpg` | Footer (en alt bölüm) arkaplanı | 1920x600 px |
| `hakkimizda-dekoratif-arkaplan.png` | Hakkımızda bölümü dekoratif arka desen | Şeffaf PNG |
| `neden-bizi-secin-arkaplan.png` | "Neden Bizi Seçin" bölümü arkaplanı | Şeffaf PNG |
| `tanitim-video-arkaplan.jpg` | Video/tanıtım bölümü arkaplanı | 1920x1080 px |
| `fiyatlar-bolumu-arkaplan.png` | Fiyat listesi bölümü arkaplanı | Şeffaf PNG |
| `kampanyalar-bolumu-arkaplan.png` | Kampanyalar bölümü arkaplanı | Şeffaf PNG |
| `musteri-yorumlari-arkaplan.jpg` | Müşteri yorumları bölümü arkaplanı | 1920x800 px |
| `harekete-gecirme-arkaplan.png` | CTA butonu bölümü arkaplanı | Şeffaf PNG |
| `restoran-dekoratif-desen.svg` | Restoran bölümü dekoratif desen | SVG vektör |

---

## 🖥️ MENÜ SAYFASI (`menu/index.html`)

| Dosya Adı | Nerede Görünür |
|---|---|
| `sayfa-baslik-arkaplan.jpg` | Menü sayfası üst başlık arkaplanı |
| Her ürün için ayrı fotoğraf | `menu-placeholder.jpg` klasörüne ürün adıyla ekleyin |

---

## ✅ Görsel Nasıl Eklenir?

1. Fotoğrafınızı hazırlayın (önerilen boyutlara dikkat edin)
2. Dosyayı yukarıdaki tabloda yazan **isimle** kaydedin
3. `luuma.com.tr/assets/frontend/images/` klasörüne kopyalayın
4. Sayfayı yenileyin — görsel otomatik olarak yerleşecektir!

> **Not:** Arka plan görselleri için yatay, geniş fotoğraflar; içerik görselleri için dikey fotoğraflar tercih edin.
