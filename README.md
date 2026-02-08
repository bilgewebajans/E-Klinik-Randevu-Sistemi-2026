# E-Klinik - Randevu Yönetim Sistemi

<div align="center">

![Laravel](https://img.shields.io/badge/Laravel-12.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.2+-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Modern, kapsamlı ve kullanıcı dostu randevu yönetim sistemi**

[Özellikler](#özellikler) • [Kullanım](#kullanım) • [Teknolojiler](#teknolojiler) • [Güvenlik](#güvenlik) • [Ekran Görüntüleri](#ekran-görüntüleri) • [Destek](#destek)

</div>

---

## Hakkında {#hakkında}

E-Klinik, sağlık kuruluşları ve klinikler için geliştirilmiş profesyonel bir randevu yönetim sistemidir. Sistem, randevu oluşturma, yönetme, otomatik hatırlatmalar ve detaylı raporlama gibi özellikler sunarak hem hasta hem de yönetim tarafında sorunsuz bir deneyim sağlar.

## Özellikler {#özellikler}

### Temel Özellikler

- **Randevu Yönetimi**
  - Online randevu oluşturma ve yönetme
  - Doktor bazlı müsaitlik kontrolü
  - Randevu durumu takibi (Beklemede, Onaylandı, Tamamlandı, İptal)
  - Randevu geçmişi ve raporlama
  - 3 Farklı Randevu Takvimi (Haftalık Çizelge - Liste Görünümü - Randevu Takvimi)
  - Otomatik çakışma kontrolü

- **Doktor Yönetimi**
  - Doktor profil yönetimi
  - Çalışma saatleri ve müsaitlik takvimi
  - Uzmanlık alanları ve hizmet tanımlama
  - Doktor bazlı randevu görüntüleme

- **Hasta Yönetimi**
  - Hasta kayıt ve profil yönetimi
  - Hasta geçmişi ve notları
  - Hasta bazlı randevu görüntüleme
  - Detaylı hasta bilgileri

- **Otomatik Bildirim Sistemi**
  - Sistem Bildirimleri
  - Email bildirimleri (SMTP desteği)
  - SMS bildirimleri (API entegrasyonu)
  - Randevu hatırlatmaları (otomatik zamanlanmış hatırlatma)
  - Özelleştirilebilir email/SMS şablonları
  - Bildirim geçmişi ve log takibi

- **Sistem Yönetimi**
  - Çoklu rol sistemi (Admin, Doktor, Hasta)
  - Kullanıcı yetkilendirme ve izin yönetimi
  - Sistem ayarları ve konfigürasyon
  - Cache yönetimi
  - Sistem izleme ve loglar

- **Lokasyon Yönetimi**
  - Şehir ve ilçe yönetimi
  - Hasta ve doktor lokasyon bilgileri

- **Raporlama ve Analitik**
  - Randevu istatistikleri
  - Doktor performans raporları
  - Hasta istatistikleri
  - Dashboard görünümleri

### Kullanıcı Arayüzü

- Modern ve responsive tasarım
- Mobil uyumlu arayüz
- Koyu mod desteği
- Kullanıcı dostu navigasyon
- Hızlı arama ve filtreleme

### Teknik Özellikler

- Asenkron iş kuyruğu (Redis Teknolojisi)
- Zamanlanmış Hatırlatma görevleri (Laravel Scheduler)
- Email ve SMS şablon sistemi
- Cache optimizasyonu
- Güvenli kimlik doğrulama

## Kullanım {#kullanım}

### Admin Paneli

1. Admin hesabı ile giriş yapın
2. Dashboard'dan sistem genel görünümünü inceleyin
3. Randevularınızı görüntüleyin ve yönetin
4. Doktorlarınızın Çalışma saatlerini ayarlayın
5. Doktorlar, Hastalar ve Randevular menülerinden yönetim yapın
6. Ayarlar bölümünden sistem konfigürasyonunu yapın
7. Kullanım Klavuzu
8. Sistem Bildirimleri (Yeni Kayıt % Yeni Randevu)

### Hasta Paneli

1. Hasta hesabı ile giriş yapın veya kayıt olun
2. Randevu al sayfasından randevu oluşturun
3. Randevularım bölümünden randevularınızı görüntüleyin
4. Randevu detaylarını inceleyin
5. Sistem Bildirimleri (Randevu Onayı)

## Teknolojiler {#teknolojiler}

- **Backend**: Laravel 12.x
- **Frontend**: Bootstrap 5, JavaScript (Vanilla)
- **Database**: MySQL/MariaDB
- **Queue**: Redis
- **Cache**: Redis / File
- **Email**: SMTP
- **SMS**: API Entegrasyonu.


## 🔐 Güvenlik {#güvenlik}

- CSRF koruması
- XSS koruması
- SQL Injection koruması
- Güvenli şifre hashleme
- Role-based access control (RBAC)


## 📸 Ekran Görüntüleri {#ekran-görüntüleri}

<div align="center">

### Admin Paneli

<table>
<tr>
<td width="50%">
<a href="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Admin%20Anasayfa.png">
<img src="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Admin%20Anasayfa.png" alt="Admin Anasayfa" width="100%"/>
</a>
<p align="center"><strong>Admin Anasayfa</strong></p>
</td>
<td width="50%">
<a href="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Randevu%20Takvimi.png">
<img src="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Randevu%20Takvimi.png" alt="Randevu Takvimi" width="100%"/>
</a>
<p align="center"><strong>Randevu Takvimi</strong></p>
</td>
</tr>
<tr>
<td width="50%">
<a href="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Randevu%20Olu%C5%9Ftur.png">
<img src="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Randevu%20Olu%C5%9Ftur.png" alt="Randevu Oluştur" width="100%"/>
</a>
<p align="center"><strong>Randevu Oluştur</strong></p>
</td>
<td width="50%">
<a href="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Randevu%20Sistemi%20Ayarlar%C4%B1.png">
<img src="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Randevu%20Sistemi%20Ayarlar%C4%B1.png" alt="Randevu Sistemi Ayarları" width="100%"/>
</a>
<p align="center"><strong>Randevu Sistemi Ayarları</strong></p>
</td>
</tr>
</table>

### Bildirim ve Şablon Yönetimi

<table>
<tr>
<td width="50%">
<a href="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Hat%C4%B1rlatma%20Ayarlar%C4%B1.png">
<img src="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Hat%C4%B1rlatma%20Ayarlar%C4%B1.png" alt="Hatırlatma Ayarları" width="100%"/>
</a>
<p align="center"><strong>Hatırlatma Ayarları</strong></p>
</td>
<td width="50%">
<a href="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Sms%20%C5%9Eablonlar%C4%B1.png">
<img src="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Sms%20%C5%9Eablonlar%C4%B1.png" alt="SMS Şablonları" width="100%"/>
</a>
<p align="center"><strong>SMS Şablonları</strong></p>
</td>
</tr>
</table>

### Hasta Paneli ve Dokümantasyon

<table>
<tr>
<td width="50%">
<a href="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Hasta%20Anasayfa.png">
<img src="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Hasta%20Anasayfa.png" alt="Hasta Anasayfa" width="100%"/>
</a>
<p align="center"><strong>Hasta Anasayfa</strong></p>
</td>
<td width="50%">
<a href="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Kullan%C4%B1m%20Klavuzu.png">
<img src="https://raw.githubusercontent.com/bilgewebajans/E-Klinik-Randevu-Sistemi-2026/refs/heads/main/Kullan%C4%B1m%20Klavuzu.png" alt="Kullanım Klavuzu" width="100%"/>
</a>
<p align="center"><strong>Kullanım Klavuzu</strong></p>
</td>
</tr>
</table>

> 💡 **Not**: Resimlere tıklayarak tam boyutta görüntüleyebilirsiniz.

</div>

## 📝 Lisans {#lisans}

Bu proje [MIT lisansı](LICENSE) altında lisanslanmıştır.

## 👨‍💻 Geliştirici {#geliştirici}

**Bilge Web Ajans**

- Website: [www.randevu-sistemi.com](https://www.randevu-sistemi.com)
- Website: [www.bilgewebajans.com](https://www.bilgewebajans.com)
- Email: bilgi@bilgewebajans.com
- WhatsApp: +90 530 230 47 03

## 🙏 Teşekkürler {#teşekkürler}

- [Laravel](https://laravel.com) - PHP framework
- [Bootstrap](https://getbootstrap.com) - CSS framework
- [Ileti Merkezi](https://iletimerkezi.com) - Sms

## 📞 Destek {#destek}

Herhangi bir sorunuz veya öneriniz için:

- 📧 Email: bilgi@bilgewebajans.com
- 📱 WhatsApp: +90 530 230 47 03
- 🌐 Website: [www.bilgewebajans.com](https://www.bilgewebajans.com)
- 🌐 Website: [www.randevu-sistemi.com](https://www.randevu-sistemi.com)

---

<div align="center">

**⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!**

Made with ❤️ by [Bilge Web Ajans](https://www.bilgewebajans.com)

</div>
