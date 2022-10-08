<h1 align="center">Performans sorunları</h1>

<p>Performans sorunları için Sorun Ayrıntıları sayfası, bir sorunun kaynağı ve uygulamanızın kullanıcıları üzerindeki etkisi hakkında daha fazla bilgi edinmenize yardımcı olur. Sayfanın ana alanı, bir sorunun parçası olan belirli bir işlem olayıyla ilgili bilgileri görüntüler. Sayfanın üst paneli ve sağ kenar çubuğu, bu sayıda gruplandırılmış tüm olayların bir özetini görüntüler:</p>

<br>
<br>

<img src="https://docs.sentry.io/static/3e2e02eb62c2c55b25f335bc9ce0d348/97a96/performance-issue-details.png">

<br>
<br>

<p>Sorun Ayrıntıları sayfası , bir sorunun parçası olan belirli bir işlem olayıyla ilgili bilgileri görüntülerken, "Eski" ve "Daha Yeni" düğmelerini kullanarak bir sorunun olayları arasında gezinebilirsiniz. Sorunla ilgili bilgilerin yanı sıra en son etkinliğin ayrıntılarını da göreceksiniz. Ayrıca, sorunun ne zaman görüldüğünün özetini, etiketlerin dökümünü, yayılma kanıtlarını ve varsa kırıntıları da görebileceksiniz.</p>

<h4>Performans Sorunları Nasıl Çalışır?</h4>
<p>Sentry, gelen işlem olaylarını tarayarak performans sorunlarını tespit eder. Önce olası sorunları tespit etmek için işlemin çeşitli özelliklerini (yayılma süreleri, yayılma düzenlemesi, yayılma türleri vb.) kontrol ederiz. Ardından, bir performans sorununun olup olmadığını belirlemek için bu özellikleri ilgili eşiklerle karşılaştırırız. Son olarak, benzersiz bir problem oluşturuyoruz parmak iziBir olayı tanımlayan özellikler kümesi.uygulamadaki sorun türüne ve konumuna göre ve bir performans sorunu oluşturmak için bu parmak izini kullanın.</p>

<h4>Etiketler</h4>

<p>Etiketler, hem dizine alınmış hem de aranabilir anahtar/değer dizisi çiftleridir. Örneğin, bir etiket size etkinlikle ilişkili tarayıcı, cihaz veya kullanıcı gibi bilgiler sağlar. Etiketler, bireysel olay için SDK tarafından gönderilen tanılama bilgileridir.</p>

<p>Bu sayfanın ana bölümünde görüntülenen etiketler, görüntülemekte olduğunuz etkinliğe özeldir. Buna karşılık, sağ kenar çubuğunda görüntülenen etiketler, sayıya dahil edilen tüm etkinlikler için tüm etiket değerlerinin bir özetidir. Etiketleri Özelleştirme bölümünde açıklandığı gibi hata ayıklama için daha kullanışlı hale getirmek için kendi etiketlerinizi ayarlayabilirsiniz.</p>

<h4>Yayılma Kanıtı</h4>

<p>Span kanıtı, mevcut olay bağlamında performans sorununu açıklayan bilgilerdir. Soruna neden olan belirli veritabanı sorguları, sorunu içeren aralıklar ve performans üzerinde etkisi olan yavaş aralıklar gibi ayrıntıları içerebilir. Bu bölümde ayrıca sorunlu yayılmaların olayın geri kalanıyla nasıl ilişkili olduğunu gösteren bir yayılma ağacı vardır. Farklı performans sorunlarının biraz farklı kanıtları olacaktır.</p>


<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/issues/states-triage"><strong>Sonraki Ders -></strong></a></div>

<br>
<br>
<br>