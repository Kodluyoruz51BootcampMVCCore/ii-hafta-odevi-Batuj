# II Hafta (6-7 Haziran) Ödevleri 

## 6 Haziran Ödevleri:
- [ ] Github'ın Gitflow'u ile diğer yaklaşımları arasındaki fark nedir? ( gitflow vs ..)
- [ ] [Git and GitHub with Briana Swift](https://www.youtube.com/playlist?list=PLg7s6cbtAD17Gw5u8644bgKhgRLiJXdX4) Youtube Listesi incelensin. (11 Video)
- [ ] Merge pull request
    - [ ] Create a merge commit
    - [ ] Squash and merge 
    - [ ] Rebase and merge altında ne fark var (Ödev)
- [ ] issue ve #pull request de id ler neden artıyor farklı sekmeler olmasına rağmen?
- [ ] [Ramp up on Git and GitHub](https://lab.github.com/githubtraining/paths/ramp-up-on-git-and-github) (ödev)
- [ ] Aspnetboilerplate ve yan ürünler araştırması. [AspNet Boilerplate - Web Application Framework](https://aspnetboilerplate.com/)
- [ ] hackerRank.com --> [30 Days Of Code](https://www.hackerrank.com/domains/tutorials/30-days-of-code)


## 7 Haziran Ödevleri:
- [ ] Razor Pages Nedir?
- [ ] 4 Farklı Projede Yapılacak *Change Authentication* :
  - [ ] No Authentication
  - [ ] Individual User Account
  - [ ] Work or School Accounts
  - [ ] Windows Authentication seçili projeler oluşturulmalı
- [ ] Ayarlardaki Output kısmındaki Console Application nedir? diğerleri arasında fark nedir? [Ders Akışındaki 6. Madde'yi inceleyin.] ( araştırma ödev verildi ).
- [ ] c# json serialize / deserialize
- [ ] MVC vs MVVM
   - [ ] MVP vs MVW vs MVU Pattern arasındaki farkı araştır
   - [ ] Model-View-Update (MVU) nedir?

**GitFlow;**

Gitflow, zamanlanmış bir yayın döngüsü olan projeler için idealdir. Farklı dallara çok özel roller atar ve nasıl ve ne zaman etkileşime girmeleri gerektiğini tanımlar.

Master ve develop olmak üzere iki ana koldan oluşur.Master üretimin bitmiş halini develop ise geliştirme amaçlı kullanılan bir daldır. Bir de ana koldan kopmadan ve master ile birleşmeden gelişen özellik dalları bulunur. Bunlar; feature,hotfix,release olarak tanımlanır.

**Feature;** özellik dalları, gelecek sürümler için yeni özellikler geliştirmek için kullanılır. Gelişmeden ayrılabilir ve gelişmek üzere birleşmelidir.

**Hotfix;** düzeltme dalları, master'ın istenmeyen durumuna derhal davranmak için gereklidir. Ustadan ayrılabilir ve ustaya karışıp gelişmelidir.

**Release;** sürüm dalları yeni bir üretim sürümünün hazırlanmasını sağlar. Birçok küçük hatanın düzeltilmesine ve bir sürüm için meta verilerin hazırlanmasına izin verir. Gelişimden ayrılabilir ve ustalaşıp gelişmelidir.

**Git flow ne zaman kullanılır?**

--Sürekli dağıtımda veya sürümlerde çalışılması sebebi ile sürüm tabanlı bir yazılım geliştirme için uygundur.

--Geliştirme kolu geliştirme ve proje arasında güvenlik sağlar.

![gitflow](https://user-images.githubusercontent.com/66273342/84819643-04410200-b021-11ea-8ffc-27736bbdb723.PNG)



**Github Flow;**

GitHub Flow, dağıtımların düzenli olarak yapıldığı ekipleri ve projeleri destekleyen hafif, dallanan bir iş akışıdır. Bir proje üzerinde çalışırken, herhangi bir zamanda devam eden bir dizi farklı özellik veya fikre sahip olunabilir. 

Github ile yeni bir **branch** oluşturulması gerekir. Böylelikle yapılacak değişiklikler ana dalı etkilememiş olur. Oluşturulan bu şubeye bir dosya eklendiğinde, düzenlendiğinde veya silindiğinde, **commit** işlemi gerçekleştirilmiş olup ve bunlar şubeye eklenmiştir. Oluşturduğumuz bu fikri paylaşmak veya fikir almak için ise **pull request** oluşturarak geri bildirimler de alınabilir. Paylaşılan yenilik tartışılır, test edilir, incelenir. Bunun sonrasında değişiklikler ana dal ile **merge** edilir yani birleştirilir.

**Github Flow ne zaman kullanılır?**

--Sürekli Entegrasyon ve sürekli dağıtım için uygundur.

--Küçük iyileştirme yapılacağı zaman kullanılabilir.

![githubflow](https://user-images.githubusercontent.com/66273342/84819563-e70c3380-b020-11ea-878d-f26312471823.PNG)


**Değişiklikleri Merge Etme Yöntemleri**

**1.Merge Commit:** Geliştirilen dalda tutulan tüm commit geçmişini ana dala aktarır.

**2.Rebase and Merge:** Yapılan tüm commitleri birleştirme commiti kullanmadan tek tek taban dalına ekler.

**3.Squash and Merge:** Katkıda bulunan kişinin yaptığı tüm değişiklikleri bir konu dalında görmek yerine tek bir commit ile varsayılan dalda birleştirme yapılır.

**Rebase ve Merge Farkları Nelerdir?**

İkisinin de amacı iki branchi birleştirmek olan yapılardır. Tek farkları aşağıdaki resimde de görüldüğü gibi daha sade bir birleştirme için rebease, fakat tüm geçmişin ayrıntılı bir şekilde görülmesi için merge yapılması daha uygun olacaktır. Ekip şeklinde çalışılıyor ise özellikle merge önerilir.


![mergerebease](https://user-images.githubusercontent.com/66273342/85228113-299b8a80-b3ea-11ea-9b1c-1b60e9f20954.png)


**Razor Pages Nedir?**

ASP .NET içinde yer alan MVC ile uygulama geliştirmek kolay olsa da küçük çaplı uygulamalarda bu uygulamanın kullanılması gerekmeyebilir. Razor Pages daha küçük uygulamalarda kullanılan web uygulama geliştirme yöntemidir.

**Console Application Nedir?**

Console grafiksel olmayan, kullanıcıdan bilgi alıp verme kısmını siyah ekran üzerinde gerçekleştiren bir uygulamadır. Daha çok programcılığa giriş kısmında kullanılır.

Bir de Windows Form Application kullanımı mevcuttur. Bu ise daha çok görsel eklentilerin olduğu bir uygulamadır. Günümüzde kullanımı yaygındır. Grafik arayüzüne sahip bir uygulamadır.


**Json C# Serialize ve Deserialize Nedir?**

**Serialize:** Bir datayı kolayca erişebilir hale getirmek için string-->nesneye çevirme olayını yapma kısmına denir.

**Deserialize:** Nesneye çevrilmiş datayı hangi dilde yazılıyor ise ona çevirme olayıdır. Kısacası; nesne-->string.

**MVC Nedir?**

Model uygulamaların verilerinin tutulmasından sorumludur.

View bu kısımda Business Layer içermeden sunum kısmından sorumludur.

Controller ise kullanıcıdan aldığı veriler ile Business Layer'ın işlenmesi için gerekli hizmetlerin çağrılmasından sorumludur. İşlenen verilerin sunulması için view ile tekrar bağlantı kurar.

Aşağıda şeması verilmiştir.


![mvc-architecture](https://user-images.githubusercontent.com/66273342/85952082-aa6d0000-b96f-11ea-8b8b-a182cfc0aab4.gif)

**MVVM Nedir?**

MVVM yapısına aslında WPF de denebilir. Burada View ile bilgiler Presentation Model tarafından tutulur. Business Layer ile koordinasyonu sağlayıp View için karar verme kısmını azaltıyor.



**MVP Nedir?**

MVP MVC’den evrilmiştir. Sadece bağımlılıkları farklıdır. Inputları direk View karşılar. Burada View Presenter’ı biliyor. Presenter ise View’ı interface aracılığı ile biliyor. Kısacası MVC arasındaki en büyük fark View’ın işlemlerini(güncelleme, bilgi alışverişi) bir interface aracığı ile halledebilmesidir.






