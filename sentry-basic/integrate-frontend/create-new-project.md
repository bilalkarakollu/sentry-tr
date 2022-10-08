<h1 align="center">Create a Sentry Project (Sentry Projesi Oluşturun)</h1>

<p>Bu öğreticide, Sentry hesabınızda yeni bir proje oluşturacaksınız. Projeler, olayları kuruluşunuzdaki farklı bir uygulamayla kapsamanıza ve kuruluşunuzdaki belirli kullanıcılara ve ekiplere sorumluluk ve sahiplik atamanıza olanak tanır. Uygulamanızda kullanılan belirli bir dil veya çerçeve için proje oluşturabilirsiniz. Örneğin, API sunucunuz ve ön uç istemciniz için ayrı projeleriniz olabilir</p>

<h4>Adım 1: Projeyi oluşturun</h4>

<p>1 - Tüm projelerinizin listesini görüntülemek için sol taraftaki gezinme menüsünden <strong>Projeler'i(Projects)</strong> seçin .</p>

<p>2 - <strong>"+ Proje Oluştur" (Create Project)</strong> düğmesine tıklayın.</p>

<br>


- <p>İzlemek istediğiniz koda göre projeniz için dili veya çerçeveyi seçin - bu durumda "React".</p>
- <p>"Proje adı" alanında projeye bir ad verin.</p>
- <strong>"Varsayılan uyarı ayarlarınızı yapın"(Set your default settings)</strong> altında, <strong>"Daha sonra kendi uyarılarımı oluşturacağım"</strong> ı seçin.
- <strong>"Ekip"(Team)</strong> açılır menüsünden birini seçerek projeye bir ekip atayın.

<br>

<img src="https://docs.sentry.io/static/14b89bd65f4eb71d2accd7a5fed04c05/2cefc/create-new-project-02.png"/>

<br>
<br>

> Herhangi bir ekip tanımlamadıysanız, varsayılan kuruluş ekibini (Sentry kuruluşunuzla aynı ada sahip ekip) seçebilir veya yeni bir ekip oluşturmak için "+" düğmesini tıklayabilirsiniz.

<p>3- "DSN" anahtarını kopyalayın ve anahtarı kaynak koduna kopyalayacağınız için elinizin altında bulundurun.</p>

<br>
<br>

<img src="https://docs.sentry.io/static/f72cab45b796b9e61843e51b8fc07abf/2cefc/create-new-project-04.png">

<br>
<br>

>DSN (veya Veri Kaynağı Adı), olayları az önce oluşturduğunuz projeyle ilişkilendirerek SDK'ya olayları nereye göndereceğini söyler.

<h4>2. Adım: Bir uyarı kuralı oluşturun</h4>

<p>Her proje için çeşitli uyarı kuralları oluşturabilir ve uygulamanızda hatalar oluştuğunda ne zaman, nasıl ve kime bildirmek istediğinizi Sentry'ye bildirebilirsiniz. Uyarı kuralları , ilişkili koşullar karşılandığında gerçekleştirilen koşullardan ve eylemlerden oluşur . Yeni bir proje oluştururken, yeni bir sorun ilk kez göründüğünde tüm proje ekibi üyelerini (e-posta ile) bilgilendiren bir uyarı kuralıyla oluşturmayı seçebilirsiniz . Bu, bir daha benzer bir hata oluştuğunda, hata "yeni" olmadığı için bildirimin tetiklenmediği anlamına gelir.</p>

<p>Bu adımda, zaten var olan bir sorunla ilişkili olsa bile, her olay gerçekleştiğinde bildirimde bulunan yeni bir uyarı kuralı oluşturursunuz . Gerçek hayattaki bir senaryoda, son kullanıcınızın tarayıcılarındaki ön uç kodunuzda her olay gerçekleştiğinde bilgilendirilmek istemeyeceğiniz için muhtemelen ek koşullar eklersiniz.</p>

<p>1- Sol taraftaki menüden Uyarılar'ı seçin.</p>
<p>2- "Uyarı Oluştur" u tıklayın.</p>
<br>
<br>
<img src="https://docs.sentry.io/static/25d9120ce233bcb305bb0087e244f191/2cefc/generate-first-error-08.png">

<br>
<br>

>Projeniz henüz seçilmemişse, kural kurulumuna başlamadan önce bunu yapmanız istenecektir.

<p>3- Uyarı türü olarak "Sorunlar"ı seçin ve "Koşulları Ayarla"yı tıklayın.</p>

<br>
<br>

<img src="https://docs.sentry.io/static/679db891db1bd54ad2ecb8ee7e476cc8/2cefc/generate-first-error-10.png">

<br>
<br>

<p>4- Aşağıdaki değerleri girin:</p>

- <p>"Ortam" alanında, "Tüm Ortamlar" ı seçin</p>
- <p>"Uyarı adı" alanına "Tüm Olaylarda Uyarılar" girin</p>
- <p>"SONRA" koşulları altında, görüntülenen açılır listeden "İhraç Sahiplerine, Takıma veya Üyeye bildirim gönder"i ve ardından "Ekip"i seçin; takımını seç</p>
- <p>Eylem aralığını beş dakikaya ayarlayın</p>

<br>
<br>

<img src="https://docs.sentry.io/static/1e05cbc67f26d1b33ef93755e3eff9b1/f0811/generate-first-error-09.png">

<br>
<br>

> Yeni uyarı kuralı , Tüm Ortamlarda bir olay her yakalandığında seçilen ekip üyelerini bilgilendirir . Varsayılan olarak, bildirim e-posta ile gönderilir, ancak ekip bildirim ayarlarınızı <strong>Ayarlar > Ekipler > [Ekip]</strong> 'in "Bildirimler" sekmesinde değiştirebilirsiniz .

<p>5- Yeni kuralı oluşturmak için "Kuralı Kaydet"e tıklayın.</p>


<a href=""><h4>Sonraki</h4></a>