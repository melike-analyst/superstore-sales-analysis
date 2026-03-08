Superstore Satış Analizi

Proje Amacı:
Bu projede bir perakende şirketine ait satış verileri analiz edilerek satış performansı ve kârlılık yapısı incelenmiştir. 
Amaç; hangi ürün kategorilerinin, bölgelerin ve müşteri segmentlerinin kârlılık üzerinde daha etkili olduğunu belirlemek ve veri üzerinden iş kararlarına katkı sağlayabilecek içgörüler (insight) elde etmektir.

Analiz sürecinde Pandas, Matplotlib ve Seaborn kütüphaneleri kullanılarak keşifsel veri analizi (EDA) gerçekleştirilmiştir.


# Proje Amaçları

Bu analiz kapsamında aşağıdaki sorulara cevap aranmıştır:

* Hangi ürün kategorileri en fazla satış üretmektedir?
* Hangi ürün kategorileri en yüksek kârı sağlamaktadır?
* Hangi alt kategoriler zarar üretmektedir?
* Satışlar zaman içinde nasıl değişmektedir?
* Kâr marjı zaman içinde nasıl değişmektedir?



# Kullanılan Teknolojiler

Bu projede aşağıdaki araçlar kullanılmıştır:

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook



# Veri Seti

Proje kapsamında kullanılan veri seti **Superstore Sales Dataset**'tir.

Veri setinde aşağıdaki bilgiler yer almaktadır:

* Sipariş tarihi
* Satış tutarı
* Kâr miktarı
* Ürün kategorisi
* Ürün alt kategorisi
* Müşteri segmenti
* Bölge bilgisi

Her satır bir satış işlemini temsil etmektedir.


# Analiz Süreci

Projede aşağıdaki analiz adımları uygulanmıştır:

### 1. Veri Yükleme ve İnceleme

* Veri seti Pandas ile içeri aktarılmıştır
* Veri tipleri incelenmiştir
* Tarih değişkeni uygun formata dönüştürülmüştür
* Veri setinin genel istatistikleri incelenmiştir



### 2. Satış Analizi

Aşağıdaki analizler yapılmıştır:

* Toplam satış analizi
* Kategori bazlı satış analizi
* Alt kategori bazlı satış analizi

Bu analiz sayesinde en çok gelir üreten ürün grupları belirlenmiştir.



### 3. Kâr Analizi

Kâr performansını değerlendirmek için:

* Toplam kâr analizi
* Kategori bazlı kâr analizi
* Zarar eden ürün grupları

incelenmiştir.



### 4. Kâr Marjı Hesaplama

Kâr marjı aşağıdaki formül kullanılarak hesaplanmıştır:

Kâr Marjı = Kâr / Satış

Bu metrik satışların ne kadar verimli olduğunu anlamak için kullanılmıştır.


## 5. Bölge ve Segment Bazlı Kârlılık
 Bölgesel segment analizi yapılmıştır.Her segmentin satışdaki oranı ,bölge ve kategorilere göre 
 kazanç etkisi hesaplanmış ve incelenmiştir.
 

### 6. Zaman Serisi Analizi

Satışların zaman içindeki değişimini incelemek için  yıllara göre aylık analiz yapılmıştır.

Analiz edilen metrikler:

* Aylık satış
* Aylık kâr
* Aylık kâr marjı

Bu analiz sayesinde satış trendleri ve dönemsel değişimler incelenmiştir.





# Önemli Bulgular

Analiz sonucunda aşağıdaki önemli bulgular elde edilmiştir:

* Bazı ürün kategorileri yüksek satış üretmesine rağmen düşük kâr marjına sahiptir.
* Bazı alt kategoriler yüksek kâr üretmektedir.
* Satışlar zaman içinde dalgalı bir trend göstermektedir.
* Kâr marjı bazı dönemlerde önemli ölçüde değişmektedir.

Bu sonuçlar ürün stratejileri ve fiyatlandırma politikaları açısından önemli içgörüler sunmaktadır.


# Gelecek Geliştirmeler

Bu proje aşağıdaki yönlerde geliştirilebilir:

* Etkileşimli dashboard oluşturma (Power BI / Tableau)
* Satış tahmin modeli geliştirme
* Müşteri segmentasyonu analizi
* Bölgesel satış performansı analizi



