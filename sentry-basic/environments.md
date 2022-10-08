<h1 align="center">Environments (Ortamlar)</h1>

<p>Environment SDK'nıza ekleyebileceğiniz (ve eklemeniz gereken) Sentry tarafından desteklenen bir etikettir. Genel olarak etiket herhangi bir değeri kabul eder, ancak kod dağıtımlarınızın geliştirme , test etme , hazırlama veya üretim gibi adlandırma kurallarına başvurmayı amaçlar .</p>

<p>
Ortamlar, sentry.io'nun <strong>Issue Details</strong>(Sorun Ayrıntıları) sayfasında sorunları, yayınları ve kullanıcı geri bildirimlerini daha iyi filtrelemenize yardımcı olur . Bu sayfada, en son sürüme odaklanarak belirli bir ortam hakkındaki bilgileri görüntüleyebilirsiniz. Çok aşamalı bir yayın süreci kullanıyorsanız, uyarıları yalnızca belirli yayın aşamalarıyla sınırlamak için farklı bir varsayılan ortam seçebilir ve öznitelikle eşleşen koşullar ayarlayabilirsiniz.
</p>

<p>
Farklı hizmetleri veya uygulamaları ayırmak için projeleri ve farklı ortamları ayırmak için ortamları veya her biri içindeki aşamaları serbest bırakmak için kullanın. Sentry'nin web kullanıcı arayüzünün filtrelerinde bir veya daha fazla proje seçtiyseniz, ortam seçici yalnızca seçili projelerden olaylarla ilişkili ortamları gösterir.
</p>

<br>

<img src="https://docs.sentry.io/static/4f1f959712aee07f50588448e19db633/e04e6/env_dropdown.png">

<br>
<br>
<p>
Ortamlar her kuruluş için benzersizdir. Ancak ortam ayarları, proje başına ortamları gizleyebildiğiniz için proje başına tanımlanır.
</p>

<h5>Ortamlar Oluşturma</h5>

<p>
Sentry, ortam etiketine sahip bir olay aldığında ortamları otomatik olarak oluşturur. Ortamlar büyük/küçük harfe duyarlıdır. Ayrıca , her SDK için belgelendiği gibiinit , SDK'nızı ilk kez oluşturduğunuzda bir ortam oluşturabilirsiniz .
</p>

<h5>Environment Filter(Ortam Filtresi)</h5>
<h6>Issues</h6>

<p>
Bir sorunda birden çok ortamdan olay varsa, bu ortamlardan herhangi birini seçtiğinizde sorun görünür. Sentry, bir sorunu benzer olayların bir gruplaması olarak tanımlar. Belirli bir ortamla ilgili bir sorun içinde bir veya daha fazla etkinliği etiketlerseniz, bu sorun, o ortam tarafından filtrelendiğinde görünümünüzde görünür.
</p>

<br>
<br>
<br>
<div style="display: flex; align-items: center; justify-content: space-between"><a href="/sentry-tr/"><strong>Anasayfa</strong></a><a href="/sentry-tr/sentry-basic/integrate-frontend.md"><strong>Sonraki Ders -></strong></a></div>