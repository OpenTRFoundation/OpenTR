---
title: "Birey Başlangıç Rehberi"
linkTitle: "Birey Başlangıç Rehberi"
description: Bu rehber, bireylerin açık kaynaklı projelerde nasıl katkıda bulunabileceklerini anlamalarına yardımcı olmak ve neden katkı yapmalarının kendileri için faydalı olacağını anlatmak için tasarlanmıştır.
weight: 20
---

<img src="/images/individual_map.png" class="img-fluid"/>


<div class="containerx mx-0" style="text-align: center;">
{{% markdown %}}
## Seviyeni seç
{{% /markdown %}}


<div class="card-group">
  <div class="card">
    <img src="/images/individual_step_1.jpeg" class="card-img-top">
    <div class="card-body">
      <h5 class="card-title">Açık kaynak katkısına istekliyim, ama teknik yetkinliğim yok</h5>
      <p class="card-text">Açık kaynağın ne olduğunu, açık kaynağa nasıl katkı yapacağımı ve nelere ihtiyaç duyacağımı öğrenmek istiyorum.</p>
    </div>
    <div class="card-footer" style="background-color: unset; border-top: unset;">
        <div class="d-grid gap-2">
          <a href="#açık-kaynak-katkısına-istekliyim-ama-teknik-yetkinliğim-yok" class="btn btn-lg btn-outline-primary" type="button">Seç</a>
        </div>
    </div>
  </div>
  <div class="card">
    <img src="/images/individual_step_2.jpeg" class="card-img-top">
    <div class="card-body">
      <h5 class="card-title">Açık kaynağa katkı yapmak istiyorum</h5>
      <p class="card-text">Programlamayı yeterince biliyorum, teknik olarak yeterliyim. Ancak, açık kaynak projelere katkı yapmadım ve nereden başlayacağımı bilmiyorum.</p>
    </div>
    <div class="card-footer" style="background-color: unset; border-top: unset;">
        <div class="d-grid gap-2">
          <a href="#açık-kaynağa-katkı-yapmak-istiyorum" class="btn btn-lg btn-outline-primary" type="button">Seç</a>
        </div>
    </div>
  </div>
  <div class="card">
    <img src="/images/individual_step_3.jpeg" class="card-img-top">
    <div class="card-body">
      <h5 class="card-title">Açık kaynağa katkı yapıyorum</h5>
      <p class="card-text">Zaten bir açık kaynak projeye katkıda bulunuyorum ve liderlik yapmak istiyorum.</p>
    </div>
    <div class="card-footer" style="background-color: unset; border-top: unset;">
        <div class="d-grid gap-2">
          <a href="#açık-kaynağa-katkı-yapıyorum" class="btn btn-lg btn-outline-primary" type="button">Seç</a>
        </div>
    </div>
  </div>
</div>

</div>


## Açık kaynak katkısına istekliyim, ama teknik yetkinliğim yok

### Giriş

OpenTR'nin hazırladığı bireyler için açık kaynağa başlangıç rehberine hoşgeldin!

Rehberin bu kısmında, açık kaynağa en baştan başlayacağız.

Herhangi bir kısımda bize ulaşıp yardım almak istersen, <https://opentr.netlify.app/contact/> adresinde yazılan iletişim seçeneklerinden birisi ile bize ulaşabilirsin.

### Yol Haritan

#### 1. Açık kaynak hakkında bilgi sahibi ol

Açık kaynağın tanımı, terimleri ve tarihçesi gibi bilgileri öğrenmek için, [Açık Kaynağa Giriş](/docs/introduction-to-open-source/) belgelerimizi oku.

#### 2. Teknik yetkinlik kazan

Açık kaynak projelere katkı yapmanın çeşitli yöntemleri var. Öncelikle kod katkısı yapma konusundan bahsedeceğiz. Diğer katkı çeşitleri için belgemizin devamını incele.

Açık kaynak projelere katkı yapman için, öncelikle projelerde kullanılan teknik konularda yetkinlik kazanman gerek. Bu teknik konular hakkında internette yeterli kaynak bulunduğu için, burada sadece bunların listesini vereceğiz.

**Git:** Açık kaynak projelerin neredeyse tamamı Git kullanmakta. Git bir kod versiyonlama sistemi ve açık kaynak toplulukların kendi içinde bir çalışma süreci oluşturmasını sağlar. Git'i öğrenmek için [Ali Özgür](https://github.com/aliozgur)'ün hazırladığı ücretsiz [Türkçe Git 101](https://aliozgur.gitbooks.io/git101/content/) kitabını okuyabilirsiniz. Kitapta alıştırmalar da bulunmakta.

**GitHub:** Açık kaynak dünyası GitHub'da yaşıyor! GitHub, Git kullanan projelerin (neredeyse açık kaynak projelerin hepsi) barındırıldığı bir online sistemdir. Git öğrendikten sonra, GitHub da kullanmayı öğrenin. GitHub sadece kod barındırmayı sağlamıyor. Aynı zamanda, proje takibi, kod inceleme, tartışmalar gibi bir projede gerekli hemen herşeyi sağlıyor. Burada şu terimleri ve bunları GitHub'da nasıl gerçekleştirdiğini öğrenmen gerekiyor: issue, pull request (PR), code review.

**Programlama dilleri:** Açık kaynak projelere katkı yapmak istiyorsan, bir programlama dili de bilmen gerekiyor. Her dilde bir açık kaynak proje bulunsa da, daha etkili ve önemli projelere katkı yapabilmen için şu dillerden birisini iyi bilmeni tavsiye ederiz: Javascript/Typescript, Java, Python, Go, C#. Bu dilleri öğrenmek için internette birçok Türkçe kaynak mevcut.

**İşletim sistemi ve platform öğren:** Bilgisayar kullanıyorsan bir işletim sistemini zaten biliyorsundur, ama açık kaynak projelerde oldukça sık kullanılan Linux işletim sistemini öğrenmeni tavsiye ederiz. Benzer şekilde, programlama dili biliyor olabilirsin, ama platform da öğrenmeni tavsiye ederiz. Yani, Javascript bilen bir kişi Node bilmeyebilir. Bildiğin dili kullanabileceğin platformları araştır.

#### 3. İngilizce öğren

Açık kaynak dünyası İngilizce konuşuyor. Aslında İngilizce yazışıyor. Senin de okuma ve yazma seviyesinde temel İngilizce öğrenmen gerekiyor. Bu göz korkutucu olsa da, aslında teknik İngilizce öğrenmek çok daha kolay. Ayrıca açık kaynak projelerde çok farklı ülkelerden ve kültürlerden insanlar olduğu için, idare eder bir İngilizce de işini görecektir.

#### 4. Eğitim al

Açık kaynağı veya katkı gereksinimlerini en iyi öğrenme yöntemi aslında daha düzenli bir eğitim almak. Tavsiyemiz üniversite eğitimi!

Üniversite eğitiminin herkesin erişebileceği birşey olmadığının farkındayız. Ama aşağıda bahsedeceğimiz eğitimler daha erişilebilir.

**42 Okulları:** [Türkiye Açık Kaynak Platformu](https://www.turkiyeacikkaynakplatformu.com/) bünyesinde faaliyet gösteren [42 Okulları](https://42istanbul.com.tr/)'nın birkaç şubesi bulunmakta. Başvuran adaylar arasında sınav ile seçim yapılarak kabul alınan okullarda, ücretsiz olarak yazılım eğitimi veriliyor.

**Udemy:** [Udemy](https://www.udemy.com/?locale=tr_TR), eğitmenlerin online olarak videolar ile ders verdiği bir site. Burada özellikle programlama dilleri için oldukça fazla Türkçe ders bulunmakta.

**Youtube:** Udemy kadar düzenli olmasa da, Youtube üzerinde de birkaç bölümden oluşan programlama dersleri var. Özellikle [Folksdev](https://www.youtube.com/c/FolksDev) benzeri kanallarda ve sonraki kısımlarda bahsettiğimiz topluluklarda oldukça kapsamlı dersler bulunmakta.

#### 5.Türkiye'deki topluluklara katıl

Yeni başladığın için soruların olacak! Yol gösteren kişilere veya seninle aynı durumdaki kişilerin fikrini almaya ihtiyacın olacak!

Açık kaynak konusundaki soruların için OpenTR'nin [iletişim kanallarından](/contact/) (Discord, Slack, vs.) bizimle iletişime geçebilirsin.

Programlama ile ilgili konularda ise, ilgili dil ve teknoloji ile ilgili topluluklarla iletişime geçmeni tavsiye ederiz.

Toplulukların listesine [Türkiye'deki Yazılım Toplulukları](/docs/communities-in-turkey/) sayfamızdan ulaşabilirsin.

Bu toplulukların çoğunun chat kanalları mevcut ve amaçları bilgi paylaşımı. Burada önemli olan konu, soru sorarken önden internet araştırması yapmak ve sonrasında çekinmemek! Merak etme herkes aynı yollardan geçti!

Aynı zamanda toplulukların çoğu, online veya fiziksel olarak farklı etkinlikler düzenliyor ve ücretsiz dersler de veriyor.

#### 6. Etkinliklere katıl

Üstte bahsedilen toplulukların yaptıkları yayınların yanı sıra, Türkiye'de birçok yazılım etkinliği düzenlenmekte. Bunların çoğu ise tüm seviyelerden kişiler için.

Etkinliklere katılman hem benzer durumdaki kişiler ile tanışman için, hem de bağlam kazanman ve bilgiye maruz kalman için önemli. Konuşmaların tamamını anlamasan da, bilgiye maruz kalma sayesinde belirli bir aşamadan sonra kullanılan dili ve terimleri anlamaya başlayacaksın.

Bilinen etkinlikleri [Türkiye'deki Yazılım Etkinlikleri](/docs/conferences-in-turkey/) sayfamızdan bulabilirsin.


## Açık kaynağa katkı yapmak istiyorum

### Giriş

OpenTR'nin hazırladığı bireyler için açık kaynağa başlangıç rehberine hoşgeldin!

Rehberin bu kısmında, açık kaynak hakkında bilgi sahibi olduğunu ve teknik yeterliliğe sahip olduğunu varsayıyoruz. Dolayısıyla, açık kaynak projelere katkı için hazır olduğunu düşünüyoruz. Eğer bu durumda değilsen, [bir önceki aşama için hazırladığımız yol haritası](#açık-kaynak-katkısına-istekliyim-ama-teknik-yetkinliğim-yok)nı okuman iyi olacaktır.

Her durumda, açık kaynağın tanımı, terimleri ve tarihçesi gibi bilgileri öğrenmek için, [Açık Kaynağa Giriş](/docs/introduction-to-open-source/) belgelerimizi okumanı tavsiye ederiz.

Herhangi bir kısımda bize ulaşıp yardım almak istersen, <https://opentr.netlify.app/contact/> adresinde yazılan iletişim seçeneklerinden birisi ile bize ulaşabilirsin.

### Neden açık kaynak katkısı?

Açık kaynak katkısı yapmak, kendini geliştirmenin ve yazılım geliştirme sürecini öğrenmenin en iyi yollarından birisidir.

Açık kaynak katkısı yaparak, yazılım geliştirme sürecini öğrenirken aynı zamanda bir topluluğun bir parçası olursun.

Ancak, daha önce hiç açık kaynak katkısı yapmadıysan, bu süreç biraz kafa karıştırıcı olabilir. Bu rehber, açık kaynak katkısı yapmaya başlamak için ihtiyacın olan bilgileri sağlamak için hazırlandı.

Açık kaynak kullanmanın faydalarını, [Açık Kaynağın Bireyler için faydaları](/docs/introduction-to-open-source/benefits-of-oss-usage-for-individuals/) yazımızda bulabilirsin. Ancak, katkı yapmak, kullanmanın bir atım ötesine geçmek anlamına gelir.


#### Becerilerini Geliştir

Açık kaynak projelere katkıda bulunmak, yazılım geliştirme becerilerini geliştirmenin harika bir yoludur. Farklı kod tabanları üzerinde çalışarak, yeni programlama teknikleri ve araçları öğrenebilirsin. Ayrıca, hata ayıklama ve problem çözme becerilerini de geliştirme fırsatı yakalarsın.


#### Özgeçmişini Güçlendir

Açık kaynak projelere katkıda bulunmak, özgeçmişini güçlendirmenin de harika bir yoludur. Potansiyel işverenler, bu tür projelere katılmış olmanı, problem çözme ve iş birliği yapma becerilerine sahip olduğunun bir göstergesi olarak göreceklerdir.


#### Bir Topluluğun Parçası Ol

Bu projeler, dünya çapında geliştiricilerden oluşan bir topluluğa katılma imkanı sunar. Bu topluluktan yeni şeyler öğrenebilir, diğer geliştiricilerle bağlantı kurabilir ve iş birliği yapabilirsin.


#### Deneyim Kazan

Açık kaynak projelere katkıda bulunmak, gerçek dünya projelerinde yer alma deneyimi kazanmak için de harika bir yoldur. Bu sayede, yazılım geliştirme yaşam döngüsünün tüm aşamalarını deneyimleme şansı yakalarsın.


#### Etki Yarat

Açık kaynak projelere katkıda bulunmak, kullandığın yazılımları geliştirmeye ve diğer insanlara fayda sağlamaya yardımcı olmanın bir yoludur. Kullanıdığın projelere geri verimde bulunarak, bu projelerin daha iyi hale gelmesine katkıda bulunabilirsin.


### İlk yapman gerekenler

#### Oryantasyon

Öncelikle, hazırladığımız [Açık Kaynağa Giriş](/docs/introduction-to-open-source/) belge serisini oku.

Bu belgeler sadece katkı yapmak isteyenler için değil, açık kaynak projeler hakkında genel bilgi edinmek isteyenler için de faydalıdır.


#### Öğrenme Kaynaklarına bak

Açık kaynak projelere katkıda bulunmak için ihtiyacın olan becerileri öğrenmek için çeşitli kaynaklar mevcut.

Seçtiğimiz bazı kaynaklara göz atabilirsin:

- 📖 [Açık Kaynağa Nasıl Katkıda Bulunulur](https://opensource.guide/tr/how-to-contribute/)

- 📖 [Do you want to start contributing to open source and need help figuring out where to begin?](https://contribute.cncf.io/contributors/getting-started/)

- 📖 [Getting started with contributing to open source](https://stackoverflow.blog/2020/08/03/getting-started-with-contributing-to-open-source/)

- ▶ [How to Find Good First Issues in Open Source?](https://www.youtube.com/watch?v=ZIkkPzTuOXw)


#### Mentorluk almayı dene

Mentorluk, açık kaynak projelere katkıda bulunmak isteyenler için harika bir yoldur. Bir mentör, sana yol gösterir, sorularını yanıtlar ve katkılarını inceleyerek geri bildirimde bulunur. Aslında, mentorluk almak, açık kaynak projelere katkıda bulunmanın en iyi yoludur.

Bir açık kaynak proje topluluğu içindeki bir mentordan hem açık kaynak kültürü hem de projenin kod tabanı hakkında bilgi alabilirsin.

Ancak, senin de zamanının sınırlı olduğu gibi herkesin zamanı sınırlıdır ve birçok açık kaynak projenin mentorluk programları yoktur. Bu yüzden, mentorluk almak için biraz çaba harcaman gerekebilir.

Mentorluk almak için en güzel yöntem, bir programa başvurmak olacaktır.

Aşağıda, başvurabileceğin bazı örnek programları listeledik:

|                                                                                  |                                                                            |                     |                   |
|:--------------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|:-------------------:|:-----------------:|
|                                   **Program**                                    |                              **Hedef kitle**                               | **Zaman ihtiyacı**  |    **Yöntem**     |
|                              [OpenTR ATOM](/atom/)                               | Teknik bilgisi olan ve açık kaynak katkıya ilk adımı atmak isteyen kişiler | Part time, 10 hafta | Birebir mentorluk |
|          [Google Summer of Code](https://summerofcode.withgoogle.com/)           |         Öğrenciler ve açık kaynağı başlangıç seviyesinde bilenler          |   Full time, 3 ay   | Birebir mentorluk |
| [Linux Foundation Mentorship](https://lfx.linuxfoundation.org/tools/mentorship/) |         Öğrenciler ve açık kaynağı başlangıç seviyesinde bilenler          |   Full time, 3 ay   | Birebir mentorluk |

İnternette araştırma yaparak farklı birçok program bulabilirsin. Yukarıdaki listelediklerimiz bizim önerdiğimiz programlardır.

Bu programlar mentorluk için tek yol değil! Açık kaynak projelerin Slack, Discord, IRC gibi topluluk kanallarına katılarak da mentorluk alabilirsin. Bu topluluklarda, projenin kod tabanı hakkında sorular sorabilir, yardım isteyebilir ve katkılarını inceleyerek geri bildirim alabilirsin.

Hatta, bazı projelerin kendine özgü mentorluk programları olabilir. Bu yüzden, katkı yapmak istediğin projenin topluluk kanallarına katılarak mentorluk almak için bir adım atabilirsin.


### Katkıya hazır mısın?

Katkıya hazır hissediyorsan, aslında yapman gereken üç şey var:

1. Proje seç
2. İlk görevini belirle
3. Topluluk ile etkileşimde bulun


#### Proje seç

"Proje seç" demek kolay, biliyoruz. Ama aslında, katkı yapmak istediğin projeyi seçmek, katkı yapmaya başlamak için en önemli adımdır.

Peki, hangi projeyi seçmelisin? Bunlar için aşağıda birkaç öneri hazırladık ve bu öneriler yukarıdan aşağıya doğru önem sırasına göre sıralanmıştır:

1. Kullandığın bir projeye katkıda bulunmaya çalışabilirsin. Bu en mantıklı seçenek olabilir çünkü projeyi zaten kullanıyorsun ve projenin eksiklerini, hatalarını veya iyileştirilebilecek yönlerini biliyorsun.

2. Bir foundation altındaki projeleri seçmeye çalışabilirsin. Bu projeler genellikle daha organize ve daha fazla kaynağa sahiptir. Örnek olarak, Apache Software Foundation, Eclipse Foundation ve Linux Foundation altındaki projeleri seçebilirsin.

3. Proje dokümantasyanuna ve GitHub issue'larına baktığında, yeni katkıya başlayanlar için yeterli dokümantasyon ve yardım sunan projeleri seçebilirsin. Bu projeler genellikle "good first issue" etiketi ile işaretlenmiş görevler sunarlar. Bu tarz görevleri ve projeleri, <https://goodfirstissues.com/> gibi sitelerde bulabilirsin.

4. Stratejik projeleri seçebilirsin. Örneğin, kariyer hedeflerine uygun projeleri seçebilirsin. Eğer bir teknolojiye veya dile hakim olmak istiyorsan, o teknolojiyi veya dili kullanan projeleri seçebilirsin.

5. Etrafında hype olan projeleri seçebilirsin. Bu projeler genellikle daha fazla katılımcıya sahiptir ve bu sayede daha fazla yardım alabilirsin. Günümüzde özellikle yapay zeka ve cloud teknolojileri hakkındaki projeler çok popülerdir.

Bu aşamada [OpenTR'ye ulaşabilir](/contact/) ve projen seçimi konusunda yardım alabilirsin.

Biliyoruz proje seçimi çok zor. Çünkü projenin teknik detaylarını bilmiyorsun ve projenin topluluğu ile etkileşimde bulunmadın. Ayrıca, belki de proje yeterli olgunluğa ulaşmıştır ve yeni katkı yapmak oldukça zor olabilir.

O yüzden belki de bir projeyi değil de sana uygun bir görevi bulman ve ondan sonra üstte bahsettiğimiz önerileri de göz önünde bulundurarak projeyi seçmek daha mantıklı olabilir.


#### Görev bul

Yukarıda da bahsettiğimiz gibi, doğrudan bir projeyi seçmek yerine, bir görev bulmak ve ondan sonra projeyi seçmek daha kolay olabilir.

Projeler çoğunlukla "good first issue" etiketi ile işaretlenmiş görevler sunarlar. Bu görevler genellikle yeni katkı yapmaya başlayanlar için uygun olacak şekilde hazırlanmıştır.

Aşağıda sıraladığımız kaynaklarda, bu tarz görevleri bulabilirsin:

- 📖 [Good First Issues](https://goodfirstissues.com/): Tüm GitHub projelerindeki "good first issue" etiketli görevleri listeleyen bir platform.

- 📖 [CLOTributor](https://clotributor.dev/): CNCF altındaki projelerdeki "good first issue" etiketli görevleri listeleyen bir platform.

Başka örnek kaynaklar için, [https://opensource.guide/tr/how-to-contribute/](https://opensource.guide/tr/how-to-contribute/#katk%C4%B1da-bulunacak-bir-proje-bulma) adresindeki "Katkıda bulunacak bir proje bulma" bölümüne bakabilirsin.

Bu sitelerde, programlama dili, teknoloji, proje kategorisi gibi kriterlere göre filtreleme yaparak, sana uygun görevleri bulabilirsin. Unutma, [Proje seç](#proje-seç) bölümünde önemine göre sıraladığımız kriterleri de göz önünde bulundur!

Ayrıca, görev seçimi oldukça zor olabilir. Bu yüzden, [OpenTR'ye ulaşarak](/contact) yardım alabilirsin. Benzer şekilde, Türkiye'deki diğer [yazılım topluluklarına](/docs/communities-in-turkey/) da danışabilirsin.

#### Görevi buldun, sırada ne var?

İlk yapacağın şey ev ödevini yapmak olmalı. Görevin gereksinimleri ve proje hakkında fikir sahibi olmalısın.

Örneğin, proje hakkında öncelikle projenin ne işe yaradığı, hangi problemi çözdüğü, kimlerin kullandığı gibi genel bilgileri öğrenmelisin. Sonrasında kendi ortamında projeyi çalıştırmalı ve projenin kod tabanını incelemelisin.

Sonrasında ise, doğrudan işe koyulmak yerine, proje topluluğuna katılarak projenin topluluğu hakkında bilgi sahibi olmalısın. Bu sayede, projenin kod tabanı hakkında sorular sorabilir, yardım isteyebilir ve katkılarını inceleyerek geri bildirim alabilirsin.

Bunları yaptıktan sonra, tercihen GitHub issue'su üzerinden anlamadığın yerleri sorarak, görevin gereksinimlerini tam olarak anlamalısın. Herşeyi anladıysan da, yapmaya başlamadan önce, yapmak istediğin şeyleri listeleyip geri bildirim isteyebilirsin. Sonrasında, işe koyulup PR gönderebilirsin!

Toplulukla etkileşimde bulunmak, açık kaynak projelere katkıda bulunmanın en önemli adımlarından birisidir. Bunu GitHub issue'su üzerinden yapabileceğin gibi, projenin Slack, Discord, IRC gibi topluluk kanallarına katılarak da yapabilirsin. Ancak, kişilere özelden yazmamaya özen göstermelisin!


#### İlk görevi tamamladın, ya sonra?

Sıradaki görev için hazırsın! Ancak, artık daha fazla sorumluluk alabilirsin...

Proje toplantılarına katılabilir, proje dokümantasyonunu güncelleyebilir, proje topluluğuna yardım edebilir, proje yönetimine katkıda bulunabilir, proje içindeki diğer katkıda bulunanlara mentorluk yapabilirsin. Hepsini yapmak hemen mümkün olmayabilir, ama zamanla bunları yapabileceğinden emin ol!

Burada ayrıca bahsetmek istediğimiz bir nokta da, proje toplantılarına katılmanın faydaları. Eğer proje topluluğu online video görüşmesi yapıyorsa, bu toplantılara katılmanı öneririz. Bu toplantılar, projenin geleceği hakkında bilgi sahibi olmanı sağlar ve projenin topluluğu ile daha yakın ilişkide olmanı sağlar. İlk başta herşey çok karışık gelse de, bilgiye maruz kalmak bile büyük etki yaratabilir.


### Biliyoruz kolay değil

Tüm bunların kolay olmadığını ve kafa karıştırıcı olduğunu biliyoruz. Ama, bu süreçte [OpenTR'ye ulaşarak](/contact/) yardım alabilirsin. Slack ve Discord kanallarımız üzerinden, diğer katkıda bulunanlardan yardım isteyebilirsin.


## Açık kaynağa katkı yapıyorum

### Giriş

OpenTR'nin hazırladığı bireyler için açık kaynağa başlangıç rehberine hoşgeldin!

Rehberin bu kısmında, açık kaynağa zaten katkı yaptığını varsayıyoruz. Eğer bu durumda değilsen, bir önceki aşama veya daha önceki aşama için hazırladığımız yol haritalarını okuman iyi olacaktır.

Her durumda, açık kaynağın tanımı, terimleri ve tarihçesi gibi bilgileri öğrenmek için, Açık Kaynağa Giriş belgelerimizi okumanı tavsiye ederiz.

Herhangi bir kısımda bize ulaşıp yardım almak istersen, <https://opentr.netlify.app/contact/> adresinde yazılan iletişim seçeneklerinden birisi ile bize ulaşabilirsin.

### Bize ulaş

Zaten açık kaynak projelere katkıda bulunuyorsan, zaten OpenTR'nin insanları ulaştırmak istediği noktadasındır. Ancak, yapabileceğin şeyler hala var!

Öncelikle, bu yetkinliğini kullanarak çevrendekiler için bir mentör olabilirsin. Açık kaynak projelere katkıda bulunmak isteyenlere yardımcı olabilir, onlara yol gösterebilir ve onları destekleyebilirsin.

[OpenTR'ye ulaşırsan](/contact/), senin yetkinliğini kullanarak başkalarına yardımcı olman için fırsatlar sunabiliriz. Ayrıca, senin gibi açık kaynak projelere katkıda bulunan diğer kişilerle tanışmanı sağlayabiliriz.

Bununla beraber, sadece katkı yapmakla kalmayıp, açık kaynak projelerin topluluklarında liderlik yapabilirsin. Projeyi yönlendirebilir, topluluğu yönetebilir ve projenin geleceği hakkında kararlar alabilirsin. Bunlar için de sürekli ve tutarlı katkılar yapman gerekecektir.

### Liderlik

Açık kaynak projelerin topluluklarında liderlik yapmak, katkıda bulunmanın bir sonraki adımı olabilir. Bu, projenin geleceği hakkında kararlar almanı, topluluğu yönlendirmeni ve projenin başarısını sağlamanı gerektirir.

Peki liderlik yolunda neler yapabilirsin?

- Proje toplantılarında aktif olarak yer alabilir ve sorumluluk alabilirsin.
- Başka insanların PR'larını inceleyerek geri bildirimde bulunabilirsin.
- Projenin katkı kılavuzunu yeni katkıda bulunmak isteyenlere yardımcı olacak şekilde güncelleyebilirsin.
- Proje topluluğunda mentorluk yapabilirsin.
- Çatı gruplarda yer alabilir ve senin projenin beraber çalıştığı diğer projelerle etkileşimde bulunabilirsin.


Bütün bunları da, yine OpenTR ile irtibata geçerek yapabilirsin!

### Türkiye'deki ekosisteme katkı

Türkiye'deki yazılım ekosisteminin gelişmesi için, yetkinliklerine kullanarak senin yapabileceğin çok şey var!

Öncelikle, OpenTR'nin açık kaynak mentorluk programı [ATOM](/atom/) programında mentorluk yaparak, yeni katkıda bulunanlara yardımcı olabilirsin. Bu program, yeni katkıda bulunanlara yardımcı olmak isteyenler ile mentorluk yapmak isteyenler arasında bir köprü görevi görüyor.

Daha az zahmet gerektiren bir seçenekler ise şunlar:

- OpenTR'nin iletişim kanallarına katılman ve soruları yanıtlaman
- OpenTR'nin kendisine katkıda bulunman (belge, topluluk yönetimi, vb.)
- Türkiye'deki diğer yazılım topluluklarına katılman


### Sırada ne var?

Evet, OpenTR olarak Türkiye'den açık kaynak projelere katkıda bulunanların sayısını artırmak istiyoruz, ancak bunu senin gibi açık kaynak projelere katkıda bulunan kişilerin yardımı olmadan başaramayız!

O yüzden seninle birlikte çalışmak istiyoruz. Eğer OpenTR'nin aktivitelerine istersen, <https://opentr.netlify.app/contact/> adresinde yazılan iletişim seçeneklerinden birisi ile bize ulaşabilirsin.
