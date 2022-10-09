<h1 align="center">Uyarı Türleri</h1>

<p>İki tür uyarı oluşturabilirsiniz:</p>

- <strong>Sorun uyarıları</strong>(Issue alerts): Bir sorun (gruplandırılmış bir dizi hata olayı) belirli bir ölçütle eşleştiğinde tetiklenir.

- <strong>Metrik uyarıları</strong>(Metric alerts): Hata veya işlem olayları için makro düzeydeki metrikler belirli eşikleri aştığında tetiklenir.

<h4>Sorun uyarıları (Issue Alerts)</h4>

<p>Sorun uyarıları, belirtilen kriterlere uyan bir projedeki herhangi bir sorun için yeni bir olay alındığında tetiklenir. Bu kriterler, örneğin, yeniden ortaya çıkan çözülmüş bir sorun veya birçok kullanıcıyı etkileyen bir sorun olabilir.</p>

<p>"Uyarı Kuralları" sekmesinde, bu uyarılar sorunlar simgesiyle tanımlanır ve varsayılan olarak uyarı listenizin altında görüntülenir. (Birkaç ölçüm uyarınız varsa, bu, sorun uyarılarınızı listenin ilk sayfasından kaldırabilir.)</p>

<img src="https://docs.sentry.io/static/09f8abe9de1661b668022a0c95061b7c/97a96/issue-alert-rules.png">

<p>Sorun uyarılarında, Sentry her yeni olay aldığında yapılandırılmış uyarı koşullarını değerlendirir. Uyarı koşullarının üç bölümü vardır:</p>

- Tetikleyiciler, ne tür bir etkinliğin izlenmesini istediğinizi veya bir uyarının ne zaman tetiklenmesi gerektiğini belirtir.
- Filtreler, yalnızca sorun belirtilen kriterlerle eşleşiyorsa bir uyarıyı tetikleyerek gürültüyü kontrol etmeye yardımcı olur.
- Ardından Eylemler, tetikleyici koşullar karşılandığında ve filtreler eşleştiğinde ne olması gerektiğini belirtir.

<h4>Uyarı Ayrıntıları</h4>

<p>Uyarı Ayrıntıları sayfası , bir sorun uyarı kuralının zaman içinde tetiklenme sayısını bir saatlik gruplar halinde gruplanmış olarak gösterir. "Uyarı Kuralları" sekmesindeki uyarı kuralı adına veya aldığınız bildirime tıklamanız sizi bu sayfaya götürecektir. Sayfa ayrıca uyarı kuralı koşullarını, uyarının mevcut durumunu (Uyarı, Kritik veya Çözümlendi) ve ne zaman oluşturulduğu, en son ne zaman değiştirildiği ve uyarının sahibi olan ekip gibi uyarı ayrıntılarını içerir.</p>

<img src="https://docs.sentry.io/static/2d12b3de1091109bb958ffe9229ccb5e/71d2f/issue-alert-status-page-example.png">

<p>Uyarı Ayrıntıları sayfası , uyarıyı tetikleyen sorunların bir listesini de içerir. Daha fazla bilgi için o sayının ayrıntılar sayfasına gitmek için listedeki sorunlardan herhangi birine tıklayabilirsiniz.</p>

<h4>Metrik Uyarıları</h4>

<p>Metrik uyarıları, bir projedeki hata sayısındaki ani artış veya gecikme, Apdex, başarısızlık oranı veya aktarım hızı gibi bir <a href="/sentry-tr/performance/metrics">performans metriğindeki</a> değişiklik gibi bir metrik eşiği aştığında size haber verir.

Metrik uyarıları, hem hata hem de işlem olayları için makro düzeydeki metrikleri izler. Bir metrik, bir dizi olayı alır ve belirli bir süre boyunca olay özelliklerine uygulanan count() veya avg() gibi bir işlevi kullanarak toplu bir değer hesaplar. Bir metrik uyarısı oluşturduğunuzda, olayları özniteliklere ve etiketlere göre filtreleyebilirsiniz.</p>

<h4>Hatalar</h4>

- Hata Sayısı
- Hata Yaşayan Kullanıcılar

<h4>Performans</h4>
<p>Performans uyarıları için, işlenmiş işlem olaylarına dayalı veriler varsayılandır. Uyarınızı yapılandırırken işlenmiş olay verileriyle uyumlu olmayan bir seçim yaparsanız, uyarınız dizine alınmış işlem olaylarını veya olaya dayalı verileri kullanır ve bunu söyleyen bir mesaj görüntülenir.</p>

- Throughput
- Transaction Duration
- Apdex
- Failure Rate
- Largest Contentful Display
- First Input Delay
- Cumulative Layout Shift
- Custom Metric

<h4>Uyarı Ayrıntıları</h4>
<p>Uyarı Ayrıntıları sayfası , varsayılan olarak son 24 saat için bir metrik uyarı kuralının geçmişini gösterir, ancak "Görüntüle" açılır menüsünü kullanarak süreyi değiştirebilir. Bir uyarı tetiklendiğinde, aldığınız bildirime tıklamak sizi uyarının aktif olduğu süreyi gösteren bu sayfaya götürür. Sayfa ayrıca uyarı kuralı koşulları, uyarının mevcut durumu ve uyarının her bir durumda (Kritik, Uyarı veya Çözümlendi) ne kadar zaman harcadığının bir özeti gibi ayrıntıları içerir.</p>

<img src="https://docs.sentry.io/static/2836a33e2d2a7e97bed09155026d8250/97a96/alert-details-example.png">

<p><strong>Uyarı Ayrıntıları</strong> sayfası, temel sorunun daha hızlı belirlenmesine yardımcı olmak için ölçümle ilgili şüpheli sorunların veya işlemlerin bir listesini de içerir</p>

<br>
<br>
<br>
<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/sentry-basic/alerts/create-alerts"><strong>Sonraki Ders -></strong></a></div>

<br>
<br>
<br>