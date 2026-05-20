# ⚡ LogiQ - Digital Logic University

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)

**LogiQ**, mühendislik öğrencileri ve dijital tasarım meraklıları için geliştirilmiş, interaktif ve kapsamlı bir eğitim uygulamasıdır. İçerisinde yer alan dinamik lojik motorları, gerçek zamanlı devre çizimleri ve akademik çözüm algoritmaları sayesinde dijital sistem tasarımını ezberlemeden öğrenmenizi sağlar.

## 🚀 Temel Özellikler

* 🎓 **Karşılama ve Onboarding (Welcome Screen):** Uygulama, mühendislik hissiyatı veren özel devre ikonları ve "Sonsuz Soru • Görsel Çözüm • Sınav Simülasyonu" vizyonuyla kullanıcıyı motive eden bir tasarımla açılır.
* 📚 **Dijital Tasarım Okulu (Konu Anlatımı):** Mantık Kapılarından FSM ve Bellek mimarilerine kadar 8 ana kategoride mühendislik düzeyinde, adım adım ders notları sunar.
* ♾️ **Sonsuz Alıştırma Modu:** Dinamik olarak üretilen grafikli ve metin bazlı sorular (Sözel/Sayısal filtrelemeli). Anında geri bildirim ve akademik çözüm incelemesi sağlar.
* ⏱️ **Final Sınavı Simülasyonu:** 30 dakika süreli, tüm konulardan karma 20 soruluk zaman kısıtlamalı sınav. AA'dan FF'e kadar harf notu hesaplaması ve sınav sonu detaylı hata analizi içerir.
* 🛠️ **Soru Atölyesi (Kendi Soruların):** Kullanıcıların kendi çalışma notlarını ve sorularını ekleyip cihaz hafızasında güvenle saklayabileceği özel alan.
* 🌍 **Topluluk Soru Bankası:** 2009-2023 yılları arası gerçek üniversite soru arşivleri. (Ödüllü reklam ile açılan OCD motoru destekli akademik çözümler barındırır).
* 📊 **Öğrenci Karnesi (İstatistikler):** Doğru/yanlış oranlarına göre başarı yüzdesi hesaplar ve "Usta", "Orta", "Çalışman Lazım" gibi statülerle gelişimi takip eder.

## 🧠 Lojik Motorlar (Logic Engines)

Uygulama statik görseller yerine çalışma anında (runtime) render edilen güçlü motorlara sahiptir:
* **Advanced Circuit Painter:** Mantık kapılarını hiyerarşik çizer. Çözüm modunda Lojik 1 (Yeşil) ve 0 (Kırmızı) renkleri ile devreden geçen akımı simüle eder.
* **Dynamic Graph Painter:** Zaman düzleminde Waveform, State Diagram (FSM geçişleri) ve Logic Analyzer grafiklerini çizer.
* **Schema Painter:** D-FF, JK-FF, T-FF ve SR-Latch gibi donanım elemanları için evrensel kutu şemaları üretir.
* **OCD & Infinite Engines:** Algoritmik olarak soru üretir ve soruların türünü analiz ederek akademik, adım adım çözüm metinleri oluşturur.

## 🏗️ Teknik Mimari ve UI

* **Reaktif State Management:** `Provider` mimarisi kullanılmıştır. Özellikle `GameProvider` ile anlık soru geçişleri, 30 dakikalık sınav sayacı ve ipucu döngüsü kusursuz yönetilir.
* **Çevrimdışı (Offline) Destek:** Temel eğitim modülleri, statik soru havuzu, eklenen özel sorular ve öğrenci istatistikleri tamamen yerel cihazda (`SharedPreferences` ve asset bazlı) tutulur. Uygulama reklamsız kısımlarda **%100 offline** çalışabilir.
* **Karanlık Tema ve Mühendislik UI:** Tasarım dili olarak göz yormayan, uzun süreli odaklanmayı kolaylaştıran **"Dark Theme"** (`AppColors` yapısı ile) tercih edilmiştir.
* **Monetizasyon:** `google_mobile_ads` ile AdMob entegrasyonu. Kullanıcı deneyimini bozmayan Banner ve Geçiş (Interstitial) reklamlarının yanı sıra, eğitimle bütünleşik Ödüllü (Rewarded) Reklamlar içerir.

## Göreseller
<img width="380" height="672" alt="image" src="https://github.com/user-attachments/assets/69f3eaa2-51d8-4b7b-b671-d8c857594b2a" />
<img width="379" height="673" alt="image" src="https://github.com/user-attachments/assets/272cab21-78ba-4493-bf75-8a55d9f0443f" />
<img width="377" height="676" alt="image" src="https://github.com/user-attachments/assets/624dd76a-f8cc-4b03-83d6-38ba08f13264" />
<img width="379" height="674" alt="image" src="https://github.com/user-attachments/assets/f12d3914-83d3-4e10-afe1-dcb9687d64ef" />
<img width="378" height="673" alt="image" src="https://github.com/user-attachments/assets/0838c93a-f70d-4d0f-a812-717fc8084217" />
<img width="377" height="674" alt="image" src="https://github.com/user-attachments/assets/16ec63a7-488e-4081-bb82-22c2941aeff9" />
<img width="379" height="672" alt="image" src="https://github.com/user-attachments/assets/ca5a8b80-a571-4818-990e-1956ded99579" />
<img width="379" height="676" alt="image" src="https://github.com/user-attachments/assets/450c226e-708c-4c66-9f05-c004fcb98600" />
<img width="379" height="677" alt="image" src="https://github.com/user-attachments/assets/3c968e6b-6aaa-401f-b9d9-e622d9bc8740" />
<img width="379" height="676" alt="image" src="https://github.com/user-attachments/assets/e2820ae8-e10f-4147-9213-dbb756347373" />
<img width="377" height="673" alt="image" src="https://github.com/user-attachments/assets/9fc338fa-113d-4123-b36a-e780f6b953f7" />
<img width="378" height="675" alt="image" src="https://github.com/user-attachments/assets/03ed3c0d-13de-4ebe-9bd3-7d7b47bdc994" />
<img width="379" height="675" alt="image" src="https://github.com/user-attachments/assets/34ac1d1c-8cbe-4110-9cb8-b7db830598e5" />
<img width="376" height="675" alt="image" src="https://github.com/user-attachments/assets/6b31956b-8bb4-4fe0-9a7d-a47e229dda16" />


## 📁 Proje Yapısı

```text
lib/
├── core/                  # İş mantığı, motorlar (logic_engine), sabitler, servisler ve Provider
├── models/                # Veri modelleri (QuizQuestion, CircuitNode, Topic vb.)
├── screens/               # Uygulama ekranları (Home, Quiz, Lecture, Welcome, Statistics vb.)
├── widgets/               # Özelleştirilmiş UI bileşenleri (Painter'lar, Şemalar, Banner Ad)
└── main.dart              # Uygulama giriş noktası ve kütüphane ilklendirmeleri
