# PatikaVeriAnalizi2.Proje
# Power BI Satış Raporu – Pınar Markası Analizi

Bu proje, Patika.dev ve Kız Başına tarafından düzenlenen veri analizi bootcampinin final projesidir. Sentetik veriler ve Power BI kullanılarak oluşturulmuştur. Pınar markasına ait satış, müşteri ve kategori analizlerini içeren interaktif bir rapordur.

---

##  Proje Amacı

Bu çalışmanın amacı, Pınar markası özelinde satış performansını farklı perspektiflerden analiz etmek ve görselleştirmektir. Rapor, yöneticilerin veya karar vericilerin aşağıdaki sorulara hızlıca yanıt bulmasını hedefler:

- Haftaiçi ve haftasonu satış davranışı nasıl değişiyor?
- Saat bazlı satış yoğunluğu hangi zaman dilimlerinde?
- Hangi bölgelerde daha çok satış yapılıyor?
- Hangi yaş grubu ne kadar alışveriş yapıyor?
- Kadın ve erkek müşterilerin dağılımı nasıl?
- En çok harcama yapan İstanbul müşterileri kimler?

---

##  Kullanılan Veritabanı Tabloları

| Tablo Adı       | Açıklama                                  |
|-----------------|--------------------------------------------|
| `Adres`         | Kullanıcının yaşadığı ülke ve şehir bilgisi |
| `Bölgeler`      | İl-bölge eşleşmesi                         |
| `Kullanıcılar`  | Ad, doğum tarihi, cinsiyet, e-posta bilgisi|
| `Sipariş`       | Sipariş tarihi, toplam fiyat, yıl-ay bilgisi|
| `SiparişDetay`  | Ürün bazlı satış adedi, ciro bilgisi       |
| `Ürünler`       | Ürün kodu, adı, kategorileri, marka        |

---

##  Rapor Sayfaları

### 1.  Giriş Sayfası
- Navigasyon butonlarıyla diğer sayfalara yönlendirme

### 2.  Özet Sayfa
- Toplam satış adedi, ciro, müşteri ve sipariş sayısı
- Haftasonu / haftaiçi satış karşılaştırması
- Saatlik satış dağılımı
- Bölgelere göre satış adedi

### 3.  Müşteri Perspektifi
- Kadın / erkek müşteri sayısı
- Bölgelere göre müşteri dağılımı
- Yaş gruplarına göre satış
- İstanbul’daki en yüksek harcama yapan 10 müşteri

### 4.  Kategori Perspektifi
- İstanbul’da yaşayan genç kullanıcıların kategorilere göre harcamalarının ağaç haritası

---

##  Oluşturulan DAX Ölçüleri ve Sütunlar

- Toplam Satış Adeti  
- Toplam Ciro  
- Müşteri Başına Ciro / Adet  
- Ortalama Sipariş Tutarı  
- Yaş, Yaş Grubu (Koşullu sütun)  
- Hafta içi / Hafta sonu sınıflandırması  
- Saat bazlı satış (saat ayırma)

---

##  Filtre Uygulaması

Bu rapor özel olarak **`Ürünler[BRAND] = "Pınar"`** olacak şekilde filtrelenmiştir. Tüm görselleştirmeler sadece Pınar markasına ait satış verilerini içerir.



