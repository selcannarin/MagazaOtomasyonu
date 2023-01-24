# MagazaOtomasyonu

Uygulama Tanımı:
Uygulamam bir mağazadaki ürünlerin, stoklarının, kategorilerinin, siparişlerin, müşterilerin ve kategorilerin yöneticilerinin bilgilerinin tutulduğu veri tabanından bilgilerini çekerek onları listelememizi, güncelleme, ekleme, silme ve arama yapmamızı sağlayan bir mağaza kontrol sistemidir.
PostgreSQL ve C# form kullanarak yapılmıştır.

Listeleme:

![image](https://user-images.githubusercontent.com/72921635/214440784-698b74f6-4079-43da-a40f-40e583d618de.png)
Ekleme:

![image](https://user-images.githubusercontent.com/72921635/214440850-5406dc2b-bfc9-40de-84ff-c4111cf6f94c.png)
Arama:

![image](https://user-images.githubusercontent.com/72921635/214440974-c165b9c9-b076-4777-8f9d-6f6e3e870ccf.png)
Güncelleme:

![image](https://user-images.githubusercontent.com/72921635/214441028-90ea29ac-d1e7-4b1d-a0dd-f2ff5503e61e.png)
Silme:

![image](https://user-images.githubusercontent.com/72921635/214441083-cb0b0ae9-3a93-4a81-874a-4f3fa25a29d3.png)
Stok Bilgisi:

![image](https://user-images.githubusercontent.com/72921635/214441153-5381b9bc-969e-42ff-93b9-82cce3aee443.png)
Siparişler:

![image](https://user-images.githubusercontent.com/72921635/214441189-d2cc3d8e-f857-45b4-ac2d-9c3a5aae2f37.png)
Müşteriler:

![image](https://user-images.githubusercontent.com/72921635/214441219-aec2c5a5-d205-4707-a679-0971f2d60a00.png)
Yöneticiler:

![image](https://user-images.githubusercontent.com/72921635/214441245-75a28725-980b-480c-8a87-d0b2560fe978.png)

İş Kuralları:

-Bir ürünün bir id’ si, adı, kategorisi, fiyatı, markası ve tedarikçisi vardır.

-Her ürünün bir birim kazancı vardır. Birim kazanç satış fiyatından alış fiyatını ve kdvli halini çıkarılıp elde edilir.

-Her ürünün bir stok bilgisi vardır. Stok adeti 50’ den az olanların stok durumu “tedarik edilmeli” 50’ye eşit veya fazla olanların ise “stok yeterli” dir.

-Stoku azalanlar tedarik edilmesi için yedeklenir.

-Her kategorinin çok sayıda ürünü vardır.

-Her kategorinin bir kdv oranı vardır.

-Bir kategorinin çok yöneticisi olabilir.

-Yöneticilerin nosu, adı ve soyadı kaydedilir.

-Bir üründen çok kez sipariş verilebilir.

-Bir siparişte çok sayıda ürün olabilir.

-Her ürün sipariş verildiğinde stok sayısı azalır.

-Bir siparişi bir müşteri sipariş edebilir.

-Bir müşteri çok sayıda sipariş verebilir.

-Her siparişin faturası, kargo firması ve alınan ürün adetine göre hesaplanan tutarı vardır

-Her müşterinin nosu, adı, soyadı, teli ve yaşadığı il kaydedilir.
