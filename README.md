# 💸 FLUX: Akıllı Finansal Akış ve Bilinçli Harcama Asistanı

> [cite_start]**Sistem Analizi ve Tasarımı (YAZ213) Dersi Grup Projesi [cite: 3]**
> [cite_start]İstanbul Sağlık ve Teknoloji Üniversitesi — Mühendislik ve Doğa Bilimleri Fakültesi, Yazılım Mühendisliği 

[cite_start]FLUX, e-ticaret çağındaki en büyük finansal tehditlerden biri olan "dürtüsel harcamayı" yavaşlatmayı ve kullanıcıların finansal farkındalığını artırmayı hedefleyen yüksek kaliteli (high-fidelity) bir mobil uygulama konseptidir[cite: 5, 6]. [cite_start]Geleneksel bütçe uygulamalarının aksine harcama sonrasında rapor sunmak yerine, satın alma anında devreye girerek "48 Saat Bekleme Odası" deneyimi ile psikolojik bir bariyer oluşturur[cite: 6, 59, 60].

[cite_start]🔗 **[İnteraktif Figma Prototipini İnceleyin](https://www.figma.com/design/e7mnSqXzYuGbYj2jijZ3fg/Sistem-Analizi-ve-Tasar%C4%B1m%C4%B1-Grup-1?node-id=0-1&t=OarIyYoTGLac2hRo-1)** [cite: 199]

---

## 🎯 Projenin Temel Çözümleri

* **Bekleme Odası (48 Saat Prensibi):** Ani bir dopamin artışıyla (FOMO) verilen satın alma kararlarını yavaşlatır. [cite_start]Kullanıcı ürünü hemen almak yerine akıllı bir sayaç ile "Bekleme Odası"na alır[cite: 6, 63, 65].
* [cite_start]**Dürtüyü Yatırıma Dönüştürme:** Süre dolduğunda vazgeçilen ürünler için ayrılan bütçe, kişinin risk profiline göre düşük riskli fonlara veya tasarruf kasasına aktarılır[cite: 64, 68].
* [cite_start]**Suni İndirim Tespiti:** YZ desteğiyle ürünlerin 90 günlük fiyat geçmişini analiz ederek satıcıların sahte indirim oyunlarını ifşa eder[cite: 69, 186].
* **Davranışsal Personalar:** Sistem; [cite_start]Ahmet (Dürtüsel), Kaan (FOMO Mağduru), Zeynep (Enflasyon Savaşçısı) ve Eren (Optimizasyon Tutkunu) olmak üzere 4 farklı finansal davranış arketipine göre kişiselleştirilmiş akışlar sunar[cite: 72, 73].

---

## 🛠️ Mimari, Yöntem ve Araçlar

[cite_start]Bu projede herhangi bir satır kod yazılmamış; yazılım geliştirme yaşam döngüsünün (SDLC) **analiz, modelleme ve tasarım** aşamalarına odaklanılmıştır[cite: 36, 91].

* [cite_start]**Metodoloji:** Çevik (Agile) Geliştirme ve Scrum (3 Sprint) [cite: 15, 45, 46, 53]
* [cite_start]**Sistem Modelleme (UML):** Use Case, Sequence, State ve Activity diyagramları [cite: 28]
* [cite_start]**Tasarım Sistemi:** Figma (High-Fidelity, Glassmorphism, Aurora Mavisi - Siber Kırmızı renk kodlaması) [cite: 165, 169, 176, 180]
* [cite_start]**YZ Entegrasyonu (DIR Çerçevesi):** Claude ve Gemini, Discover-Interact-Review (DIR) etiği çerçevesinde şeffaf birer üretkenlik ve analiz aracı olarak kullanılmıştır[cite: 31, 50, 221, 222].

---

## 👨‍💻 Benim Rolüm ve Katkılarım

[cite_start]Ekip koordinatörü (**Baran Kemal Kılıç**) olarak projede üstlendiğim temel sorumluluklar[cite: 9, 37]:
* [cite_start]**Proje Yönetimi & Raporlama:** Ekip içi koordinasyonun sağlanması ve akademik/teknik proje raporunun uçtan uca derlenmesi[cite: 37, 217].
* [cite_start]**UI/UX Tasarımı:** "Ahmet - Dürtüsel Fırsat Avcısı" personasının ana ekran, Bekleme Odası ve Suni İndirim tespiti süreçlerinin Figma üzerinde yüksek kaliteli tasarımlarının yapılması[cite: 37, 186].
* [cite_start]**DIR (YZ Şeffaflık) Dokümantasyonu:** Proje boyunca kullanılan yapay zeka araçlarının iteratif süreçlerinin ve doğrulama mekanizmalarının uluslararası etik standartlara göre skorlanıp (Discover-Interact-Review) dokümante edilmesi[cite: 37, 219, 223].
* [cite_start]**Sistem Analizi:** Use case senaryolarının (alternatif ve istisnai akışlar dahil) belirlenmesi ve mimari modellerin tutarlılık denetimi[cite: 218].

---

## 📁 Depo İçeriği ve Dokümanlar

Bu depoda, kod yerine yazılımın "Blueprint"i olan aşağıdaki mimari dokümanları bulabilirsiniz:

* 📄 **[`/docs/FLUX_Proje_Raporu_Grup1.pdf`](#):** Projenin tüm teknik detaylarını, UML diyagramlarını ve analiz süreçlerini barındıran kapsamlı final raporu. *(Lütfen docx dosyanızı PDF yapıp depoya yükleyin ve buraya linkini verin)*
* 🖼️ **[`/images`](#):** Figma tasarımından yüksek çözünürlüklü arayüz örnekleri ve UML şemaları.

### Örnek Sistem İşleyişi (UML Activity Diagram)
*(Buraya Şekil 6 — FLUX Uçtan Uca Değer Akışı (Activity Diyagramı) görselini yükleyip gösterebilirsin)*
`![FLUX Değer Akışı](images/activity-diagram.png)`

---
[cite_start]*Bu proje Grup 1 (Süleyman Canberk Eğriboz, İrem Serra Onmaz, Nihat Güney, Baran Kemal Kılıç) tarafından geliştirilmiştir[cite: 8, 9].*
