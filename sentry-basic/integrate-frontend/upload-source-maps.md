<h1 align="center">Hatalarınızda Okunabilir Yığın İzlerini Etkinleştirin</h1>


<p>Yayın sürümü , kodunuzun yeni bir sürümünü her gönderdiğinizde değişen dinamik bir tanımlayıcıdır. Sentry'ye sürümleriniz hakkında bilgi verdiğinizde, alım sırasında küçültülmüş JavaScript yığın izlerinin kaynak eşlemesi dahil olmak üzere çeşitli özelliklerin kilidini açarsınız. Sürüm belgelerimizde daha fazla bilgi edinin . Bu bölümde şunları yapacaksınız:</p>

1- Sentry hesabınızı şu şekilde güncellemek için oluşturma işlemi sırasında Sentry CLI'yi kullanın :

- Yeni bir yayın sürümü oluşturma
- Projenin en son kaynak haritalarını yükleme (ve bunları yeni yayın sürümüyle ilişkilendirme)

2- Yayın sürümünü Sentry SDK yapılandırmasına ekleyin. Bu, uygulamamızda SDK tarafından yakalanan herhangi bir hatayı bu özel sürümle ilişkilendirir. Sentry, hatanın yığın izini küçültmek için sürümün yüklenen kaynak haritalarını kullanacak.


