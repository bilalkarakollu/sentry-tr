<h1 align="center">Data Source Name (DSN)</h1>

<p>
Sentry, uygulamanızdaki olayları izlemeye başlamak için bir proje oluşturduğunuzda size otomatik olarak bir Veri Kaynağı Adı (DSN) atar.
</p>

<br>
<h5>DSN'nin Yaptıkları</h5>
<p>Bir DSN, olayların doğru projeyle ilişkilendirilmesi için bir Sentry SDK'ya olayların nereye gönderileceğini söyler.</p>

<p>Bu değer sağlanmazsa, SDK'lar, SENTRY_DSN uygun olduğunda, ortam değişkeninden okumaya çalışır. Bu geri dönüş, ortam değişkenleri kavramının olmadığı bir web tarayıcısı gibi durumlarda geçerli değildir.</p>

<p>Bir SDK başlatılmazsa veya boş bir DSN ile başlatılırsa, SDK, yakalanan istisnalar gibi ağ üzerinden herhangi bir veri göndermez.</p>
<br>

<h5>DSN Kullanımı</h5>

<p>DSN'leri herkese açık tutmak güvenlidir çünkü yalnızca yeni olayların ve ilgili olay verilerinin sunulmasına izin verirler; herhangi bir bilgiye okuma erişimine izin vermezler.</p>

<p>Herhangi bir kullanıcının kuruluşunuza istedikleri herhangi bir bilgiyle olay gönderebildiği bir DSN'yi kötüye kullanma riski olsa da, bu nadir görülen bir durumdur. Sentry, IP'leri ve benzer endişeleri engellemek için kontroller sağlar . <strong>[Proje] > Ayarlar > İstemci Anahtarları (DSN)</strong> seçeneğine giderek DSN'leri de döndürebilir (ve iptal edebilirsiniz ) .</p>

<p>
Uygulamanız istemci cihazlara gönderiliyorsa, mümkünse DSN'yi dinamik olarak yapılandırmanın bir yolunun olmasını öneririz. İdeal bir senaryoda, müşteri en son sürümü indirmeden uygulamanıza yeni bir DSN "gönderebilirsiniz". Bunun her zaman pratik olmayabileceğinin farkındayız, ancak bu senaryo uygulamaya özel olduğu için daha fazla tavsiye sunamıyoruz.
</p>
<br>
<h5>DSN'nizi Nerede Bulabilirsiniz?</h5>

<p>Bir proje oluşturma sürecindeyseniz, DSN'nizi kurulum sırasında sentry.io'da sağlanan kurulum veya yapılandırma kod parçacıklarında bulabilirsiniz :</p>

<img src="https://docs.sentry.io/static/f72cab45b796b9e61843e51b8fc07abf/2cefc/create-new-project-04.png"/>

<br>
<br>

<p>DSN'yi , sentry.io'da <strong>[Proje] > Ayarlar > İstemci Anahtarları (DSN)</strong> seçeneğine giderek proje ayarlarınızda da bulabilirsiniz </p>

<br>
<br>
<br>
<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/sentry-basic/environments"><strong>Sonraki Ders -></strong></a></div>
<br>
<br>
<br>