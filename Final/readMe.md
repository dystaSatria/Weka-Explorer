# Final Summary

## Kümeleme Analizi Nedir?
* Her biri bir dizi öznitelik ile, veri noktalarının bir kümesi ve noktalar arasındaki benzerliği ölçen
* Kümelemenin amacı; sağlayan kümeleri bulmaktır

## Kümeleme Analizi Ne Değildir?
* Denetimli sınıflandırma (Sınıf etiketi bilgisine sahip)
* Basit bölümleme (Soyadına göre farklı kayıt gruplarının alfabetik bolunmesi)
* Bir sorgunun sonuçları (Bir şarta göre gruplamaların elde edilmesi)

## Kümeleme tipleri
* ```Bölümlemeli Kümeleme```, Veri nesnelerinin,kapsamayan alt kümelere ayrılmasıdır.Her bir veri nesnesi altkümelerden sadece birinde
yer alır.
*  ```Hiyerarşik Kümeleme```.hiyerarşik ağaç gibi iç içe kümelerin dizi.

## Kümelerin Tipleri
* İyi dağıtılmış kümeler (Well-separated clusters)
*  Merkez tabanlı kümeler.
*  Bitişik Kümeler
*  Yoğunluk tabanlı kümeler

## İyi dağıtılmış kümeler
* Her bir nokta,  kendi kümesindeki diğer noktalara daha yakın ,başka kümeden noktalara ise daha uzaktır.

## Merkez tabanli
* Merkez tabanli : Küme içindeki bir nokta, kendi küme merkezine diğer küme merkezlerine oranla daha yakın.
* bütün noktaların bir ortalaması olan : centroid.
*  kümeyi sunmak için en uygun nokta olan : medoid.

## Yoğunluk tabanlı
* Yoğunluk tabanlı: Daha ```düşük yoğunluklu bölgelerden``` ayrılan ```daha yüksek yoğunluklu noktaların``` bir kümesidir
* Kümeler; düzensiz, birbirine karışmış veya gürültülü olduğunda 
kullanılır.

## Kümeleme Algoritmaları
* K-means ve onun çe
şitleri
*  Hiyerar
şik kümeleme
*  Yo
ğunluk tabanlı kümeleme 


<br>
<br>
<br>

## K-means Kümeleme 
* Bölümlemeli kümeleme yaklaşımıdır.
* Kümelerin sayısı, K, belirlenmelidir.
* Temel algoritma çok basittir.
* Her bir küme bir centroid ile uyumludur (merkez nokta)/
* Her bir nokta kendisine en yakın centroid ile uyumlu

## 
* Başlangıç merkez noktaları sıklıkla rastgele seçilir
* Centroid tipik olarak kümedeki noktaların bir ortalamasıdır.
* ‘Yakınlık’ ```Euclidean uzaklığı```, ```cosine benzerliği```, ```correlation```, v.s. ile hesaplanabilir ve  noktada bir 
araya getirecektir.
*

