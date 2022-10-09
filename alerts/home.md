<h1 align="center">Alerts</h1>

<p>Uyarılar, kodunuzla ilgili sorunlara ve kullanıcılarınız üzerindeki etkisine ilişkin gerçek zamanlı görünürlük sağlar. Özelleştirilebilir eşikler ve entegrasyonlarla kullanılabilen çeşitli uyarı türleri vardır.</p>

<p>sentry.io'daki Uyarılar sayfasından yeni uyarı kuralları oluşturabilir ve mevcut olanları yönetebilirsiniz . "Uyarı Kuralları" sekmesi, mevcut uyarı kurallarınızı, mevcut durumları, proje, ekip ve oluşturma tarihi ile birlikte görüntüler. Varsayılan olarak liste, yalnızca üyesi olduğunuz ekiplerle ilişkili uyarıların yanı sıra herhangi bir ekiple ilişkili olmayan uyarıların görüntüleneceği şekilde filtrelenir. Filtre düğmesini kullanarak bunu değiştirebilirsiniz.</p>

<img src="https://docs.sentry.io/static/fe206672947487b119939ca4cd59da64/97a96/alert-listing.png">

<p>Uyarılar sayfası ayrıca , ne zaman tetiklendiği ve ne kadar süreyle etkin olduğu gibi bilgilerle birlikte ölçüm uyarılarının bir listesini bulabileceğiniz bir "Geçmiş" sekmesi görüntüler.</p>

<h4>Hatalar için Uyarı Verme</h4>

<p>Sorun uyarıları, bir projedeki herhangi bir sorun belirtilen kriterlerle eşleştiğinde tetiklenir. Sorun düzeyindeki değişiklikler için aşağıdakiler gibi uyarılar oluşturabilirsiniz:</p>

- Yeni sorunlar
- Sorun sıklığı artıyor
- Çözülen ve göz ardı edilen sorunlar çözülemiyor

<h4>Hatalar ve Performans için Metrik Uyarıları</h4>

<p>Metrik uyarıları , hata veya işlem olayları için bir metrik ihlal edildiğinde tetiklenir . Tüm projenizdeki, önemli sayfalardaki veya belirli etiketlerdeki hata sıklığı veya performans ölçümleri gibi önemsediğiniz sınırlı ve bilinen bir ölçüm ve bileşen kümesini izlemek için ölçüm uyarılarını kullanın.</p>

<p>Metrikleri izlemek için uyarılar oluşturun, örneğin:</p>

- Projenizdeki toplam hata
- Gecikme(Latency): min, maks, ortalama, yüzdelik dilim
- Başarısızlık oranı (Failure rate)
- Sürüm durumunu izlemek için kilitlenmesiz oturum veya kullanıcı oranı (Crash free session or user rate for monitoring release health)
- Özel metrikler (Custom metrics)

<h4>Uyarı Oluşturma</h4>

<p>sentry.io'da yeni bir proje oluşturduğunuzda, varsayılan bir sorun uyarısı seçebilirsiniz. Ancak, bu en iyi uygulamaları kılavuz olarak kullanarak ekibinizin ihtiyaçlarına uygun <a href="https://docs.sentry.io/product/alerts/create-alerts/">kendi uyarılarınızı</a> da oluşturabilirsiniz.</p>

<h4>Bildirimler</h4>

<p>Uyarıların yanı sıra, Sentry size sorun durumu değişiklikleri, sürüm dağıtımları ve kota kullanımı gibi çeşitli şeyler hakkında bildirimler gönderir. Bu bildirimlerin yanı sıra kişisel uyarı ayarlarınızda <strong>Kullanıcı Ayarları > Bildirimler</strong>'de ince ayar yapabilirsiniz . Belgelerin tamamında bildirimler ve bunlarla ilişkili ayarları düzenleme hakkında daha fazla bilgi edinin.</p>

<h4>Daha fazla bilgi edin</h4>

- <h5><a>Uyarı Türleri</a></h5>
  <p>Sentry'nin sağladığı iki uyarı türü hakkında bilgi edinin: sorun uyarıları ve ölçüm uyarıları.</p>

- <h5><a>Uyarı Oluştur</a></h5>
  <p>Uygulamanızdaki hatalar ve performans sorunları hakkında sizi bilgilendiren uyarıları nasıl oluşturacağınızı öğrenin.</p>

- <h5><a>Uyarılar En İyi Uygulamaları</a></h5>
  <p>Uyarı oluşturmaya yönelik en iyi uygulamaları öğrenin.</p>

- <h5><a>Bildirimler</a></h5>
  <p>Sentry'nin size gönderdiği bildirim türleri ve bunların nasıl yönetileceği hakkında bilgi edinin.</p>


<br>
<br>
<br>
<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/sentry-basic/alerts/alert-types"><strong>Sonraki Ders -></strong></a></div>

<br>
<br>
<br>