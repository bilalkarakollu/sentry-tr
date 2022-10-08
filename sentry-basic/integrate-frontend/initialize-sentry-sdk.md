<h1 align="center">Ön Uç Kodunuza Sentry SDK'yı Tanıtın</h1>

<p>Bu öğreticide, React demo kodunu yerel geliştirme ortamınıza aktarır, Sentry SDK'yı ekler ve onu başlatırsınız.</p>

<h4>1. Adım: Kodu alın</h4>

- GitHub'da "ön uç izleme"(frontend monitoring) örnek <a target="_blank" href="https://github.com/sentry-tutorials/frontend-monitoring">kod deposunu açın</a>.
- "Çatal"(Fork) ı tıklayın ve bu havuzun çatallanmasını istediğiniz hedef GitHub hesabını seçin.
  
<br>
<br>

<img src="https://docs.sentry.io/static/11c56ee9d7c2cafbafc617102ad0192d/912fc/initialize-sentry-sdk-01.png">

<br>
<br>

- <p>Çatal tamamlandığında, "Klonla veya indir"i tıklayın ve depo HTTPS URL'sini kopyalayın.</p>

<img src="https://docs.sentry.io/static/762a1fc772268f4fec2b9575db48c6ec/5a6dd/initialize-sentry-sdk-02.png">

<br>
<br>

```bash
> git clone <repository HTTPS url>
```

- Örnek kod artık yerel olarak mevcut olduğuna göre, tercih ettiğiniz kod düzenleyicide "ön uç izleme" projesini açın.

<br>
<br>
<h4>2. Adım: SDK'yı yükleyin</h4>

<p>Sentry, uygulama çalışma zamanınızda platforma özel bir SDK kullanarak verileri yakalar. SDK'yı kullanmak için, kaynak kodunuzda içe aktarın ve yapılandırın. Demo projesi React ve Browser JS kullanıyor. Başlamanın en hızlı yolu, JavaScript tarayıcı SDK'sının CDN'de barındırılan sürümünü kullanmaktır, ancak NPM, <a href="https://docs.sentry.io/platforms/javascript/install/npm/">tarayıcı SDK'sını</a> da yükleyebilirsiniz.</p>

1- "index.html" Dosyayı açın (altında bulunur _./frontend-monitoring/public/_).

<img src="https://docs.sentry.io/static/362ddf58c53519ebbda0b4c7591971cd/9c701/initialize-sentry-sdk-03.png">


>Kodumuzda SDK'yı mümkün olduğunca erken içe aktarıp başlattığımıza dikkat edin.

2- Sentry SDK yapılandırmasında, önceki adımlardaDSN oluşturduğunuz projeden kopyaladığınız anahtar değerini girin .


```js
Sentry.init({
  dsn: "<PASTE YOUR DSN KEY HERE>",
});
```

<h4>3. Adım: Demo uygulamasını yükleyin ve çalıştırın</h4>
<p>Demo uygulamasını yerel ana makinenizde oluşturmak ve çalıştırmak için:</p>

1- Bir kabuk terminali açın ve dizini frontend-monitoringproje klasörüne değiştirin.

2- .nvmrc Bu projeyle uyumlu Düğüm sürümünü ayarlamak için dosyayı kullanın . Koşmak:

```
> nvm use
```
3- Aşağıdakileri çalıştırarak proje bağımlılıklarını kurun:

```
> npm install
```
4- Aşağıdakileri çalıştırarak projeyi yerel ana makinenizde derleyin, dağıtın ve çalıştırın:

```
> npm run deploy
```

<img src="https://docs.sentry.io/static/1eb5f3cebf4e0d3bf4bf48af784b20cd/e4611/initialize-sentry-sdk-04.png">


<br>
<br>
<br>
<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/sentry-basic/integrate-frontend/generate-first-error"><strong>Sonraki Ders -></strong></a></div>
<br>
<br>
<br>