<h1 align="center">Breadcrumb Kullanma (Using Breadcrumbs)</h1>

<p>Sentry, bir sorundan önce meydana gelen olayların izini oluşturmak için içerik kırıntılarını kullanır. Bu olaylar geleneksel günlüklere çok benzer, ancak daha zengin yapılandırılmış verileri kaydedebilir.</p>

<p>SDK'lar, entegrasyonları etkinleştirerek içerik haritalarını otomatik olarak kaydetmeye başlar. Bunu platformunuz için nasıl yapacağınızı öğrenmek için sayfanın üst kısmındaki açılır menüden platformu seçin, ardından o platform için içerik kırıntıları belgelerini inceleyin.</p>

<p>Bir hata olayı bir iz sağlıyorsa, sentry.io, Sorun Ayrıntıları sayfasında içerik haritalarını görüntüler:</p>
<img src="https://docs.sentry.io/static/1c8c99d9aa883cbaedceb4daa4005ed2/59f0d/crumb-section.png">

<h4>Breadcrumb Detail</h4>

<p>İçerik haritasının her bölümü ayrı bir satırda görüntülenir ve her satırda şu ayrıntılar bulunur: Tür(Type), Kategori(Category), Açıklama(Description), Düzey(Level) ve Zaman(Time).</p>

<h5>Type</h5>

<p>Yarı dahili bir öznitelik type, içerik haritasının türünü kontrol edebilir. Varsayılan olarak, tüm içerik haritaları olarak kaydedilir , bu da onların bir girdi defaultolarak görünmesini sağlar, ancak Sentry, içerik haritalarının nasıl oluşturulacağını etkileyen başka türler sağlar.</p>

<h5>Kategori</h5>

<p>Etkinliğin kategorisi. Bu veriler bir günlükçü adına benzer ve auth gibi bir olayın gerçekleştiği alanı anlamanıza yardımcı olur.</p>

<h5>Tanım</h5>

<p>Bir açıklama ya:</p>

- <p>Mesaj(Message): Tüm boşluklar korunarak metin olarak işlenen, olayı açıklayan bir dize. Genellikle geleneksel bir günlük mesajı için bir açılır mesaj olarak kullanılır.</p>
-  <p>Veri(Data): Olay meta verilerinin bir anahtar/değer eşlemesi. Bu genellikle bir mesaj yerine kullanılır, ancak bir mesaja ek olarak da kullanılabilir. sentry.io gönderilen tüm verileri görüntüler.</p>

<h5>Level</h5>

<p>Bir olayın ciddiyeti. Düzey, önem derecesine göre önemli, hata, uyarı, bilgi ve hata ayıklama olan beş değerden birine ayarlanır.</p>

<h5>Time</h5>

<p>İçerik haritasının ne zaman oluştuğunu gösteren bir zaman damgası. Biçim, RFC 3339'da tanımlandığı gibi bir dize veya Unix döneminden bu yana geçen saniye sayısını temsil eden sayısal (tamsayı veya kayan nokta) bir değerdir. Varsayılan olarak, sentry.io zaman damgasını mutlak bir zaman olarak görüntüler. Görüntüyü göreli zamana güncellemek için geçiş düğmesine tıklayabilirsiniz:</p>

<img src="https://docs.sentry.io/static/cdcdb0ca4d1f09508ccd34aa62a2c018/f2d11/toggle-time-btn.png">

<br>
<br>

<h4>Ekranı Filtreleme</h4>
<p>Ekmek kırıntıları listesini türe ve düzeye göre filtreleyebilirsiniz. Sağlanan türler ve seviyeler, filtrede seçenekler olarak görüntülenir:</p>
<br>
<br>
<img src="https://docs.sentry.io/static/5cd520222297b764289f7c2b29d0f260/08115/filter-by.png">

<br>
<br>

<h4>Tam Metin Arama</h4>

<p>Filtre arama alanına herhangi bir şey yazarsanız, sentry.io tüm parçalanmış verileri filtreler ve arama kriterlerine uygun bir eşleşme bulmaya çalışır. Bir tane bulursa, eşleşme vurgulanır. Tam metin arama, Filtreleme Ölçütü seçeneğiyle birlikte de çalışır</p>

<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/sentry-basic/environments"><strong>Sonraki Ders -></strong></a></div>
<br>
<br>
<br>