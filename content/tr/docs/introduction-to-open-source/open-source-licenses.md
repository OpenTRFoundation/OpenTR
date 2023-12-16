---
title: "Açık Kaynak Lisansları"
linkTitle: "Açık Kaynak Lisansları"
description: Bu belgede, genel olarak lisans kavramını ve açık kaynak lisanslarının ne olduğunu okuyabilirsiniz.
weight: 50
---

Açık kaynak yazılımın en temel taşlarından biri lisanslardır. Bir yazılımın lisansı, kullanıcılarına ne tür haklar tanıdığını ve hangi koşullar altında kullanılabileceğini belirler.

## Lisans tanımı

Açık kaynak lisansları, yazılımın özgürce kullanılmasını, dağıtılmasını, değiştirilmesini ve geliştirilmesini sağlar, ancak bu özgürlükler genellikle belirli şartlara bağlıdır. Açık kaynak lisansın tanımının çeşitli şekilleri olmaklar birlikte, [Open Source Initiative](https://opensource.org/)’in (OSI) [tanımı](https://opensource.org/osd/) genellikle endüstride kullanılan tanımdır. Özeti ise, bir lisansın açık kaynak lisansı olabilmesi için, sadece kaynak koda erişime izin vermesi değil, yeniden dağıtım gibi konulara da izin vermesi gerekmektedir.

## Lisans türleri

OSI, [websitesinde](https://opensource.org/licenses/) onayladığı lisansları listelemektedir. Bunlar arasında oldukça bilindik lisanlarla birlikte, bazı az bilinen lisanslar da bulunmaktadır.

Açık kaynak yazılım lisansları, genellikle iki ana kategori altında toplanır: [permissif](https://en.wikipedia.org/wiki/Permissive_software_license) (izin verici) lisanslar ve [kısıtlayıcı](https://en.wikipedia.org/wiki/Copyleft) (copyleft) lisanslar. İzin verici lisanslar, yazılımın özgürce kullanılmasına ve diğer projelerle entegrasyonuna daha fazla esneklik tanırken, kısıtlayıcı lisanslar daha katı kurallara tabidir ve türetilmiş yazılımın aynı özgür özelliklere sahip olmasını gerektirebilir.

Bazı bilindik açık kaynak lisansları şunlardır:
* GNU Genel Kamu Lisansı (GPL): Yazılımın özgürce kullanılmasına izin verir, ancak türetilmiş çalışmaların da GPL altında lisanslanmasını zorunlu kılar.
* MIT Lisansı: Yazılımın özgürce kullanılmasına ve değiştirilmesine izin veren permissif bir lisans.
* Apache Lisansı: Kapsamlı bir permissif lisans olan Apache, özgür kullanımı destekler ve aynı zamanda patent ihlali durumunda bir koruma mekanizması sunar.

Bunlara ek olarak, bazı açık kaynak projeler, ticari ve kapalı kaynaklı kullanım için özel lisanslar sunar. Bu, şirketlere açık kaynak kodu kullanma özgürlüğü verirken, aynı zamanda ticari ürünlerini kapalı kaynaklı tutma olanağı tanır. Bu yaklaşım, açık kaynak projelerin sürdürülebilir finansman modeli olarak görülebilir.

Projeler zamanla geliştikçe, lisans gereksinimleri veya topluluk dinamikleri değişebilir. Bu durumda, projeler lisanslarını güncelleyebilir veya değiştirebilirler. Lisans değişiklikleri ve diğer önemli kararlar genellikle topluluk katılımını gerektirir.

## Lisans seçimi ve etkileri

Proje liderleri ve katılımcılar, açık kaynak yazılım geliştirirken uygun lisansı seçmek zorundadır. Bu seçim, projenin hedeflerine, topluluğun dinamiklerine ve katkıda bulunanların beklentilerine göre şekillenir. Ayrıca, lisans seçimi, ticari kullanım, patent hükümleri ve diğer faktörleri de içerebilir.

Lisanslar, yazılımın nasıl kullanılabileceğini ve dağıtabileceğini belirler. Permissif lisanslar geniş bir kullanım serbestisi tanırken, kısıtlayıcı lisanslar belirli koşullara bağlı kullanımı gerektirebilir. Bazı lisanslar, türetilmiş çalışmaların da aynı lisans altında paylaşılmasını şart koşar.

Lisanslar, aynı zamanda kullanıcıların yazılımı nasıl değiştirebileceğini belirler. Açık kaynak lisansları genellikle değişiklik yapma özgürlüğü tanır, ancak bu değişikliklerin nasıl paylaşılacağına dair kurallar içerir.

Lisanslar belirli kurallara tabi olduğundan, lisans ihlalleri ciddi sonuçlar doğurabilir. Projeler, lisanslarını doğru bir şekilde uygulamak ve izlemek zorundadır. Aynı zamanda projeler kullandıklari diğer projelerinin de lisanlarının şartlarına uymak zorundadır. Aksi takdirde, hukuki sorunlar ortaya çıkabilir ve projenin sürdürülebilirliği riske girebilir.

Açık kaynak projeler genellikle dünya genelinde katılımcılara sahiptir, bu nedenle lisanslar küresel olarak anlaşılır ve uygulanabilir olmalıdır. Proje liderleri, farklı kültürlerden gelen katılımcıları düşünerek lisans kararlarını yapmalıdır.

## Açık Kaynak olmayan varyasyonlar

Endüstride çoğunlukla OSI’ın [açık kaynak lisans tanımı](https://opensource.org/osd/) kullanılsa da, bazen farklı lisans türleri hata ile veya kasten açık kaynak olarak sunulmaktadır.

**Shared Source Model**: Kaynak kodu belirli koşullar altında belirli kişilere açık olan bir model. Ancak, özgürce değiştirilmesine ve paylaşılmasına izin vermez.

Bu lisanslara örnek olarak Hashicorp’un [Business Source License](https://thenewstack.io/hashicorp-abandons-open-source-for-business-source-license/) lisansı ve Facebook’un [Llama 2 Community License](https://www.theregister.com/2023/07/21/llama_is_not_open_source/) lisansı verilebilir. Bunlar açık kaynak olarak lanse edilse de, aslında dağıtım ve değişim yapmak isteyenlere kısıtlamalar getiren lisanlardır.

> _Açık kaynak kavramı, Open Source Initiative'ın resmi Açık Kaynak Tanımı'nda kodlanmış olarak, "sadece kaynak koda erişim anlamına gelmez." Bunun yanı sıra, "açık kaynak" olmak, kullanıcıların kaynak kodunu kendi ihtiyaçlarına göre düzenleyip değiştirmelerine ve bu kodu herhangi bir telif hakkını ihlal etmeden üretime sokmalarına olanak tanıma anlamına gelir._
>
> – "HashiCorp’s Licensing Change is only the Latest Challenge to Open Source"
>
>– [The New Stack](https://thenewstack.io/hashicorp-abandons-open-source-for-business-source-license/)

**Freeware**: Ücretsiz olarak kullanılabilen yazılım, ancak kaynak kodu genellikle kamuya açık değildir ve değiştirilemez.

**Proprietary Software with Source Access**: Şirketler, kaynak kodunu belirli müşterilere açar, ancak genel olarak kamuya açık değildir.
