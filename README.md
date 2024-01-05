# API Test Projesi

Bu proje, **Postman** kullanılarak geliştirilmiş bir API test projesini içermektedir. Proje, [Restful Booker](https://restful-booker.herokuapp.com/) sitesindeki API'leri test etmek amacıyla oluşturulmuştur.

## Proje Detayları

- **Geliştirici:** Erdem Büke
- **Kullanılan Araç:** Postman
- **API Base URL:** https://restful-booker.herokuapp.com/

## Proje İçeriği

Proje, toplamda **8 adet request** (3 GET, 2 POST, 1 PATCH, 1 DELETE) içermektedir. Bu request'lerin her biri, Restful Booker API'lerinin farklı özelliklerini test etmek için tasarlanmıştır.

### 1. Authentication
   - Kullanıcı girişi için token alma işlemi.

### 2. Create Booking
   - Yeni bir rezervasyon oluşturma.

### 3. Get Bookings
   - Kayıtlı rezervasyonların id'lerini getirme.

### 4. Update Booking
   - Var olan bir rezervasyonu güncelleme.

### 5. Partial Update Booking
   - Rezervasyonun belirli alanlarını güncelleme.

### 6. Delete Booking
   - Var olan bir rezervasyonu silme.

### 7. Get Booking By ID
   - Belirli bir id degerindeki rezervasyonun detayli bilgilerini getirme.

### 8. Health Check
   - API'nin sağlığını kontrol etme.

## Nasıl Kullanılır

1. Proje dosyalarını bilgisayarınıza indirin.
2. **Postman uygulamasını açın.**
3. "Import" butonuna tıklayarak projeyi içeren **Collection dosyasını yükleyin.**
4. Collection içindeki her bir request'i inceleyip, gerektiğinde güncelleyerek veya test ederek kullanabilirsiniz.

## Lisans

Bu proje, [MIT lisansı](LICENSE) altında lisanslanmıştır. Detaylı bilgi için lisans dosyasını inceleyebilirsiniz.
