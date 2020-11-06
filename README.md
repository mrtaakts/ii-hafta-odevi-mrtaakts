# II. Hafta Ödevleri

 - :heavy_check_mark: Yeni bir Gitthub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?
 - :heavy_check_mark: Merge - Squash-Rebase arasındaki farklar nelerdir?
 - :heavy_check_mark: Github Learning Lab'de First Day ve First Week kısımlarını bitiriniz.
 - :heavy_check_mark: Agile-Scrum-Kanban kavramlarını araştırınız
 - :heavy_check_mark: Derste yaptığımız .Net Console uygulamasının .NetCore versiyonunu yazmayı deneyiniz.
 - :heavy_check_mark: Github Flow'un alternatifleri nelerdir? Artılarını ve eksilerini karşılaştırınız.
 - :heavy_check_mark: Gang of Four(GOF) araştırınız.
 - :heavy_check_mark: Interface ve Abstract sınıflar arasındaki farklar nelerdir?

# Merge Squash Rebase

Konuya başlamadan önce sıkça kullandığımız git merge ve git rebase arasındaki farka bakalım;

- **Git merge** ile yaptığımız birleştirmede yeni bir commit yaratacak ve yeni branch’deki tüm history tarafını kaybetmeden birleştirme işlemi gerçekleşmiş olcaktır.

- **Git rebase** ile birleştirdiğimizde ise branch deki commit’lerimizi tek tek alıp istediğmiz branch üzerine ekleyecektir. Böylelikle tek bir history oluşturacak ve istenmeyen history ortadan kalkacaktır.

- **Git squash**  komutu aslında farklı bir rebase kullanımı olarak değerlendirmek daha doğru olacaktır. Geçmişte atılan commit’leri yeniden düzenlemek, isimlendirmek veya birleştirmek için kullanıyoruz. Unutmamamız gereken bir nokta da, git squash işlemi yaptıktan sonra ‘force push’ kullanmamız gerektiğidir. İstenilen commit aralığını geri gidip yeniden düzenleme yaptıgımız için ‘force push’ kullanımı zorunludur.
#Agile Scrum ve Kanban

## Agile 

Agile modeli proje yönetimi, yazılım geliştirme sürecinde karşılaşılan problemleri çözmek üzere, tekrarlanan yazılım geliştirme modeli taban alınarak geliştirilmiş, sık aralıklarla parça parça yazılım teslimatını ve değişikliği teşvik eden bir yazılım geliştirme modeli.

### Agile Manifesto — 4 Temel Değer:

- İş süreçleri ve araçlardan ziyade **bireyler ve bireyler arasındaki etkileşim** değerlidir.

- Kapsamlı bir dokümantasyon sürecinden ziyade, **çalışan bir yazılım** ortaya koymak daha önemlidir.

- **Müşteri ile işbirliği yapmak**, sözleşme görüşmelerinden daha önemlidir.

- **Değişime cevap vermek**, mevcut planı izlemekten daha önemlidir.

## Scrum

Kendi rehberindeki tanımlaması “İnsanların mümkün olan en yüksek değere sahip ürünleri üretken ve yaratıcı bir şekilde geliştirirken, karmaşık ve adaptasyona açık sorunları ele alabildikleri bir çerçeve” olan scrum, agile proje yönetme metodolojilerinden biridir.

Bu şekilde, aylar boyunca lineer bir geliştirme süreci sonunda ürün çıkarmak yerine, hızla değişen ihtiyaçlara cevap verebilmek adına, haftalık çalışma planlamaları “sprint” adı verilen çalışma süreleri içinde gerçekleştirilir.

Her sprint’te yapılması gereken işler, kişiler tarafından sahiplenilir ve sprint sonunda ürün olarak çıkar. Sprint şu parçalardan oluşuyor:

- **Preparation:** İş sahipleri tarafından üretime hazırlanan doküman, araştırma ek tasarım gerektiren işler. Sprint boyunca aday olmaya hazırlanan işler.

- **Candidates:** Hazırlığı tamamlandığı düşünülen işler. Sprint meeting’de herkes bu listeden öncelik sıralamasına göre current’a kart alır. Sprint meeting’den önce hepimiz mutlaka göz gezdiririz. Alttaki sorular önceliğinde fikirler geliştirmek sprint toplantımızı hem daha verimli hem daha kısa ve öz hale getirir.

- **Current Sprint:** Bütün ekibin, içinde bulunulan sprint için üreteceğini taahhüt ettiği işleri içeren liste.

- **Review not accepted:** Müşteriden veya PB ekibinden geri dönmüş olan kartlar.

- **In progress:** Hepimizin o sırada hangi işlerle uğraştığımızı görebilmek için yapmaya başladığımız iş bu listeye alınır.

- **Waiting review:** Teste gönderilmiş. PB ekibindeki müşteri temsilcilerinin veya iş sahiplerinin testini bekleyenler.

- **Client test:** Gerçekten müşterilerin veya test’te deneme yapılamayan konular için iş sahiplerinin testini bekliyor.

- **Review accepted:** Test edilmiş, kabul edilmiş. Production’a alınabilir durumda olanlar.

- **Done:** Biten, kullanımda — yayında olan tüm işlerimiz.

## Kanban

Yazılım geliştirme yaşam döngünüsünü (Software Development Life Cycle) inceleyecek olursak, aşağıdaki grafikte olduğu gibi, birbirini tekrar eden adımlardan oluştuğunu göreceğiz.

![Life Cycle](https://miro.medium.com/max/875/1*yDHiyZIKVfX-gZLwvhh6Ng.png)

Bu bahsedilen adımları bir bütün olarak “sağlıklı” bir şekilde yönetmek amacıyla modeller ve metodolojiler geliştirilmiştir. KANBAN tekniğini **“Agile”** yazılım geliştirme metodolojisinin, **“SCRUM”** yaklaşımı altında sıklıkla görüyor oluruz.

Temelinde planlama, kontrol altında tutma gibi ihtiyaçlardan yola çıkarak geliştirilmiş olan bu metodolojiler kendi dinamikleri içerisinde de yardımcı araçlara ve tekniklere ihtiyaç duyarlar.

KANBAN’da bu tekniklerden birisidir. Elinizde bulunan kaynakları nasıl daha verimli bir şekilde kullanırsınız, nasıl daha planlı yönetirsiniz gibi problemlere efektif çözümler sunar.

# Github Lisanları


### GNU AGPLv3

* İzin Verilenler
	* Ticari Kullanım
	* Dağıtma
	* Değiştirme
	* Özel Kullanım
	* Patent Kullanımı: bu lisans katkıda bulunanlara patent alma hakkı verir.
	
* Şartlar
	* Kullandığınız yazılımı açık kaynaklı yapmak zorundasınız.
	* Lisansın bir kopyasını kullanacağınız yerde bulundurmalısınız.
	* Yazılım kullanılarak bir ağ servisi oluşturulursa da ilgili ağ servisini sağlayan yazılım açık kaynaklı olmalıdır.
	* Yeni yazılım aynı lisansla veya uyumlu lisansla lisanslanmalıdır.
	* Yazılımdaki değişiklikleri belirtmek zorundasınız.
	
* Sınırlamalar
	* Yazılımın kullanılmasından dolayı ortaya çıkabilecek sorunlardan yazar sorumlu tutulamaz.

### GNU GPLv3

* İzin Verilenler
	* Ticari Kullanım
	* Dağıtma
	* Değiştirme
	* Özel Kullanım
	* Patent Kullanımı: bu lisans katkıda bulunanlara patent alma hakkı verir.

* Şartlar
	* Kullandığınız yazılımı açık kaynaklı yapmak zorundasınız.
	* Lisansın bir kopyasını kullanacağınız yerde bulundurmalısınız.
	* Yeni yazılım aynı lisansla veya uyumlu lisansla lisanslanmalıdır.
	* Yazılımdaki değişiklikleri belirtmek zorundasınız.

* Sınırlamalar
	* Yazılımın kullanılmasından dolayı ortaya çıkabilecek sorunlardan yazar sorumlu tutulamaz.
	
### GNU LGPLv3

* İzin Verilenler
	* Ticari Kullanım
	* Dağıtma
	* Değiştirme
	* Özel Kullanım
	* Patent Kullanımı: bu lisans katkıda bulunanlara patent alma hakkı verir.

* Şartlar
	* Kullandığınız yazılımı açık kaynaklı yapmak zorundasınız.
	* Lisansın bir kopyasını kullanacağınız yerde bulundurmalısınız.
	* Yeni yazılım aynı lisansla veya uyumlu lisansla lisanslanmalıdır.
	* Yazılımdaki değişiklikleri belirtmek zorundasınız.
	
* Sınırlamalar
	* Yazılımın kullanılmasından dolayı ortaya çıkabilecek sorunlardan yazar sorumlu tutulamaz.


![Lisans](https://3.bp.blogspot.com/-c3WWMvQEMaM/V8xLOsb4rKI/AAAAAAAAdGE/c-0iLYZbtC0YSMYsf5ORFfSysM3-L7uRACLcB/s640/Floss-license-slide-image.png)

	
### MIT Lisansı

* İzin Verilenler
	* Ticari Kullanım
	* Dağıtma
	* Değiştirme
	* Özel Kullanım
	
* Şartlar
	* Lisansın bir kopyasını kullanacağınız yerde bulundurmalısınız.

*Sınırlamalar
	* Yazılımın kullanılmasından dolayı ortaya çıkabilecek sorunlardan yazar sorumlu tutulamaz.
	
### Apache Lisans 2.0

* İzin Verilenler
	* Ticari Kullanım
	* Dağıtma
	* Değiştirme
	* Özel Kullanım
	* Patent Kullanımı: bu lisans katkıda bulunanlara patent alma hakkı verir.

* Şartlar
	* Lisansın bir kopyasını kullanacağınız yerde bulundurmalısınız.
	* Yazılımdaki değişiklikleri belirtmek zorundasınız.
	
* Sınırlamalar
	* Yazılımın kullanılmasından dolayı ortaya çıkabilecek sorunlardan yazar sorumlu tutulamaz.
	* Marka Hakları (This license explicitly states that it does NOT grant you trademark rights, even though licenses without such a statement probably do not grant you any implicit trademark rights.)

### Mozilla Public Lisans 2.0

* İzin Verilenler
	* Ticari Kullanım
	* Dağıtma
	* Değiştirme
	* Özel Kullanım
	* Patent Kullanımı: bu lisans katkıda bulunanlara patent alma hakkı verir.

* Şartlar
	* Lisansın bir kopyasını kullanacağınız yerde bulundurmalısınız.
	* Yazılımdaki değişiklikleri belirtmek zorundasınız.
	* Yeni yazılım aynı lisansla veya uyumlu lisansla lisanslanmalıdır.
	
* Sınırlamalar
	* Yazılımın kullanılmasından dolayı ortaya çıkabilecek sorunlardan yazar sorumlu tutulamaz.
	* Marka Hakları (This license explicitly states that it does NOT grant you trademark rights, even though licenses without such a statement probably do not grant you any implicit trademark rights.)

# Github Flow nedir?

GitHub flow, dağıtımların düzenli olarak yapıldığı ekipleri ve projeleri destekleyen, hafif, branch tabanlı bir iş akışıdır.

- Master branchteki her şey yayınlanabilir.

- Yeni bir şey üzerinde çalışmak için açıklayıcı bir şekilde adlandırılmış bir branch oluşturulur.

- Geri bildirime veya yardıma ihtiyacınız olduğunda veya branchin birleştirilmeye hazır olduğunu düşündüğünüzde, bir pull request açılır.

- Başka biri özelliği inceleyip onayladıktan sonra onu master branche birleştirebilirsiniz. Merge ve push işlemleri yapıldıktan sonra ana branch hemen yayına alınmalıdır.

# Abstract vs İnterface 

![İnterface vs Abstract](https://miro.medium.com/max/826/1*vmQhGSTGAeIIsCX0jEPUqg.jpeg)

# Gang Of Four

Yaklaşık 25 yıl önce Gang of Four (GoF) olarak bilinen Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides, **'Design Patterns — Elements of Reusable Object-Oriented Software'** adında kitap yayınladılar ve ilk kez yazılım alanında tasarım kalıpları (design patterns) kavramını ortaya attılar.

Yazılım tasarım kalıpları 3 ana başlıkta incelenir. Bunlar:

* **Creational Design Patterns ( Yaratımsal Tasarım Kalıpları ) :** Nesnelerin **oluşturulması** ve **yönetilmesi** ile ilgili tasarım kalıplardır. Meydana gelebilecek değişikliklere karşı sorun çıkarmayacak şekilde nesneleri nerede ve nasıl yaratmamız gerektiği konusunda bize yardımcı olurlar.
	
	* Abstract factory
	* Builder
	* Factory method
	* Prototype
	* Singleton

* **Structural Patterns (Yapısal Kalıplar):** Nesnelerin birbirleri ile olan ilişkilerini düzenleyen kalıplardır. Sınıflar ve nesnelerin birleştirilerek daha geniş yazılım gruplarının kurulmasına yardımcı olan tasarım kalıplarıdır.
	
	* Adapter
	* Bridge
	* Composite
	* Decorator
	* Facade
	* Flyweight
	* Proxy

* **Behavioral Patterns (Davranışsal Kalıplar):** Birden fazla sınıfın bir işi yerine getirirken nasıl birlikte davranacağını belirleyen tasarım kalıplarıdır.

	* Chain of responsibility
	* Command
	* Interpreter
	* Iterator
	* Mediator
	* Memento
	* Observer (or Publish/Subscribe)
	* State
	* Strategy
	* Template method
	* Visitor

## Kaynakça 

- https://mozanunal.com/2016/09/ack-kaynak-yazlm-lisans-turleri-ve/
- https://medium.com/@PeopleBox/agile-nedir-scrum-nedir-ba%C5%9Far%C4%B1l%C4%B1-proje-y%C3%B6netimi-y%C3%B6ntemleri-nelerdir-64c4ae723496
- https://medium.com/@sercandumansiz/kanban-tekni%C4%9Fi-nedir-4e2b3bdebd49
- http://fehmicansaglam.net/git-flow-bir-gelistirme-surecinin-anatomisi
- https://medium.com/neyasistechnology/git-rebase-squash-ile-ge%C3%A7mi%C5%9Fi-yeniden-d%C3%BCzenlemek-9de36441f947
- https://stackoverflow.com/questions/1673841/examples-of-gof-design-patterns-in-javas-core-libraries


