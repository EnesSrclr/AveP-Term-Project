# Güneş Sistemi Fizik Simülasyonu 🌌

Bu proje, **Bursa Teknik Üniversitesi - Algoritmalar ve Programlama** dersi dönem projesi kapsamında geliştirilmiştir. Uygulama, C programlama dili kullanılarak hazırlanmış konsol tabanlı bir uzay simülasyonudur.

## 📋 Proje Tanıtımı

Simülasyon, bir bilim insanının Güneş Sistemi'ndeki farklı gezegenlerde (Merkür, Venüs, Dünya, Mars, Jüpiter, Satürn, Uranüs, Neptün) temel fizik deneylerini gerçekleştirmesini konu alır. Kullanıcıdan alınan metrik veriler (kütle, uzunluk, hız vb.), her gezegenin kendine özgü yerçekimi ivmesi kullanılarak işlenir ve sonuçlar karşılaştırmalı olarak listelenir.

## 🚀 Özellikler ve Deneyler

Proje kapsamında aşağıdaki 9 farklı fizik deneyi simüle edilmektedir:

1.  **Serbest Düşme Deneyi:** Belirli bir sürede düşülen mesafenin hesaplanması.
2.  **Yukarı Atış Deneyi:** Belirli bir hızla atılan cismin çıkabileceği maksimum yüksekliğin hesaplanması.
3.  **Ağırlık Deneyi:** Bir kütlenin farklı gezegenlerdeki ağırlığının (Newton) hesaplanması.
4.  **Kütleçekimsel Potansiyel Enerji:** Belirli bir yükseklikteki cismin potansiyel enerjisi.
5.  **Hidrostatik Basınç Deneyi:** Sıvı basıncının gezegenlere göre değişimi.
6.  **Arşimet Kaldırma Kuvveti:** Sıvı içindeki cisme etki eden kaldırma kuvveti.
7.  **Basit Sarkaç Periyodu:** Sarkacın bir salınımını tamamlama süresi.
8.  **Sabit İp Gerilmesi:** Asılı duran bir kütlenin ipte oluşturduğu gerilme.
9.  **Asansör Deneyi:** İvmelenen bir asansör içindeki cismin etkin ağırlığı.

## 🛠 Teknik Detaylar ve Kısıtlamalar

Bu proje, ders kapsamında belirtilen aşağıdaki teknik zorunluluklara uygun olarak geliştirilmiştir:

* **Dil:** Saf C Programlama Dili.
* **Arayüz:** Sadece konsol (metin) tabanlı etkileşim.
* **Pointer Aritmetiği:** Diziler üzerindeki tüm erişim ve işlemler (gezegen verileri dahil) pointer mantığı ile yapılmıştır (`dizi[i]` yerine `*(ptr + i)` kullanımı).
* **Girdi Doğrulama:** Negatif girilen fiziksel büyüklükler (kütle, zaman vb.), `if-else` kullanılmadan **Ternary Operator** kullanılarak mutlak değere dönüştürülmüştür.
* **Modüler Yapı:** Her deney ayrı bir fonksiyon olarak tasarlanmış ve gezegen verileri fonksiyonlara pointer olarak gönderilmiştir.


## 📝 Kullanım Senaryosu

1.  Program başladığında bilim insanı (kullanıcı) adını girer.
2.  Ana menüden yapmak istediği deneyi seçer (1-9).
3.  Seçilen deney için gerekli parametreleri (örn: sarkaç uzunluğu) girer.
4.  Program, girilen değeri Güneş Sistemi'ndeki 8 gezegen için ayrı ayrı hesaplar ve sonuçları tablo halinde gösterir.
5.  Çıkış yapmak için menüde `-1` değeri girilir.

## 👤 Hazırlayan

* **Ad Soyad:** Enes Sarıcalar
* **Öğrenci No:** 24360859039
* **Ders:** Algoritmalar ve Programlama

---
*Bu proje 2025-2026 Güz Dönemi Proje Ödevi kapsamında hazırlanmıştır.*# AveP-Term-Project
