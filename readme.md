# Uçak Bilet Rezervasyon Konsol Uygulaması

Bu proje, Java ile geliştirilmiş basit bir **uçak bilet rezervasyon sistemi**dir.  
Konsol üzerinden çalışan uygulama, uçak, lokasyon, uçuş ve rezervasyon işlemlerini yönetir.

---

## Özellikler

- Uçak, lokasyon ve uçuş bilgilerini modelleme  
- Uçuşlar arasında seçim yapma  
- Kullanıcıdan alınan bilgilerle rezervasyon yapma  
- Uçak koltuk kapasitesine göre doluluk kontrolü  
- Rezervasyonların CSV dosyasına kaydedilmesi  

---

## Kullanılan Teknolojiler

- Java SE  
- Dosya işlemleri (CSV formatında veri saklama)  
- Konsol tabanlı kullanıcı arayüzü  

---

## Nasıl Çalıştırılır?

1. Projeyi klonlayın veya indirin.  
2. `UcakBiletRezervasyon.java` dosyasını bir Java derleyicisinde derleyin:

   ```bash
   javac UcakBiletRezervasyon.java
Programı çalıştırın:

bash
Kopyala
Düzenle
java UcakBiletRezervasyon
Konsolda listelenen uçuşlardan birini seçip rezervasyon bilgilerinizi girin.

Rezervasyon başarıyla yapıldıktan sonra bilgiler rezervasyonlar.csv dosyasına kaydedilir.

Proje Yapısı
Ucak: Uçak modeli, marka, seri no ve koltuk kapasitesi bilgileri

Lokasyon: Ülke, şehir, havaalanı ve aktiflik durumu

Ucus: Uçuş zamanı, lokasyon ve uçak bilgisi

Rezervasyon: Yolcu bilgileri ve seçilen uçuş

UcusServisi: Uçuş ve rezervasyon işlemlerinin yönetimi

