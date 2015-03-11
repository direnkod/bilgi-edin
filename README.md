Bu proje ile devlet kurumlarından bilgi istek işlemlerini hızlandırmayı, kolaylaştırmayı, ve kolektif olarak takip edilebilir hale getirerek devlet kurumlarını daha hesap verebilir hale getirmeyi hedefliyoruz.

[Bilgi Edinme Kanunu](http://www.mevzuat.gov.tr/Metin.Aspx?MevzuatKod=1.5.4982&sourceXmlSearch=&MevzuatIliski=0)'na göre, her TC vatandaşı bilgi edinme hakkına sahiptir. Çeşitli devlet kurumlarının web sitelerinde [Bilgi Edinme Kanunu Yönetmeliği](http://www.meb.gov.tr/BilgiEdinme/yonetmelik.html)'ne göre "Bilgi Edin" sayfalarındaki formlar kullanılarak bu işlem yapılabiliyor. Ancak ne bilgi edinme hakkını kullanmak için ne birleşik bir arayüz mevcut, ne de yapılan işlemler şeffaf.

Bu projede bilgi edinme hakkına kolektif zekayı katarak bilgi istek sürecini hızlandırmak, isteklerin takipçisi olmak, ve insanlara ne gibi bilgileri talep edebilecekleri konusunda yol gösteren bir platform geliştirmeyi amaçlıyoruz.

### Hazırlık aşamasında yapılacaklar

- Farklı kurumlara göre adapte olabilien yalın bir Bilgi Edinme Formu tasarımı (içereceği bilgiler, kuruma göre şablonlar, ve gönderilecek makamların listesi)
 
- Bilgi Edinme Kanunu'nun kullanabileceği kurumların ve form adreslerinin derlenmesi ([bilgi_edinme_kaynaklari.json](https://github.com/direnkod/bilgi-edin/blob/master/bilgi_edinme_kaynaklari.json))

- Bilgi Edinme Kanunu'nun kullanabileceği kurumların listelendiği ve linklendiği yalın bir sayfa üretimi ([index.html](https://github.com/direnkod/bilgi-edin/blob/master/index.html))

- Derlenen kurumlar listesinden yola çıkara talep edilebilecek bilgilerin kategorilendirilmesi.

### İlk aşamada yapılacaklar

- Bilgi Edin Formu'nun seçilen kuruma göre programatik olarak submit edilebilmesi. Öncelikle sadece 3-5 kritik kurumda çalışır hale gelmesi yeterli.

- Soruların listelenmesi ve sık sorulan bilgilerin öne çıkarılması (uservoice getstaisfaction vb sitelerdeki gibi)

- Sorulan bilgiler arasında arama

- "Ben de bu bilgiyi talep ediyorum" tek tıkla Bilgi Edinme talebi gönderme listeden seçerek

### İkinci aşamada yapılacaklar

- Bilgi Edin Formu'nun çalışabildiği kurumların sayısını arttıran adaptörler geliştirme.

- Taleplere devletin verdiği cevapların (bilgi veya red) takibi ve istatistiklerini derleme ve gösterme

- TBMM'de milletvekillerin verdiği "Soru Önergeleri"ni de takibe alma.
