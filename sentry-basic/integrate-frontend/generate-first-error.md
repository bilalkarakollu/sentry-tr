<h1 align="center">İlk Hatanızı Yakalayın</h1>

Artık demo uygulaması, Sentry SDK ile entegre yerel ortamınızda çalıştığına ve çalıştığına göre, ilk hatayı oluşturmaya hazırsınız.

<h4>1. Adım: İlk etkinliğinizi kaydedin</h4>

1- Tarayıcınızda <a target="_blank" href="http://localhost:5000/">localhost bağlantısını</a> açarak demo uygulamasını başlatın .

2- Bir hatanın oluştuğunu doğrulamak için tarayıcının "Konsolunu"(Console) açın.


<img src="https://docs.sentry.io/static/a013059ec2a59dc3d12be82818f23eb3/43fbc/generate-first-error-02.png">

3- "Satın al!" (Buy!) Alışveriş sepetinize ürün eklemek için düğmeler.

4- Bir hata oluşturmak için sağ paneldeki "Ödeme" düğmesini tıklayın.

<img src="https://docs.sentry.io/static/6059335ffb1ace35dc31903043ead971/e04e6/generate-first-error-01.png">

<h5>Dikkat edin:</h5>

- Uygulamada "Bir şeyler ters gitti"(Something went wrong) hata mesajı görüntüleniyor.
- Hata tarayıcı konsolunda görünüyor.
- Sentry'de yapılandırılan e-posta adresinize, uygulamanızda meydana gelen bir hata hakkında sizi bilgilendiren bir uyarı gönderilir.

<br>
<br>

<img src="https://docs.sentry.io/static/00eac437ce9445dc1f119b4c6881362e/f5eb6/generate-first-error-03.png">

<br>
<br>

<h4>2. Adım: Hatayı ele alın</h4>

1- E-postanıza gidin ve Sentry'den gelen bildirimi açın.

<img src="https://docs.sentry.io/static/caea0d3f355656db338a4e0965d7d0a8/b94e3/generate-first-error-04.png">

<br>
<br>

2- Bu hatanın tüm ayrıntılarını ve içeriğini Sentry hesabınızda görüntülemek için "Sentry'de Görüntüle"yi tıklayın.

<img src="https://docs.sentry.io/static/55ed0d5a4e65491d924701898535b84b/9c2d2/generate-first-error-05.png">
<br>
<br>

>Sentry'nin benzer hataları (olayları) tek bir sorunda topladığını unutmayın .

3- Hesabınızda "İstisna"(Exception) yığın izlemesine gidin.

<br>
<br>
<img src="https://docs.sentry.io/static/c032d6f94d735575d657dcdda413c992/8b936/generate-first-error-06.png">

<br>
<br>

- Yığın izinin küçültüldüğüne dikkat edin . JavaScript genellikle kaynak kodun boyutunu küçültmek için küçültülür.
- Sentry, kodu okunabilir biçimine geri döndürebilir ve sonraki bölümde ele alınan her yığın çerçevesinde kaynak (kod) bağlam satırlarını görüntüleyebilir.


<br>
<br>
<br>
<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/sentry-basic/integrate-frontend/upload-source-maps"><strong>Sonraki Ders -></strong></a></div>
<br>
<br>
<br>





