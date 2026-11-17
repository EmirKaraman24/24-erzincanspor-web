<div align="center">

# ⚽ 24 Erzincanspor — Kulüp Web Sitesi & Yönetim Arayüzü

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)

**24 Erzincanspor Futbol Kulübü** için geliştirilmiş, çok sayfalı kurumsal kulüp tanıtım web sitesi ve ön yüz yönetim paneli.

</div>

---

## ✨ Özellikler

### 🌐 Ziyaretçi Sayfaları
- **Ana Sayfa (`index.html`):** Kulüp vitrini, öne çıkan haberler ve hızlı bağlantılar.
- **Haberler & Detay (`haberler.html`, `haber-detay.html`):** Güncel kulüp haberleri ve detay görünümü.
- **Kadro & İstatistikler (`kadro.html`, `istatistikler.html`):** Takım kadrosu ve sezon istatistikleri.
- **Kulüp Mağazası (`magaza.html`):** Taraftar ürünleri vitrini.
- **Hakkımızda & İletişim (`hakkimizda.html`, `iletisim.html`):** Kulüp tarihçesi ve iletişim sayfası.

### 🛠️ Yönetim Arayüzü (`admin/`)
- **Kontrol Paneli (`admin/index.html`):** Genel yönetim ekranı.
- **İçerik Yönetimi:** Haber (`admin/haberler.html`), kadro (`admin/kadro.html`) ve mağaza ürün (`admin/urunler.html`) sayfaları.

---

## 📂 Proje Yapısı

```text
24-erzincanspor-web/
├── admin/                  # Yönetim paneli sayfaları
│   ├── index.html
│   ├── haberler.html
│   ├── kadro.html
│   └── urunler.html
├── css/                    # Bootstrap, global ve sayfa stilleri
├── fonts/                  # İkon ve yazı tipi dosyaları
├── img/                    # Görseller ve kulüp medyaları
├── js/                     # Bootstrap ve jQuery betikleri
├── index.html              # Ana sayfa
├── haberler.html           # Haber listesi
├── haber-detay.html        # Haber detay sayfası
├── kadro.html              # Takım kadrosu
├── istatistikler.html      # İstatistikler
├── magaza.html             # Kulüp mağazası
├── hakkimizda.html         # Hakkımızda
├── iletisim.html           # İletişim
└── admin.html              # Yönetim giriş sayfası
```

---

## 🚀 Yerelde Çalıştırma

Herhangi bir derleme aracı gerektirmez. Projeyi klonlayıp `index.html` dosyasını doğrudan tarayıcıda veya yerel bir HTTP sunucusuyla açabilirsiniz:

```bash
git clone https://github.com/EmirKaraman24/24-erzincanspor-web.git
cd 24-erzincanspor-web
npx serve .
```

---

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) altında sunulmaktadır.
