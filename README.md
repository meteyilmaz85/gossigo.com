# GossiGo web sayfaları

İki bağımsız, Türkçe landing page bulunur. Yeni tasarım eklenirken `index.html` değiştirilmemiştir.

| Sayfa | Dosya | Yayınlandıktan sonraki adres |
| --- | --- | --- |
| İlk tasarım (koyu tema) | `index.html` | `/` veya `/index.html` |
| Yeni tasarım (açık tema) | `gossigo.html` | `/gossigo.html` |

Her iki HTML dosyasını aynı dizinde yayınlamak yeterlidir. Yeni sayfanın altındaki “İlk tasarımı görüntüle” bağlantısı eski sayfaya gider. Repo, GitHub Pages üzerinden `master` branch’inin kök dizininden yayınlanır; iki sayfa da aynı yayına dahildir.

## Yerel önizleme

Dosyaları tarayıcıda doğrudan açabilir veya repo dizininde basit bir sunucu başlatabilirsiniz:

```sh
python3 -m http.server 8000
```

- İlk tasarım: http://localhost:8000/
- Yeni tasarım: http://localhost:8000/gossigo.html

Derleme veya paket kurulumu gerekmez. Yeni sayfa JavaScript kullanmaz; soru-cevap bölümü tarayıcının yerleşik `details` bileşeniyle çalışır. Yazı tipleri Google Fonts’tan yüklenir; bağlantı olmadığında sistemin sans-serif yazı tipi kullanılır.

Uygulama örnekleri temsilidir. Erken erişim bağlantıları mevcut sayfadaki `info@startyazilim.com` adresine e-posta oluşturur; form verisi toplanmaz. Mağaza durumu ve uygulama özellikleri mevcut `index.html` içeriği temel alınarak yazılmıştır; uygulama yayınlandığında mağaza bağlantıları ve “yakında” metinleri güncellenmelidir.
