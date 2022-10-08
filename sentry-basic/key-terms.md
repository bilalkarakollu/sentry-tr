<h1>Key Terms</h1>

<p>Bu sayfada tanımlanan temel terimler ve kavramlar Sentry'nin temelleridir. Belgelerimizde karşılaştığınız yeni terimleri tanımlarken, buradaki temel kavramları ve özellikleri anlamak, ürün hakkında daha karmaşık fikirleri öğrenmeyi kolaylaştıracaktır.</p>

<p>Bu liste, her tanım bir öncekini temel alacak şekilde sıralanmıştır.</p>

<h2>Anahtar kavramlar</h2>

- <h5>Sentry SDKs</h5>
  <p>
  Sentry'nin uygulama izleme için programlama diline/çerçeveye özel kitaplıkları. Uygulamanıza SDK'larımızdan birini eklediğinizde, uygulamanızdaki olay verileri yakalanır ve Sentry'ye gönderilir, böylece size hata ve performans raporları sağlayabiliriz.
  </p>
- <h5>sentry.io</h5>
  <p>
  Sentry'nin kullanıcı arayüzü Hizmet Olarak Sunulan YazılımlarSentry'nin bulut tabanlı, hizmet olarak yazılım çözümü.SDK'mız tarafından yakalanan olay verilerinin görselleştirildiği müşteriler. (Kendi kendine barındırılan kullanıcılar için, kullanıcı arabirimi şirketinizin dahili etki alanındadır.)
  </p>
- <h5>event</h5>
  <p>Bir hata veya işlem.</p>
- <h5>error</h5>
  <p>
  Neyin hata olarak sayılacağı platforma göre değişir, ancak genel olarak istisna gibi görünen bir şey varsa, Sentry'de hata olarak yakalanabilir. Sentry, platforma bağlı olarak diğer hata türlerinin yanı sıra hataları, yakalanmayan istisnaları ve işlenmeyen reddetmeleri otomatik olarak yakalar.
  </p>
- <h5>attachments</h5>
  <p>
   Bir hata olayına eklenen yapılandırma veya günlük dosyaları gibi depolanan ek dosyalar.
  </p>
- <h5>issues</h5>
  <p>
  Sorun, benzer hata olaylarının gruplandırılmasıdır. Her hata olayı, kendi adı verilen bir dizi özelliğe sahiptir. parmak iziBir olayı tanımlayan özellikler kümesi., Sentry bunları gruplamak için kullanır. Örneğin, Sentry, kodunuzun aynı bölümü tarafından tetiklendiğinde olayları birlikte gruplandırır. Olayların sorunlara göre gruplandırılması, bir sorunun ne sıklıkla meydana geldiğini ve kaç kullanıcıyı etkilediğini görmenizi sağlar.
  </p>
- <h5>transaction</h5>
  <p>
  İşlem, sayfa yükleme, sayfa gezinme veya eşzamansız görev gibi ölçmek veya izlemek istediğiniz bir işlemi desteklemek için çağrılan hizmetin tek bir örneğini temsil eder. İşlem olayları, işlem adına göre gruplandırılır.
  </p>
- <h5>data</h5>
  <p>
  Sentry'ye gönderdiğiniz her şey. Buna olaylar (hatalar veya işlemler), ekler ve olay meta verileri dahildir.
  </p>
- <h5>project</h5>
  <p>
  Bir proje, hizmetinizi veya uygulamanızı Sentry'de temsil eder. Uygulamanızda kullanılan belirli bir dil veya çerçeve için proje oluşturabilirsiniz. Örneğin, API sunucunuz ve ön uç istemciniz için ayrı projeleriniz olabilir. Daha fazla bilgi için proje oluşturmaya yönelik en iyi uygulamalarımıza göz atın . Projeler, olayları kuruluşunuzdaki farklı bir uygulamayla ilişkilendirmenize ve kuruluşunuzdaki belirli kullanıcılara ve ekiplere sorumluluk ve sahiplik atamanıza olanak tanır.
  </p>
- <h5>DSN</h5>
  <p>
  Veri Kaynağı Adı. Bir DSN, Sentry SDK'ya olayların nereye gönderileceğini söyler, böylece olaylar doğru projeyle ilişkilendirilir. Sentry, bir proje oluşturduğunuzda size otomatik olarak bir DSN atar. Tam DSN belgelerimizde daha fazla bilgi edinin .
  </p>
- <h5>team</h5>
  <p>
   Ekipler, Sentry projelerinizle ilişkilendirilir ve üyeleri, sorun sahibi olmanın yanı sıra sorun bildirimleri alır. Ekip kurma hakkında daha fazla bilgi edinin .
  </p>
- <h5>environment</h5>
  <p>
  geliştirme, test etme , hazırlama veya üretimenvironment gibi kod dağıtımlarınızın adlandırma kurallarına başvurmayı amaçlayan, SDK'nıza ekleyebileceğiniz, Sentry tarafından desteklenen bir etikettir . Ortamlar, diğer kullanımlar arasında sorunları ve işlemleri daha iyi filtrelemenize yardımcı olur. Tam Ortam belgelerimizde daha fazla bilgi edinin .
  </p>
- <h5>release</h5>
  <p>
  Sürüm, kodunuzun bir ortama dağıtılan bir sürümüdür. Sentry'yi bir sürüm hakkında bilgilendirdiğinizde, onunla ilişkili yeni sorunları ve gerilemeleri belirleyebilir, bir sonraki sürümde bir sorunun çözülüp çözülmediğini onaylayabilir ve kaynak haritaları uygulayabilirsiniz. Tam Sürüm belgelerinde daha fazla bilgi edinin .
  </p>
- <h5>release health</h5>
  <p>
  Yayın sağlığı verileri, kullanıcı deneyiminizle ilgili olduğu ve her yeni sorunla ilgili eğilimleri ortaya koyduğu için, kilitlenmelerin ve hataların etkisine ilişkin bilgi sağlar. Tam sürüm sistem durumu belgelerinde daha fazla bilgi edinin .
  </p>
- <h5>performance monitoring</h5>
  <p>
  Performans izleme, uygulama performansını izleme ve kaç işlemin gönderildiği ve belirli bir işlemin tüm oluşumları için ortalama yanıt süresi gibi metrikleri ölçme eylemidir. Bunu yapmak için Sentry, bireysel hizmetlerin yanı sıra bu hizmetler içindeki işlemleri ölçmek için işlemlerden ve aralıklardan oluşan dağıtılmış izleri yakalar.
  </p>
- <h5>alerts</h5>
  <p>
  Uyarılar, belirli uyarı kuralı koşulları karşılandığında size bildirimler göndererek kodunuzla ilgili sorunları gerçek zamanlı olarak size bildirir. Özelleştirilebilir eşikler ve entegrasyonlarla kullanılabilen çeşitli uyarı türleri vardır.
  </p>

<br>
<br>
<br>
<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/sentry-basic/dsn-explainer.md"><strong>Sonraki Ders -></strong></a></div>