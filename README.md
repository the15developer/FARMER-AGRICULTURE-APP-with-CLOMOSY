# AgroTrack – Tarım Takip ve Danışmanlık Mobil Uygulaması

Bu proje, üniversite ikinci zorunlu yaz stajım kapsamında geliştirdiğim **üçüncü projedir** ve **8 gün içerisinde** tamamlanmıştır. Uygulamanın amacı, çiftçilerin günlük tarımsal faaliyetlerini dijital ortamda daha düzenli ve verimli bir şekilde yürütebilmelerine yardımcı olmaktır.

---

## Proje Açıklaması

AgroTrack, çiftçilerin mahsul takibi yapmasını, hava durumunu kontrol etmesini, yatırım kategorilerine göre yeni mahsuller keşfetmesini ve yapay zeka destekli öneriler almasını sağlayan mobil tabanlı bir platformdur. Uygulama, **Clomosy** platformu üzerinde geliştirilmiş olup **SQLite** veritabanı kullanmaktadır.

---

##  1. Giriş (Login) ve Yeni Kullanıcı Sayfası

Uygulama, kullanıcıyı ilk olarak AgroTrack’e ait logo ile karşılar. Ardından kullanıcı, modern tasarıma sahip giriş ekranına yönlendirilir. Eğer hesabı yoksa "Yeni Kullanıcı" seçeneği ile kayıt olabilir. Giriş ve kayıt ekranlarında kullanıcı adı/parola doğrulama gibi temel kontroller ivedilikle yapılır.

** Ekran Görüntüsü:**
![Intro Ekranı](introImage.jpeg)
![Login ve Yeni Kullanıcı](login.jpeg)
![Login ve Yeni Kullanıcı](newuser.jpeg)

---

## 2. Ana Sayfa – Hava Durumu, Tarım İpucu ve Sohbet

Ana sayfada, lokasyon bazlı hava durumu, her gün değişen tarım ipuçları ve kullanıcının ekili mahsulleri görsel kartlar şeklinde sunulur. Ayrıca, yatırım kategorisine göre önerilen mahsul kartları da burada yer alır.

En dikkat çeken özellik ise Gemini API ile entegre edilen yapay zeka destekli sohbet panelidir. Kullanıcılar, metin veya görsel göndererek yapay zekadan destek alabilir.

** Ekran Görüntüsü:**
![Ana Sayfa](mainPage.jpeg)
![Ana Sayfa](mainPage.jpeg)
![Ana Sayfa](mainPage.jpeg)

---

## 3. Yatırım Önerileri Sayfası

Kullanıcı, bu sayfada dört yatırım kategorisinden birini seçebilir: Düşük Risk, Yüksek Getiri, Güvenlik ve Hızlı Yetişen Mahsuller. Seçilen kategoriye göre ekranda önerilen mahsuller, görselli kart formatında detaylı bilgilerle birlikte gösterilir.

**Ekran Görüntüsü:**
![Yatırım Önerileri Sayfası](guide1.jpeg)
![Yatırım Önerileri Sayfası](guide2.jpeg)
![Yatırım Önerileri Sayfası](guide3.jpeg)
![Yatırım Önerileri Sayfası](guide4.jpeg)
![Yatırım Önerileri Sayfası](guide5.jpeg)

---

## 4. Ekili Mahsullerim Sayfası

Bu sayfa, kullanıcının geçmişte ektiği mahsulleri listelediği alandır. Her mahsul için fotoğraf, ekim tarihi, kullanıcı notları gibi bilgiler yer alır. Yeni mahsul eklerken kullanıcı fotoğrafı:
- Anında kamera ile çekebilir,
- Telefona kayıtlı görseli seçebilir,
- Veya bir görsel URL’si girebilir.

**Ekran Görüntüsü:**
![Ekili Mahsullerim Sayfası](planner1.jpeg)
![Ekili Mahsullerim Sayfası](planner2.jpeg)
![Ekili Mahsullerim Sayfası](planner3.jpeg)
![Ekili Mahsullerim Sayfası](planner4.jpeg)

---

## 5. Kullanıcı Profili Sayfası

Kullanıcı adı, tam adı ve e-posta adresinin gösterildiği sade ve anlaşılır bir profil sayfasıdır. Karmaşık tasarım öğeleri içermeyen bu sayfa, kullanıcıya hızlı bilgi sunar.

**Ekran Görüntüsü:**
![Kullanıcı Sayfası](user.jpeg)


---

## Planlanan Geliştirmeler

- Ekili mahsulleri düzenleme ve silme özellikleri
- Yapay zekaya hastalık ve zararlı tespiti için daha detaylı analiz sistemleri
- Maliyet takibi ve yatırım planlama modülü
- Sohbet paneli için çok dilli destek

---

## Teknik Bilgiler

- **Platform:** Clomosy
- **Veritabanı:** SQLite
- **Yapay Zeka:** Google Gemini API
- **Dil:** TRObject Script (Clomosy'nin görsel kodlama sistemi)

---

## Teknolojiler, metotlar

- Clomosy ve TRObject programlama dili ile mobil uygulama geliştirme
- SQLite veritabanı kullanımı
- Yapay zeka API entegrasyonu
- UI/UX tasarımı ve kullanıcı deneyimi düzenlemeleri
- Sanal klavye yönetimi, görsel kart sistemleri ve timer tabanlı olay kontrolü


