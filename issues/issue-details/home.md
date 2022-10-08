<h1 align="center">Sorun Ayrıntıları (Issues Detail)</h1>

<p>Sorun Ayrıntıları sayfası, sorunun kaynağı ve uygulamanızın kullanıcıları üzerindeki etkisi hakkında daha fazla bilgi edinmenize yardımcı olur. Sayfanın ana alanı, bir sorunun parçası olan belirli bir hata olayıyla ilgili bilgileri görüntüler. Sayfanın üst paneli ve sağ kenar çubuğu, bu sayıda gruplandırılmış tüm olayların bir özetini görüntüler.</p>

<img src="https://docs.sentry.io/static/8bce13c96cf484065f2560ae06da2804/2b608/issue-details.png">

<p>Sorun Ayrıntıları sayfası , bir sorunun parçası olan belirli bir hata olayıyla ilgili bilgileri görüntülerken, "Eski" ve "Daha Yeni" düğmelerini kullanarak bir sorunun olayları arasında gezinebilirsiniz. Zil simgesini tıklayarak bir soruna abone olun ve <strong>Kullanıcı Ayarları > Bildirimler</strong>'de sorunla ilgili iş akışı bildirimlerinde ince ayar yapın . Sorun başlığının hemen altında, olayın hata seviyesini temsil eden bir simgeyle birlikte olay açıklaması görüntülenir:</p>

<br>
<br>
<img src="https://docs.sentry.io/static/beb27655a6b091af9d494a6e8c0733ba/4c04a/error-level-icon-2.png">

<br>
<br>

<p>Seviye şunlar olabilir:</p>

- Hata(Error) - turuncu
- Bilgi(Info) - mavi
- Uyarı(Warning) - sarı
- Ölümcül(Fatal) - kırmızı
- Hata ayıklama(Debug) - gri
- Örnek(Sample) - mor

<p>
<i>Sağ kenar çubuğunda, sentry.io, sorunun son 24 saat ve son 30 gün içinde ne sıklıkta meydana geldiği ve ayrıca sorunun en son ne zaman ve ilk görüldüğü gibi bilgileri içeren bir özeti yansıtır.</i>
</p>
<p>Sorun herhangi bir GitHub veya Jira sorunuyla bağlantılıysa bu da burada görüntülenir. Bu bölümü, mevcut GitHub veya Jira sorunlarına bağlanmak için de kullanabilirsiniz. Son olarak, sayıya dahil edilen tüm olaylar için etiketlerin değerlerinin dağılımını gösteren bir yön haritası vardır. Bu değerlerin tümü, ortam açılır menüsünde seçtiğiniz ortamı temel alır.

Ek olarak, bu sayfa birkaç başka önemli bilgi sağlar.
</p>

<h4>İz Gezgini (Trace Navigator)</h4>
<br>
<p>İzleme gezgini (tarihin altında görüntülenir), mevcut işlem için ilgili izlemenin kısaltılmış bir görünümüdür . Her biri olay izinin farklı gruplarını temsil eden en fazla altı düğüm görüntüler:</p>

- <strong>Kök(Root)</strong> : İşlemi başlatma
- <strong>Ata(Ancestor)</strong> : Kökün soyundan gelen ve doğrudan mevcut olayla ilgili olan olaylar
- <strong>Ebeveyn(Parent)</strong> : Mevcut olayı doğrudan başlatan olay
- <strong>Bu Olay(This Event)</strong> : Görüntülenmekte olan mevcut olayı temsil eden düğüm
- <strong>Çocuklar(Children)</strong> : Mevcut etkinliğin doğrudan başlattığı etkinlikler
- <strong>Torunları(Descendants)</strong> : Bu etkinliğin çocukları tarafından oluşturulan gelecek nesiller etkinlikleri

<br>
<br>

<h4>Şüpheli İşlemler (Suspect Commits)</h4>

<p>Şüpheli taahhüt , hata olayına potansiyel olarak neden olduğu belirlenen bir taahhüttür. Şüpheli taahhütleri yapılandırdıysanız bunlar görüntülenir. Bu, sorunu oluşturmuş olması muhtemel taahhütleri hemen araştırmanıza olanak tanır. Şüpheli taahhüdün yazarı da konu için bir vekil olarak önerilmektedir.</p>

<h4>Etiketler(Tags)</h4>

<p>
Etiketler , hem dizine alınmış hem de aranabilir anahtar/değer dizisi çiftleridir. Örneğin, bir etiket size etkinlikle ilişkili tarayıcı, cihaz veya kullanıcı gibi bilgiler sağlar. Etiketler, bireysel olay için SDK tarafından gönderilen tanılama bilgileridir.
</p>

<p>Bu sayfanın ana bölümünde görüntülenen etiketler, görüntülemekte olduğunuz etkinliğe özeldir. Buna karşılık, sağ kenar çubuğunda görüntülenen etiketler, sayıya dahil edilen tüm etkinlikler için tüm etiket değerlerinin bir özetidir. Etiketleri Özelleştirme bölümünde açıklandığı gibi hata ayıklama için daha kullanışlı hale getirmek için kendi etiketlerinizi ayarlayabilirsiniz .</p>

<h4>İstisna (Yığın İzleme) (Exception)</h4>
<p>Sayfanın İstisna bölümü, size olayın hata verdiği kod satırını gösteren yığın izlemesini görüntüler.</p>

<img src="https://docs.sentry.io/static/a18607dcbb1e9905afcda6eab4588fd8/7830c/issue-exception.png">


<br>
<br>

<p>Bu, Sentry gruplandırma algoritmasının olayları tek bir sorunda gruplamak için kullandığı en önemli bilgi parçasıdır. Ayrıca olayların nasıl gruplanacağını da özelleştirebilirsiniz. Sorun Gruplandırma'da özelleştirilmiş gruplama hakkında daha fazla bilgi edinin.</p>
<br>

<h4>Breadcrumbs</h4>

<p>Breadcrumbs, hata olayına giden bir geçmiş ve zaman çizelgesi sağlar. Bunlar, HTTP istekleri, konsol veya sunucudan günlük ifadeleri ve JavaScript'teki DOM (belge nesne modeli) olayları gibi şeyleri içerebilir.</p>

<img src="https://docs.sentry.io/static/d60f6177b17d08d52c0410f931a57056/47218/issue-breadcrumbs.png">

<h4>Sekmeler (Tabs)</h4>

<p>Bu sayfa, ilk açıldığında Ayrıntılar sekmesini görüntüler, ancak birkaç başka sekme daha mevcuttur:</p>

- Etkinlik(Activity): Ekip üyelerinin yorum paylaşabileceği etkinlik için etkinlik geçmişi.
- Kullanıcı Geri Bildirimi(User Feedback): SDK'nın kullanıcı geri bildirimi aracılığıyla kullanıcılardan toplanan herhangi bir geri bildirim .
- Ekler(Attachments) : Olaya eklenen yapılandırma veya günlük dosyaları gibi depolanan ek dosyalar.
- Etiketler (Tags): Sayıda yer alan tüm etkinliklerdeki etiketler hakkında daha ayrıntılı bilgi.
- Olaylar (Events): Sayıda yer alan tüm olayların listesi.
- Birleştirilmiş Sorunlar (Merged Issues): Bununla birleştirilmiş sorunların listesi.
- Benzer Sorunlar (Similar Issues): Birleştirebileceğiniz benzer yığın izine sahip sorunların listesi.

<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/issues/issue-details/breadcrumbs"><strong>Sonraki Ders -></strong></a></div>
<br>
<br>
<br>