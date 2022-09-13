---
####
# YAML section setting up the home page
# run `yarn docs:dev` at any time to start local dev server and access
# website at localhost:8080 by default
####
home: true # use default home page layout (hero image with text, features section)
heroImage: https://agoric.com/wp-content/themes/agoric_2021_theme/assets/img/logo.svg
## Action button
actionText: Try Beta Dapps → # text that goes in the button
actionLink: /getting-started/beta.html # go-to link when clicking on button
features:
  - title: New Protocol
    details: Agoric empowers individuals to securely execute transactions, establish new markets, and craft novel patterns of exchange — without centralized control.

  - title: Better security architecture with OCAPs
    details: Agoric uses an object-capability (ocap) security architecture, in which access to a programming object itself is the authority to use the object.

  - title: Securely Create and Transfer
    details: All kinds of digital assets can be easily created, but importantly, they can be transferred in exactly the same ways, with exactly the same security properties.

footer: Apache-2.0 Licensed | Copyright © 2022 - Agoric
---

<div class="flex flex--column flex--center">
  <p>
    Learn about <a href="/getting-started/ertp-introduction.html">ERTP</a>, a uniform way of transferring tokens and other digital assets in JavaScript.
  </p>
  <Button-Action-Link
    text="Get Started with ERTP"
    link="/ertp/guide/"
  />
</div>
<br>
<div class="flex flex--column flex--center">
  <p>Ready for more? Check out <a href="/getting-started/intro-zoe.html">Zoe</a>. Zoe is responsible for enforcing what we call "offer safety", and the smart contract that runs on top of Zoe is responsible for figuring out a proposed reallocation of resources.
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
