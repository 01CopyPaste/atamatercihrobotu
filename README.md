Öğretmen Yerleştirme Sistemi - Kullanım Kılavuzu

        1. Genel Bakış
Bu sistem, öğretmenlerin tercihlerine ve sıralamalarına göre okullara yerleştirilmesini sağlayan bir Google Apps Script uygulamasıdır.

        2. Sistem Gereksinimleri
•	Google Sheets erişimi
•	Düzenleme yetkisi

        3. Sayfa Yapısı
Sistem üç ana sayfadan oluşur:
•	Öğretmen Tercihleri: Öğretmenlerin bilgileri ve tercihleri
•	Okul Kontenjanları: Okulların kontenjan bilgileri
•	Yerleştirme Sonuçları: Yerleştirme işlemi sonuçları

          4. Menü Kullanımı
Üst menüde "Yerleştirme İşlemleri" başlığı altında dört seçenek bulunur:
•	Yerleştirme Yap: Yerleştirme işlemini başlatır
•	Kontenjanları Güncelle: Mevcut yerleşme durumlarını günceller
•	Tercih Doğrulamasını Aktifleştir: Tercih kontrollerini etkinleştirir
•	Okul Kontenjanları Formatını Düzenle: Okul sayfasını düzenler

          5. Veri Girişi Kuralları
Öğretmen Tercihleri Sayfası
•	Sütun A: Öğretmen ID
•	Sütun B: Öğretmen Adı
•	Sütun C: Sıralama Puanı
•	Sütun D-AQ: Tercihler (40 tercih hakkı)
Okul Kontenjanları Sayfası
•	Sütun A: İl
•	Sütun B: İlçe
•	Sütun C: Okul Adı
•	Sütun D: Kontenjan
•	Sütun E: Yerleşen Sayısı (otomatik güncellenir)
•	Sütun F: Tercih Edilme Sayısı (otomatik güncellenir)

          6. Önemli Özellikler
Tercih Kontrolü
•	Aynı okul birden fazla kez tercih edilemez
•	Tekrarlanan tercih girişinde uyarı verilir
•	Geçersiz tercihler otomatik silinir
Renk Kodlaması
•	Kırmızı Arka Plan: Yerleştirilemeyen öğretmenler
•	Yeşil Arka Plan: Yerleşilen tercih
•	Kırmızı Arka Plan (Okul): Kontenjanı dolan okullar

          7. İşlem Adımları
Yerleştirme Yapmak İçin:
1.	Öğretmen bilgilerini girin
2.	Okul kontenjanlarını girin
3.	"Yerleştirme Yap" menüsüne tıklayın
4.	Sonuçları "Yerleştirme Sonuçları" sayfasından kontrol edin
Kontenjanları Güncellemek İçin:
1.	"Kontenjanları Güncelle" menüsüne tıklayın
2.	Güncel doluluk oranlarını kontrol edin

          8. Hata Durumları ve Çözümleri
•	Tercih Hatası: Tekrarlanan tercih mesajı görüldüğünde, farklı bir okul seçin
•	Sayfa Bulunamadı Hatası: Tüm gerekli sayfaların mevcut olduğundan emin olun
•	Yerleştirilememe Durumu: Öğretmenin tercih ettiği tüm okulların kontenjanları dolmuş olabilir

          9. İpuçları
•	Yerleştirme öncesi tüm verilerin doğru girildiğinden emin olun
•	Düzenli olarak kontenjan güncellemesi yapın
•	Tercih girişlerinde okul adı formatına dikkat edin

          10. Teknik Destek
Sorun yaşamanız durumunda sistem yöneticinizle iletişime geçin.

