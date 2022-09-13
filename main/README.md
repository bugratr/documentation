---
####
# YAML section setting up the home page
# run `yarn docs:dev` at any time to start local dev server and access
# website at localhost:8080 by default
####
home: true # use default home page layout (hero image with text, features section)
heroImage: https://agoric.com/wp-content/themes/agoric_2021_theme/assets/img/logo.svg
## Eylem düğmesi
actionText: Beta Dapps'i deneyin → düğmeye giren # metin
actionLink: /getting-started/beta.html # butona tıklandığında gidilecek bağlantı
özellikleri:
   - title: Yeni Protokol
     ayrıntılar: Agoric, bireyleri merkezi kontrol olmadan güvenli bir şekilde işlemleri yürütme, yeni pazarlar oluşturma ve yeni değişim kalıpları oluşturma konusunda güçlendirir.

   - title: OCAP'lerle daha iyi güvenlik mimarisi
     ayrıntılar: Agoric, bir programlama nesnesine erişimin, nesneyi kullanma yetkisi olduğu bir nesne kapasiteli (ocap) güvenlik mimarisi kullanır.

   - title: Güvenli Bir Şekilde Oluşturun ve Aktarın
     detaylar: Her türlü dijital varlık kolayca oluşturulabilir, ancak daha da önemlisi, tamamen aynı güvenlik özellikleriyle tamamen aynı şekillerde aktarılabilirler.

footer: Apache-2.0 Licensed | Copyright © 2022 - Agoric
---

<div class="flex flex--column flex--center">
  <p>
   JavaScript'te jetonları ve diğer dijital varlıkları aktarmanın tek tip bir yolu olan <a href="/getting-started/ertp-introduction.html">ERTP</a> hakkında bilgi edinin..
  </p>
  <Button-Action-Link
    text="Get Started with ERTP"
    link="/ertp/guide/"
  />
</div>
<br>
<div class="flex flex--column flex--center">
  <p>Daha fazlası için hazır mısınız? <a href="/getting-started/intro-zoe.html">Zoe</a>'ya göz atın. Zoe, "güvenlik teklifi" dediğimiz şeyi uygulamaktan sorumludur ve Zoe'nin üzerinde çalışan akıllı sözleşme, önerilen bir kaynakların yeniden tahsisini bulmaktan sorumludur.
  </p>
  <Button-Action-Link
    text="Build on Zoe"
    link="/zoe/guide/"
  />
</div>

## Platform

30 yıllık deneyime dayanan Agoric, akıllı sözleşmeler ve pazar odaklı programlama için güvenli bir dağıtılmış ocap platformu geliştiriyor. Platformumuz, büyük kamu blok zincirlerinden küçük iki taraflı sözleşmelere kadar birçok farklı ölçekte akıllı sözleşmelerin ve piyasa kurumlarının geliştirilmesini destekler.

Ocap platformumuz şunlardan oluşur:

- Güvenli akıllı sözleşmeler oluşturmak için sağlam bir mimari.
- Maksimum erişim için JavaScript'te bir temel.
- Zincirler arası birlikte çalışabilirlik için bir kriptografik yönlendirme yapısı.
- Piyasa soyutlamalarından oluşan bir kitaplık ve bunları güvenli bir şekilde oluşturmak için bir çerçeve.
- Güvenli kullanıcı etkileşimi için bir çerçeve.

## Başlarken

[Belgeleme Kılavuzumuz](/getting-started/) belgelerimizi açıklar ve Agoric platformuna başlamak için bir sipariş önerir.
