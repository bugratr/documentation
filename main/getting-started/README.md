# Agorik Dokümantasyon Kılavuzu

::: ipucu Beta durumu
Agoric platformu beta aşamasındadır. Güvenlik açıkları için resmi olarak değerlendirilme sürecinde ve ana ağ-1 lansmanını desteklemek için güvenlik tedavisi ve sertleştirme sürecinden geçiyor. Üretim amaçlı kullanmayınız.
:::

Agoric, üç ana belge türü ve ayrıca aşağıdakilere bağlantılar sağlar:
"büyük resim" sunumları, makaleler ve GitHub'daki kaynak kodumuza bağlantılar. Bu sayfa, belgelerin nerede olduğunu ve bunları ne zaman kullanmanız gerektiğini ve ayrıca bunları hangi sırayla okumanız gerektiğini belgeleme yapımızı açıklar.

Üç ana belge tipimiz şunlardır:
- **Başlarken**: Bunlar, okumanız gereken ilk şeylerdir. Agoric'in akıllı sözleşme araçlarını kurmak, kurmak ve kullanmaya başlamak için ne yapılması gerektiğini kapsarlar. Ayrıca bu araçları ve bunların temel kavramlarını ve tasarımlarını tanıtırlar.
- **Kılavuzlar**: Bunlar daha ayrıntılı ve eksiksiz açıklamalardır
araçlarımız ve konseptleri, tasarımları ve kullanımları. Onlar içerir
Agoric ile çeşitli görevlerin nasıl yapılacağına dair açıklamalar ve örnekler
yazılım.
- **Referans**: Bunlar, API'lerimizin ve komutlarımızın özellikleridir,
  belirten ve açıklayan kontrol listesi tablolarının yanı sıra
  Agoric kurulumu gibi genişletilmiş prosedürler için adımlar
  yazılım.

Bazı belgeler birden fazla kategoriye ayrılır. Örneğin, Agoric kurulum belgemiz hem Referans hem de Başlangıç ​​belgesidir.

Bunları şu sırayla okumalısınız:
1. **[Agoric SDK'yı Kullanmadan Önce](./before-using-agoric.md)**:
Agoric SDK'nın bağlı olduğu yazılım nasıl kurulur.
2. **[Bir Proje Başlatın](./start-a-project.md)**: A
  sıfırdan yeni bir Agoric SDK projesi oluştururken size yol gösteren prosedür kontrol listesi.
3. **[ERTP Tanıtımı](./ertp-introduction.md)**:
 Agoric yazılımının kalbi olan Agoric'in Elektronik Hak Transfer Protokolü'nün (ERTP) kavramlarını ve bileşenlerini kısaca açıklayan bir Başlarken belgesi.
4. **[Zoe Girişi](./intro-zoe.md)**:
JavaScript'te başka akıllı sözleşmeler yazmak için yeniden kullanılabilir akıllı sözleşmemiz olan Zoe'nin kavramlarını ve bileşenlerini kısaca açıklayan bir Başlarken belgesi. Zoe, kullanıcıların ya sözleşmeden istediklerini almaları ya da bunun için koyduklarının tam bir geri ödemesini garanti etmemizi sağlar.
5. **[Agorik Platform/Yığın](/platform/README.md)**: Tam Agorik platform/teknik yığına kısa bir giriş.
6. **[Agorik Dapp Kılavuzu](/dapps/README.md)**:
 Dapp, tipik olarak tarayıcı tabanlı bir kullanıcı arayüzü, genel bir API sunucusu ve Agoric blok zincirinde çalışan bir sözleşme ile merkezi olmayan bir uygulamadır. Bu belge, bir Dapp'in temel dizini ve dosya yapısını açıklar.
7. **[Akıllı Sözleşmeleri Dağıtma](./deploying.md)**:
Sözleşmeleri zincire ve uygulama kodunu uygulama sunucusuna dağıtmaya yönelik araçların ve süreçlerin kısa bir açıklaması.
8. **[JavaScript Dağıtılmış Programlama Kılavuzu](/guides/js-programming/)**:
 Kavramlar, sözdizimi ve Agoric kitaplığına eklemeler dahil olmak üzere çeşitli katmanlarda Agoric'e özgü bazı eklemeler yaptık. Agoric platformunda programlama yapmadan önce bunları bilmeli ve anlamalısınız.
8. **[ERTP Kılavuzu](/ertp/guide/README.md)**:
 ERTP kavramlarının, tasarımının, bileşenlerinin ve komutlarının ayrıntılı bir açıklaması. Komut kullanım örnekleri içerir. Ayrıca ERTP belgeleri kenar çubuğu menüsünden erişilebilen ERTP API belgelerine de bakmalısınız.
9. **[Zoe Rehberi](/zoe/guide/README.md)**:
  Zoe kavramlarının, tasarımının, bileşenlerinin ve komutlarının ayrıntılı bir açıklaması.
  Komut kullanım örnekleri içerir. Ayrıca, Zoe belgeleri kenar çubuğu menüsünden erişilebilen Zoe API belgelerine de bakmalısınız.

Gerektiğinde **[ERTP API Referansı](/ertp/api/)**, **[Zoe API Referansı](/zoe/api/)**, **[Cüzdan Kılavuzu ve API Referansı]( /guides/wallet)** ve ilgili komutlarla ilgili ayrıntılar için **[Agoric CLI Guide](/guides/agoric-cli/)**. Cüzdan Kılavuzu ayrıca Cüzdan Kullanıcı Arayüzü ve Agoric Cüzdan ile genel çalışmayı da kapsar.

Bir REPL'ye (Okuma-Değerlendirme-Baskı Döngüsü) erişebilirsiniz. Geliştiriciler, REPL'den ve onun "home" nesnesinden, dağıtım komut dosyalarının sözleşmeleri ve Dapp'leri dağıtmak için kullandığı tüm zincir üstü komutları kullanabilir. Ayrıntılar için **[REPL Kılavuzu](/repl/)**'ye bakın.

Agoric'in Dinamik IBC'sini ([Blok Zincirler Arası İletişim Protokolü](https://cosmos.network/ibc)) yani dIBC'yi kullanıyorsunuz,
diğer blok zincirlerindeki hizmetlere bağlanmak veya Agorik blok zincirindeki hizmetleri diğer blok zincirlerine sunmak için.
Daha fazla bilgi için **[dIBC Kılavuzumuza](https://github.com/Agoric/agoric-sdk/blob/HEAD/packages/SwingSet/docs/networking.md)** bakın.

Çalışan Agoric akıllı sözleşmeleri hakkında bilgi edinmek için **[Örnek Sözleşmelere](/zoe/guide/contracts/README.md)** göz atın.

Ayrıca Agorik-bağlam verdiğimiz terimler için bir **[Agorik Sözlük](/sözlük/)** var
tanımlar (yani *nane* Agorik bağlamda ne anlama gelir?).

Agoric'in fikirleri, planları ve hedefleri hakkında daha fazla bilgi için **[Ana Sayfamıza](https://agoric.com/) bakın**.


**[Bildiriler](https://agoric.com/papers/)** sayfamızda Agoric'in teknik geçmişini ve fikirler.

Agoric'in **[YouTube kanalında](https://www.youtube.com/channel/UCpY91oQLh_Lp0mitdZ5bYWg)** Agoric mühendisleri ve yönetimi tarafından eğiticiler, şirket aramaları ve diğer konuşmalar bulunur.

Son olarak, nihai belgelere bağlantılarımız var; **[GitHub
Agoric SDK'yı tanımlayan kod için depolar](https://github.com/Agoric/)**.

