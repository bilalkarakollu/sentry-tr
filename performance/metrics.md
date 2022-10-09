<h1 align="center">Metrikler</h1>

<p>Metrikler, kullanıcıların uygulamanızı nasıl deneyimlediği hakkında bilgi sağlar. Performans bölümünde, başlamanıza yardımcı olacak birkaç temel metrik ayarlayacağız. Hedef eşiklerde daha fazla özelleştirme için, Discover Query Builder'ı kullanarak bir sorgu oluşturmaktan çekinmeyin. Uygulamanızı ölçmek için faydalı eşikleri belirleyerek, uygulamanızın sağlığının ölçülebilir bir ölçümüne sahip olursunuz. Bu, hataların ne zaman meydana geldiğini veya performans sorunlarının ortaya çıkıp çıkmadığını daha kolay belirleyebileceğiniz anlamına gelir.</p>

<h4>Apdex</h4>

<i>Apdex, uygulama yanıt sürelerinize dayalı olarak kullanıcı memnuniyetini izlemek ve ölçmek için kullanılan endüstri standardı bir ölçümdür. Daha yüksek bir Apdex puanı, daha düşük olandan daha iyidir; puan, tatmin edici bir deneyime sahip kullanıcıların %100'ünü temsil eden 1.0'a kadar çıkabilir. 1 e yakın olan puan iyiye işarettir. Apdex puanı, belirli bir işlem veya uç noktada <strong>tatmin edici</strong>, <strong>tolere edilebilir</strong> ve <strong>hayal kırıklığına</strong> uğramış isteklerin oranını sağlar. Bu metrik, işlem performansını karşılaştırmanız, hangilerinin ek optimizasyon veya araştırma gerektirebileceğini anlamanız ve performans için hedefler veya hedefler belirlemeniz için bir standart sağlar.</i>

<p>Apdex'in bileşenleri ve formülü aşağıdadır:</p>

- <strong>T</strong>: Hedef yanıt süresi için eşik.
- <strong>Satisfactory (Tatmin Edici)</strong>: Kullanıcılar, sayfa yükleme süreleri T'ye eşit veya daha az olduğunda uygulamayı kullanmaktan memnun olurlar.
- <strong>Tolerable (Tolere Edilebilir)</strong>: Kullanıcılar, sayfa yükleme süreleri T'den büyük ve 4T'ye eşit veya daha az olduğunda uygulamayı kullanmak için tolere edilebilir olarak kabul eder.
- <strong>Frustrated (Hayal Kırıklığı)</strong>: Sayfa yükleme süreleri 4T'den fazla olduğunda kullanıcılar uygulamadan rahatsız olurlar.
- <strong>Apdex</strong>: 

<strong>(Tatmin Edici İstek Sayısı + (Tolere Edilebilir İstek Sayısı/2)) / (Toplam İstek Sayısı)</strong>

<p>Apdex için tatmin edici bir yanıt süresi eşiğinin (ms) ne olduğunu <strong>Ayarlar > Performans</strong> bölümünde yapılandırın. Bunu, özel eşiklerle her proje için ayarlayabilirsiniz.</p>

<h4>Başarısızlık oranı (Failure Rate)</h4>
<i>failure_rate()başarısız işlemlerin yüzdesini gösterir. </i>

<h4>Verim (Throughput):</h4>

<p>Verim, belirli bir zaman aralığında (Toplam), dakika başına ortalama işlem (TPM) veya saniye başına ortalama işlem (TPS) üzerindeki işlem sayısını gösterir.</p>

<h4>Gecikme (Latency):</h4>

<h5>Average Transaction Duration</h5>
<p>Ortalama İşlem Süresi, belirli bir işlemin tüm oluşumları için ortalama yanıt süresini gösterir.</p>
<p>Aşağıdaki işlevler işlem sürelerini toplar:</p>

- ortalama (average)
- çeşitli yüzdelikler (varsayılan olarak, önceden oluşturulmuş İşlemler sorgusu 75. ve 95. yüzdelikleri gösterir, ancak özel yüzde birlik dahil olmak üzere birçok başka seçenek vardır).
- maksimum (maximum)

<br>

<h4>P50 Eşiği</h4>
<i>P50 Eşiği, işlem sürelerinin %50'sinin eşikten daha büyük olduğunu gösterir. Bu aynı zamanda ortancadır. Örneğin, P50 eşiği 10 milisaniyeye ayarlanırsa, işlemlerin %50'si bu eşiği aşarak 10 milisaniyeden uzun sürer.</i> <br>
<i><strong>Örneğin p50 eşiği 1 saniye olarak ayarlandığında, 100 işlemden 50 si 1 saniye üzerinde gerçekleştiğini ifade eder.</strong></i>
<br>
<br>
<br>

<h4>P75 Eşiği</h4>

<p><i>P75 Eşiği, işlem sürelerinin %25'inin eşikten daha büyük olduğunu gösterir. Örneğin, P75 eşiği 10 milisaniyeye ayarlanırsa, işlemlerin %25'i bu eşiği aşarak 10 milisaniyeden uzun sürer.
</i></p>
<i><strong>Örneğin p75 eşiği 1 saniye olarak ayarlandığında, 100 işlemden 25 i 1 saniye üzerinde gerçekleştiğini ifade eder.</strong></i>
<br>
<br>
<br>
<h4>P95 Eşiği</h4>
<p><i>
P95 Eşiği, işlem sürelerinin %5'inin eşikten daha büyük olduğunu gösterir. Örneğin, P95 eşiği 50 milisaniye ise, işlemlerin %5'i bu eşiği aşarak 50 milisaniyeden uzun sürer.
</i></p>
<i><strong>Örneğin p95 eşiği 1 saniye olarak ayarlandığında, 100 işlemden 5 i 1 saniye üzerinde gerçekleştiğini ifade eder.</strong></i>

<br>
<br>
<br>

<h4>P99 Eşiği</h4>
<p><i>
P99 Eşiği, işlem sürelerinin %1'inin eşikten daha büyük olduğunu gösterir. Örneğin, P99 eşiği 5 saniye ise, işlemlerin %1'i bu eşiği aşarak 5 saniyeden uzun sürer.
</i></p>
<i><strong>Örneğin p99 eşiği 1 saniye olarak ayarlandığında, 100 işlemden 1 i 1 saniye üzerinde gerçekleştiğini ifade eder.</strong></i>

<br>
<br>
<br>

<h4>User Misery (Kullanıcı sefaleti)</h4>

<p>User Misery, uygulama performansınızın göreli büyüklüğünü değerlendirmek için kullanıcı ağırlıklı bir performans metriğidir. Apdex ile çeşitli yanıt süresi eşik düzeylerinin oranını inceleyebilseniz de ,<storng>User Misery</storng>, tatmin edici yanıt süresi eşiğinin (ms) <strong>dört katına(4)</strong> dayalı olarak hayal kırıklığına uğrayan benzersiz kullanıcıların sayısını sayar. User Misery, kullanıcılar üzerinde en yüksek etkiye sahip işlemleri vurgular.</p>


<br>
<br>
<br>

<h4>Özel Eşikler</h4>

<p>Her proje için Apdex ve User Misery'nin nasıl hesaplanacağını <strong>[Project] > Settings > Performance</strong> içinde yapılandırabilirsiniz. Proje düzeyindeki ayarları, <strong>İşlem Özeti > Ayarlar</strong>'da işlem düzeyinde geçersiz kılabilirsiniz .</p>