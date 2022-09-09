# Agoric SDK'nın Kurulması

Agoric Zoe çerçevesini kullanarak JavaScript akıllı sözleşmeleri yazmak için,
önce Agoric Software Development Kit'i (SDK) kurun.

## Hızlı başlangıç

"node", "yarn" ve "git" gibi JavaScript geliştirme araçlarına aşinaysanız:

```shell
node --version # 14.15.0 or higher
npm install --global yarn
git clone https://github.com/Agoric/agoric-sdk
cd agoric-sdk
yarn install
yarn build
yarn link-cli ~/bin/agoric
agoric --version
```

Ardından [bir proje başlatmaya](/getting-started/start-a-project.md) geçin.

Daha ayrıntılı bir açıklama aşağıdadır.

::: ipucu İzle: Agorik Ortamınızı Hazırlayın (Kasım 2020)
Bu sunum, Agoric SDK kurulum sürecine iyi bir genel bakış niteliğindedir, ancak birkaç ayrıntı güncelliğini yitirmiştir:
 - node version: 12.x is too old; use 14.15.0 or higher
 - skip `git checkout hackathon-2020-11`; use the default `master` branch

<iframe width="560" height="315" src="https://www.youtube.com/embed/w0By22jYhJA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::

## Platform: Linux kabuğu veya eşdeğeri

Agoric SDK üzerinde desteklenir
<a href="https://en.wikipedia.org/wiki/Linux">Linux</a>,
<a href="https://www.apple.com/macos/">MacOS</a> veya
<a href="https://docs.microsoft.com/en-us/windows/wsl/">Linux için Windows Alt Sistemi (WSL).</a>

 - Mac'lerde bir terminal açmak için **Finder**'da **Uygulamalar>Yardımcı Programlar>terminal** bölümüne bakın.
 - Windows 10'da belirli bir klasörde bir bash kabuğu başlatmak için:
   1. Dosya Gezgini'nde o klasöre gidin.
   2. Bu klasördeyken adres çubuğuna tıklayın.
   3. Adres çubuğuna <code>bash</code> yazın ve <b>Enter</b>'a basın


## Node.js 14.15.0 veya sonraki sürümünü yükleyin

[nodejs.org](https://nodejs.org/) adresinden indirin ve platformunuz için talimatları izleyin.


## Yarn paket yöneticisini kurun

[Yarn Kurulumu](https://classic.yarnpkg.com/en/docs/install) izleyin
Talimatlar; örneğin:

```shell
npm install --global yarn
```

## Agoric SDK'yı klonlayın

```shell
git clone https://github.com/Agoric/agoric-sdk
cd agoric-sdk
```

Mevcut bir klonu güncellemek için:

```shell
git pull
```

## NPM bağımlılıklarını yükleyin

```shell
yarn install
```

**Not:** Yükleme veya derleme sırasında hatalarla karşılaşırsanız, build-essential'ın kurulu olduğundan emin olun. "gcc --versiyon".

## Paketler oluşturun

```shell
yarn build
```

## Install `agoric` CLI
## 'agoric' CLI'yi kurun

'agoric' komut satırı arabirimini '$PATH' dosyanızda aşağıdaki gibi uygun bir yere kurun:

```shell
yarn link-cli ~/bin/agoric
```

or:

```shell
sudo yarn link-cli /usr/local/bin/agoric
```

To check that it's installed correctly:

```shell
agoric --version
```
