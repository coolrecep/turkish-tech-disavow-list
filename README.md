# 🛡️ Turkish Tech Sites Negative SEO & Spam Disavow List

Bu repository, Türkiye merkezli teknoloji yayınlarını, forumları ve içerik üreticilerini hedef alan **Negatif SEO (Negative SEO)** saldırılarına karşı bir topluluk savunma hattı oluşturmak amacıyla kurulmuştur. 

Sektördeki büyük sitelere (Techolay vb.) yapılan sistematik saldırılardan elde edilen verilerle derlenen bu liste, Google Search Console üzerinden zararlı bağlantıları reddetmek (disavow) için kullanılır.

## 🛠️ Neleri Kapsar?

Bu liste, aşağıdaki zararlı bağlantı türlerini otomatik ve manuel incelemelerle filtreler:

* **Adult & Illegal Anchor Spam:** Sitenizi yasa dışı veya yetişkin içerikli anahtar kelimelerle ilişkilendirmeye çalışan bağlantılar.
* **Gambling & Betting Networks:** Sistematik bahis ve kumar sitesi backlink saldırıları.
* **BHS & SEO Anomaly:** Otomatik oluşturulmuş paravan blog (PBN) ağları.
* **Scraper Bots & Cloudflare Pages Spam:** İçerik hırsızlığı yapan botlar ve düşük kaliteli `pages.dev` saldırıları.
* **Hacked Redirects:** Güvenliği ihlal edilmiş siteler üzerinden gelen zehirli yönlendirmeler.

## 📥 Nasıl Kullanılır?

1.  Bu depodaki en güncel [disavow.txt](./disavow.txt) dosyasını indirin.
2.  Dosyayı bir metin düzenleyici ile açıp, kendi sitenize özel faydalı olabilecek backlinklerin yanlışlıkla listede olup olmadığını hızlıca gözden geçirin.
3.  [Google Search Console Bağlantıları Reddetme Aracı](https://search.google.com/search-console/disavow-links) adresine gidin.
4.  İlgili mülkünüzü seçin ve hazırladığınız dosyayı yükleyin.

> **Not:** Eğer daha önceden bir disavow listeniz varsa, bu listedeki satırları mevcut dosyanızın sonuna ekleyerek yüklemeniz önerilir.

## 🤝 Katkıda Bulunun

Spam ağları her gün değişiyor. Sitenize yapılan yeni bir saldırı dalgası fark ederseniz veya listede olmaması gereken bir domain (false-positive) görürseniz lütfen katkıda bulunun:

1.  Yeni bir **Issue** açarak durumu bildirin.
2.  Domain eklemek veya çıkarmak için bir **Pull Request** gönderin.

---
**Başlatan:** [Recep Baltaş](https://github.com/recepbaltas)  
**Lisans:** MIT - Bu liste topluluğun faydası için ücretsiz ve açık kaynaklıdır.
