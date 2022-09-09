# Agorik Beta
Yayın Sürümü: Baltık

![Agoric Banner](./assets/agoric-banner-2.png)

Agorik Beta'nın 1. Aşamasına hoş geldiniz!

Bu dokümantasyon sitesi Agorik sistem hakkında ayrıntılı bilgi vermektedir. Beta için herkesin etkileşime girerek başlamasını öneririz.
bir kullanıcı olarak dağıtılan uygulama ile. Oynamak için bazı sahte varlıklar da dahil olmak üzere cüzdanınızı kurarak başlayacaksınız.

## Bir Cüzdan Kurma (Agorik Solo Makinesi) ##

Diğer blok zincirlerinden farklı olarak, Agoric "cüzdanınız" aslında bazı ek durumları koruyan solo bir makinedir (işlem).
hesabınız hakkında. Şimdilik bunun için bazı işlemleri yerel olarak çalıştırmanız gerekiyor. Cüzdanınızı kurmayla ilgili talimatlar için:

[Agoric Wallet Set-up Guide (Docker)](https://github.com/Agoric/agoric-sdk/wiki/Setting-up-an-Agoric-Dapp-Client-with-docker-compose)

[Agoric Wallet Set-up Video Walkthrough](https://www.youtube.com/watch?v=e5LQx0EqR0o)

Endişelenme, bu yakında çok daha kolay olacak. İncelemeleri geçtikten sonra, cüzdan indirilebilir bir uygulama aracılığıyla kullanıma sunulacak. Ana ağ lansmanında Agoric, basit bir eklenti aracılığıyla önde gelen cüzdan sağlayıcılarıyla entegre edilecek.

## Vault Uygulamasına gidin ##

Cüzdanınızı önceden stokladığımız sahte varlıklarla işlem yapın.

[Vault Uygulaması](https://treasury.agoric.app)

## Bir Şeyler İnşa Etmeye Başlayın ##

[Kodlamaya Başlayın](/getting-started/), başlamak için belgelerimizin nasıl kullanılacağına ilişkin bir açıklama ile.

[Discord Topluluğumuza Katılın](https://agoric.com/discord) ve bizimle ve diğer geliştiricilerle sohbet edin.

## Beta'da Neler İnşa Edebilirsiniz?

<div class="two-col-table">

| Değiştirilebilir ve değiştirilemez belirteçler | Atom takası |
| ------ | ----------- |
| <div style="text-align: center">![Non Fungible Token](./assets/nft-small.png) </div> <br>Sözleşmelerinizle takas edilebilir veya takas edilemez dijital varlıklar oluşturun ve kullanın . | <div style="text-align: center">![Atomic Swap](./assets/atomicswap.png) </div> <br>Merkezi aracılar kullanmadan bir kripto para biriminin başka bir kripto para birimiyle değişimini etkinleştirin. |

| Gizli çağrı | Basit değişim |
| ------ | ----------- |
| <div style="text-align: center">![Covered Call](./assets/covered-call-small.png) </div> <br>Sahibinin belirli bir satın alma işlemi gerçekleştirmesini sağlayan bir opsiyon sözleşmesi oluşturun, önceden emanet edilmiş, önceden belirlenmiş bir kullanım fiyatında (son kullanma tarihinden önce) varlık. | <div style="text-align: center">![Basit Değişim](./assets/simple-exchange-small.png) </div> <br>Fiyatlandırılmış bir varlık için sipariş defteri içeren temel bir değişim ikinci bir varlık. |

| Otomatik piyasa yapıcı |
| ------ |
| <div style="text-align: center">![Otomatik Piyasa Yapıcı](./assets/amm-small.png) </div> <br>Zincir üzerinde otomatik DEX işlevi gören bir akıllı sözleşme oluşturun: likidite. |

</div>

## Akıllı Sözleşme Kodu Örneği: Çağrı Seçeneği

Örnek olarak, *kapsamlı arama seçeneği*, dijital varlıkları *kullanım fiyatı* olarak adlandırılan önceden belirlenmiş bir fiyattan satın alma hakkıdır (zorunluluk yoktur). Bu arama seçeneği *kapsanır*, yani sahibinin arama seçeneği için dijital varlıkları emanet ettiği anlamına gelir. *Emanet*, bir varlığın sahibinin sözünü tutmasına güvenmeden varlıkların taraflar arasında devredilebileceğini garanti eder. Fırsat iptal edildiğinde, arama seçeneğinin bir *son kullanma tarihi* vardır.
Dijital varlık sahibi, varlıkları son kullanma tarihinden önce emanetten çıkaramaz.

Kapsamlı bir çağrı teklifi şuna benzer:

```js
const proposal = {
    give: { StrikePrice: moola(25) },
    want: { Asset: concertTicket("E4") },
    exit: { afterDeadline: { deadline: time, timer: myTimer } },
};
```

*Son tarih* opsiyonun sona erme tarihidir. Yukarıdaki kod, opsiyonun son tarihe kadar kullanılmaması durumunda, dayanak varlıklarının sözleşmenin yaratıcısına emanet edilen varlıklarının iadesi olarak ödeneceğini belirtir.

## Geliştirici Deneyimi
Agoric bir mühendis ekibidir. Geliştirici deneyimimizi onlarca yıllık açık kaynaklı yazılım deneyimimize dayandırdık. Betamızda aşağıdakileri bekleyebilirsiniz:

* Hata ayıklama destekli VS Kodu
* Yerel olarak oluşturma ve test etme yeteneği
* Yerel gelişiminizi hızlandırmak için dahil edilen türler
* Ava test altyapısı ile hızlı test iterasyonu

### Başlamaya hazır mısın?
[Kodlamayı Başlat](/getting-started/)

### Bir şeye mi takıldınız?
Mühendislerimizle [Agoric Discord](https://agoric.com/discord) üzerinden sohbet edin.

### Bizimle sosyal ağlarda bağlantı kurmak ister misiniz?
Bizi [Twitter](https://twitter.com/agoric), [Telegram](https://t.me/agoricsystems) ve [LinkedIn](https://www.linkedin.com/company/agoric) üzerinden takip edin /).
