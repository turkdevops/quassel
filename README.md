<? xml version = "1.0" encoding = "utf-8"?>
<rss version = "2.0" xml: base = "https://quassel-irc.org" xmlns: dc = "http://purl.org/dc/elements/1.1/">
<kanal>
 <title> Quassel IRC </title>
 <link> https://quassel-irc.org </link>
 <açıklama> Quassel IRC, modern, platformlar arası, dağıtılmış bir IRC istemcisidir, yani bir (veya birden çok) müşterinin merkezi bir çekirdeğe bağlanabileceği ve buradan ayrılabileceği anlamına gelir - popüler ekran ve metin kombinasyonu gibi WeeChat gibi tabanlı IRC istemcisi, ancak grafiksel. Bu benzersiz özelliğe ek olarak, tüm büyük platformlara (Linux®, Windows® ve MacOS X® ile Android akıllı telefonlar dahil) zevkli, rahat bir sohbet deneyimi getirmeyi hedefliyoruz, bu da meslektaşlarınızla iletişimi yalnızca kolay değil, aynı zamanda ayrıca her yerde mevcuttur.

Ve en iyisi: Quassel'i GPL altında dağıttığımız için hem birada hem de konuşmada olduğu gibi ücretsizdir ve siz de indirip kendiniz görmeye davetlisiniz!

</description>
 <language> tr </language>
<item>
 <title> Biraz Bakım Yapma - Quassel 0.13.1 </title>
 <link> https://quassel-irc.org/node/135 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
& lt; p & gt; Quassel 0.13.1 olan 0.13 döngüsü için bir bakım sürümüyle 2019'a geri döndük. Önceki sürüme göre bir dizi düzeltme ve iyileştirmenin yanı sıra, 0.13.1, birikim mesajlarının hepsinin alınamayacağı Qt4 tabanlı sistemlerde 0.13.0 ile özellikle can sıkıcı bir sorunu düzeltir. & Lt; a href = & quot; https: //github.com/justjanne" & gt; Janne & quot; justJanne & quot; 'e teşekkür etmek istiyorum Koschinski & lt; / a & gt; ve & lt; a href = & quot; https: //github.com/digitalcircuit" & gt; Shane & quot; digitalcircuit & quot; Synan & lt; / a & gt; özellikle bu sorunun nedenini bulmanın yanı sıra düzeltmenin uygulanması ve test edilmesi için! & lt; / p & gt;
& lt; p & gt; Quassel 0.13.0'ı hala Qt4 kullanan bir sistem veya dağıtım üzerinde çalıştırırsanız, yükseltmeyi unutmayın (veya dost dağıtımcılarınızdan bunu yapmasını isteyin), aksi takdirde sohbet geçmişiniz sivilceli olabilir ... Resmi Windows ve OSX için 0.13.0 derlemeleri zaten Qt5 kullanıyor, bu yüzden etkilenmezler. Ayrıca, Qt5 oldukça uzun bir süredir çıktığı için, yakın tarihli herhangi bir dağıtım sürümü geçişi halihazırda yapmış olmalıydı. & Lt; / p & gt;
& lt; p & gt; Quassel 0.13.1 ayrıca veritabanı şeması yükseltmelerini devam ettirilebilir hale getirerek daha sağlam hale getirir ve yerleşik kimlik için dinleme adreslerini yapılandırmaya izin verir. Lütfen & lt; a href = & quot; https: //github.com/quassel/quassel/blob/0.13.1/ChangeLog#L16" & gt; ChangeLog & lt; / a & gt; değişikliklerin tam listesi için. & lt; / p & gt;
& lt; p & gt; Her zaman olduğu gibi, & lt; a href = & quot; /pub/quassel-0.13.1.tar.bz2" & gt; kaynakları & lt; / a & gt; & lt; a href = & quot; / indirmeler & quot; & gt; indirmeler sayfası & lt; / a & gt;. & lt; / p & gt;
& lt; p & gt; Şerefe, & lt; br / & gt;
• Sputnick & lt; / p & gt;
& lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/135" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <category domain = "https://quassel-irc.org/taxonomy/term/12"> duyuru </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/11"> paketleyiciler </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/7"> serbest bırak </category>
 <pubDate> 18 Şubat 2019, Pzt 20:51:58 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 135, https://quassel-irc.org </guid> adresinde
</item>
<item>
 <title> Oluyor! - Quassel 0.13.0 </title>
 <link> https://quassel-irc.org/node/134 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
& lt; p & gt; Quassel IRC'nin son özellik sürümünden bu yana 1312 gün geçti. Zaman zaman proje neredeyse hareketsiz kaldı; daha sonra bazı çok aktif katılımcılar (digitalcircuit, justJanne, romibi, mamarley, sadece birkaçını saymak gerekirse) nedeniyle tekrar faaliyetlerle dolup taşıyordu. Ve sonunda, kendime bile yardım edemedim ve tekrar kodlamaya başlamak zorunda kaldım! Sonuç olarak, nihayet sizin için yeni bir özellik yayınlayabiliriz. Ve ne bir sürüm! & Lt; / p & gt;
& lt; p & gt; Yeni bir markamız ve uygulama simgemiz var, modern Breeze simge setini destekliyoruz ve bir bütün olarak iyileştirilmiş simge teması desteği. Sohbette kullanıcı modlarını gösterme özelliğinden tüm platformlarda yazım denetimine kadar bir dizi UI iyileştirmesi ekledik. Hemen hemen tüm modern biçimlendirme seçeneklerinin oluşturulması da dahil olmak üzere birçok IRCv3 özelliği artık desteklenmektedir. Yeni kimlik doğrulama ve yapılandırma seçenekleri, konteynerleştirmeye veya çekirdek için bir LDAP arka uç kullanımına izin verir. Veritabanı artık 64 bit ileti kimliği ve zaman damgası kullanıyor, bu da onu dev biriktirme listeleri ve 2038 yılı için geleceğe hazır hale getiriyor. & Lt; / p & gt;
& lt; p & gt; Mobil istemcileri daha iyi desteklemek ve performansı artırmak için çok çalışma yapıldı. Örneğin, sohbet etkinliği izleme ve vurgulama kuralları çekirdeğe taşındı, böylece müşterilerin tüm birikimi aynı anda çekmesi gerekmez. Bundan yararlanan ilk mobil istemci & lt; a href = & quot; https: //quasseldroid.info/" & gt; Quasseldroid & lt; / a & gt; ve yakında Android telefonlarda yakında yayınlanacak olan tam bir yeniden yazım gördü sen. Elbette, bu iyileştirmeler aynı zamanda masaüstü istemcisinin performansına yönelik gelecekteki iyileştirmeler için zemin hazırlar. & Lt; / p & gt;
& lt; p & gt; Lütfen & lt; a href = & quot; https: //github.com/quassel/quassel/blob/0.13.0/ChangeLog" & gt; tam ChangeLog & lt; / a & gt; daha ayrıntılı bir değişiklik listesi için. & lt; / p & gt;
& lt; p & gt; Yükseltmeden önce, lütfen hem veritabanı şemasının hem de yapılandırma dosyası biçimlerinin 0.12'den beri güncellendiğini unutmayın. Quassel, yeni sürüm ilk kez başlatıldığında her ikisini de otomatik olarak yükseltecektir, ancak & lt; strong & gt; geri dönüş mümkün değildir & lt; / strong & gt;, bu nedenle yeni sürüme başlamadan önce bir yedekleme yapın! Veritabanınız makul derecede büyükse (yetersiz) ve bu sırada çekirdek veya tekli istemcinin kullanılamadığı durumlarda yükseltme uzun sürebilir (birkaç saate kadar). Yükseltme ayrıca geçici olarak iki katına kadar disk alanı gerektirebilir. Yükseltme sürecini kesintiye uğratmayın, aksi takdirde veritabanınız bozulabilir! & Lt; / p & gt;
& lt; p & gt; Bunun dışında, lütfen & lt; a href = & quot; / downloads & quot; & gt; indirme sayfasına & lt; / a & gt; kendinize yeni bir Quassel tarball, Windows yükleyici veya OSX paketi edinin. Veya yeni sürüm size yakın bir dağıtıma ulaşana kadar bekleyin! Her zaman olduğu gibi, & lt; a href = & quot; https: //freenode.net/" & gt; Freenode IRC ağı & lt; / a & gt; Sorularınız varsa veya sadece dost canlısı topluluğumuzla konuşmak istiyorsanız. & lt; / p & gt;
& lt; p & gt; Son bir açıklama: Şimdi birkaç kez duyurduğumuz gibi, 0.13 yayın döngüsü, yıllardır ölü olan Qt4 ve KDE4 kitaplıklarını hala destekleyen son döngüdür. Ancak bu tek değişiklik değil; perde arkasında, kod tabanını modernize etmekle çok meşguldük ve 0.13'ü aştıktan kısa bir süre sonra devasa bir değişiklik yığınını ana dalda birleştireceğiz. Quassel ileride daha yeni bir araç zincirine ve sistem kitaplıklarına ihtiyaç duyacaktır; Şimdilik seçtiğimiz temel, Ubuntu 16.04 & quot; Xenial & quot; dir ve orada mevcut olandan daha eski sürümleri destekleme niyeti yoktur. Bunun çok fazla kullanıcıyı etkilemeyeceğini umuyoruz; üç yıldan daha eski bir kurulumu desteklemenin makul olduğunu düşünüyoruz,
& lt; p & gt; Tüm söylenenlerle birlikte, size güzel bir hafta sonu diliyorum ve yeni Quassel 0.13.0'ı beğeneceğinizi umuyorum! & lt; / p & gt;
& lt; p & gt; Şerefe, & lt; br / & gt;
• Sput & lt; / p & gt;
& lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/134" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <category domain = "https://quassel-irc.org/taxonomy/term/12"> duyuru </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/11"> paketleyiciler </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/7"> serbest bırak </category>
 <pubDate> Cts, 17 Kas 2018 19:30:36 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 134, https://quassel-irc.org </guid> adresinde
</item>
<item>
 <title> Son Uzatma - Quassel 0.13-rc2 </title>
 <link> https://quassel-irc.org/node/133 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
Yaklaşan 0.13 sürümü için ilk sürüm adayı & lt; p & gt; bazı sorunları ortaya çıkardı ve bunların düzeltilmesi bizim istediğimizden daha karmaşık değişiklikler gerektirdi. Bu nedenle, ikinci bir yayın adayı çıkarmaya karar verdik. & Lt; / p & gt;
& lt; p & gt; rc1 ile karşılaştırıldığında en önemli değişiklikler: & lt; / p & gt;
& lt; ul & gt;
& lt; li & gt; Kapatma sırasında her şeyi düzgün bir şekilde temizlemek için başlatma ve kapatma sırasını ve sinyal işlemeyi yeniden çalışın & lt; / li & gt;
& lt; li & gt; Normal ifadelerin işlenmesini yeniden çalışın, örneğin, daha fazla esneklik ve daha iyi performans için kuralları yok saymak ve vurgulamak için. Bu, eski kuralları görmezden gelme kurallarını ihlal edebilir; & lt; a href = & quot; https: //bugs.quassel-irc.org/projects/quassel-irc/wiki/Pattern_matching#Migrating-to-Quassel-013" & gt; geçiş kılavuzu & lt; / a & gt; daha fazla bilgi için & lt; / li & gt;
& lt; / ul & gt;
& lt; p & gt; Lütfen & lt; a href = & quot; https: //github.com/quassel/quassel/blob/0.13-rc2/ChangeLog" & gt; güncellenmiş ChangeLog & lt; / a & gt; daha fazlası için. Elbette, 0.13-rc1 & lt; / a & gt; için & lt; a href = & quot; / node / 132 & quot; & gt; yayın duyurusunda bahsedilen bilgiler ve uyarılar; hala geçerlidir. & lt; / p & gt;
& lt; p & gt; Lütfen & lt; a href = & quot; / indirmeler & quot; & gt; indirilenler sayfasına & lt; / a & gt; paketleri almak için veya sadece burayı tıklayın: & lt; / p & gt;
& lt; ul & gt;
& lt; li & gt; & lt; a href = & quot; /pub/quassel-0.13-rc2.tar.bz2" & gt; Kaynak tarball & lt; / a & gt; & lt; / li & gt;
& lt; li & gt; OSX & lt; a href = & quot; /pub/QuasselCore_MacOSX-x86_64_0.13-rc2.dmg" & gt; core & lt; / a & gt ;, & lt; a href = & quot; /pub/QuasselClient_MacOSX-x86_64 .dmg & quot; & gt; bağımsız istemci & lt; / a & gt ;, & lt; a href = & quot; /pub/QuasselCore_MacOSX-x86_64_0.13-rc2.dmg" & gt; monolitik istemci & lt; / a & gt; & lt; & lt; / li & gt;
& lt; li & gt; Windows yükleyici (& lt; a href = & quot; /pub/quassel-x86-setup-0.13-rc2.exe" & gt; 32 bit & lt; / a & gt ;, & lt; a href = & quot; / pub / quassel- x64-setup-0.13-rc2.exe & quot; & gt; 64 bit & lt; / a & gt;) çekirdek, istemci ve bağımsız istemciyi içerir
& lt; / li & gt; & lt; / ul & gt;
& lt; p & gt; Son bir 0.13.0 sürümünü, başka bir gecikmeyi gerektirecek ciddi sorunların keşfedilmesini bekleyerek yalnızca birkaç gün içinde yapmayı umuyoruz. & lt; / p & gt;
& lt; p & gt; Şerefe, & lt; br / & gt;
• Sput & lt; / p & gt;
& lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/133" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <category domain = "https://quassel-irc.org/taxonomy/term/12"> duyuru </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/11"> paketleyiciler </category>
 <pubDate> Paz, 28 Ekim 2018 23:52:00 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 133, https://quassel-irc.org </guid> adresinde
</item>
<item>
 <title> Yapım Aşamasında Uzun Bir Aday - Quassel 0.13-rc1 </title>
 <link> https://quassel-irc.org/node/132 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
& lt; p & gt; 0.12.0'ın piyasaya sürülmesinden bu yana üç yıldan fazla bir süredir ve mevcut kararlı dalda yapılan işlemlerin yanı sıra 500'den fazla taahhütte, nihayet bir sonraki büyük özellik sürümünün son aşamasındayız! & lt; / p & gt;
& lt; p & gt; Çok fazla çalışma ve & lt; a href = & quot; https: //github.com/quassel/quassel/blob/0.13-rc1/ChangeLog#L16" & gt; değişiklikler & lt; / a & gt; bu konuyu ele aldık, bu sefer yalnızca bir sürüm adayı çıkarmaya değil, aynı zamanda bunu herkese duyurmaya karar verdik, böylece cüretkar insanlar son sürümden önce bir şeyleri test edebilir. & lt; / p & gt;
& lt; p & gt; Bazı uyarılar önceden: Hem veritabanı şeması hem de yapılandırma dosyası biçimleri 0.12'den beri güncellenmiştir. Quassel, yeni sürüm ilk kez başlatıldığında her ikisini de otomatik olarak yükseltecektir, ancak & lt; strong & gt; geri dönüş mümkün değildir & lt; / strong & gt;, bu nedenle bir yedekleme yapın! Ayrıca, yükseltme & lt; em & gt; uzun & lt; / em & gt; Veritabanınız makul derecede büyükse (birkaç saat), bu sırada çekirdek veya tekli istemcinin kullanılamaması. Yükseltme ayrıca geçici olarak iki katına kadar disk alanı gerektirebilir. Yükseltme sürecini kesintiye uğratmayın, aksi takdirde veritabanınız bozulabilir! & Lt; / p & gt;
& lt; p & gt; Bununla birlikte, uzak çekirdekler ve istemciler arasındaki Quassel protokolü, 2009'da piyasaya sürülen 0.5.0'a kadar geriye dönük olarak hala uyumludur. sürümler, işler hala çalışıyor ve her iki ucu aynı anda yükseltmeye gerek yok. & lt; / p & gt;
& lt; p & gt; Bu aynı zamanda çevirmenler için & lt; güçlü & gt; bir çağrıdır & lt; / strong & gt; Quassel'in kendi dilinizde yerelleştirilmesini iyileştirmek istiyorsanız, lütfen & lt; a href = & quot; https: //www.transifex.com/quassel/quassel/" & gt; Transifex & lt; / a & gt ; ve katkıda bulunun. 0.13.0'ın son sürümünden kısa bir süre önce güncellenmiş çevirileri tekrar birleştireceğiz. & Lt; / p & gt;
& lt; p & gt; Bu sürümde tümünü listeleyebilmek için çok fazla değişiklik yapıldı (& lt; a href = & quot; https: //github.com/quassel/quassel/blob/0.13-rc1/ChangeLog Makul bir genel bakış için # L16 & quot; & gt; ChangeLog & lt; / a & gt;), ancak bazı önemli noktalar şunlardır: & lt; / p & gt;
& lt; ul & gt;
& lt; li & gt; Yeni markalama, daha modern simgeler (Breeze simge temasından) & lt; / li & gt;
& lt; li & gt; Simge temaları için daha iyi destek & lt; / li & gt;
& lt; li & gt; Birçok kullanıcı arayüzü iyileştirmesi & lt; / li & gt;
& lt; li & gt; Modern biçimlendirme kodlarının görüntülenmesi de dahil olmak üzere birçok IRCv3 özelliği için destek & lt; / li & gt;
& lt; li & gt; Öne çıkanlar ve sohbet etkinliği izleme gibi işlevler, & lt; a href = & quot; https: //quasseldroid.info/" & gt; mobil istemciler & lt; / a & gt; daha verimli olmak & lt; / li & gt;
& lt; li & gt; Kapsayıcıya alma desteği, yani yapılandırmasız çekirdek & lt; / li & gt;
& lt; li & gt; LDAP aracılığıyla isteğe bağlı kimlik doğrulama & lt; / li & gt;
& lt; li & gt; 64 bit kimlikler ve zaman damgaları desteği ve performans ayarlamaları dahil olmak üzere veritabanı iyileştirmeleri & lt; / li & gt;
& lt; li & gt; ... ve çok daha fazlası! & lt; / li & gt;
& lt; / ul & gt;
& lt; p & gt; Normal paketler şimdi indirilebilir: & lt; / p & gt;
& lt; ul & gt;
& lt; li & gt; & lt; a href = & quot; /pub/quassel-0.13-rc1.tar.bz2" & gt; Kaynak tarball & lt; / a & gt; & lt; / li & gt;
& lt; li & gt; OSX & lt; a href = & quot; /pub/QuasselCore_MacOSX-x86_64_0.13-rc1.dmg" & gt; core & lt; / a & gt ;, & lt; a href = & quot; /pub/QuasselClient_MacOSX-x86_64 .dmg & quot; & gt; bağımsız istemci & lt; / a & gt ;, & lt; a href = & quot; /pub/QuasselCore_MacOSX-x86_64_0.13-rc1.dmg" & gt; monolitik istemci & lt; / a & gt; & lt; & lt; / li & gt;
& lt; li & gt; Windows yükleyici (& lt; a href = & quot; /pub/quassel-x86-setup-0.13-rc1.exe" & gt; 32 bit & lt; / a & gt ;, & lt; a href = & quot; / pub / quassel- x64-setup-0.13-rc1.exe & quot; & gt; 64 bit & lt; / a & gt;) çekirdek, istemci ve bağımsız istemciyi içerir
& lt; / li & gt; & lt; / ul & gt;
& lt; p & gt; Sahte statik çekirdeği bırakıyoruz, çünkü çoğu platformda çalışan statik ikili dosyalar oluşturmak giderek daha kırılgan hale geliyor; OpenSSL gibi şeyleri bir araya getirmek, paketlenmiş sürüm sistemle birlikte güncellenmeyeceğinden güvenlik risklerini de beraberinde getirir. Ek olarak, OSX ve Windows için ikili paketlerimiz, derleme ortamlarımızdaki sınırlamalar ve talep eksikliği nedeniyle çekirdek için PostgreSQL veritabanı arka ucunu desteklemez. & Lt; / p & gt;
& lt; p & gt; Sorunlar veya gerilemelerle karşılaşırsanız bize bildirin. Aksi takdirde, önümüzdeki haftalarda son bir sürüm çıkmasını bekliyoruz! & Lt; / p & gt;
& lt; p & gt; & lt; strong & gt; NOT: & lt; / strong & gt; Daha önce birkaç kez duyurulduğu üzere, 0.13.0, Qt4 ve KDE4'ü destekleyen son özellik sürümü olacak. Kod tabanını modernize edebilmek için gelecekteki sürümler için derleme ve çalışma zamanı gereksinimlerini önemli ölçüde artıracağız. 0.14 sonrası için planlanan taban çizgisi Ubuntu 16.04 "Xenial" ve OSX ve Windows için son zamanlardaki makul araç zincirleridir. & Lt; / p & gt;
& lt; p & gt; İşte & # 039; şimdilik bu kadar! & lt; / p & gt;
& lt; p & gt; Her zaman sizin, & lt; br / & gt;
• Sput & lt; / p & gt;
& lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/132" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <category domain = "https://quassel-irc.org/taxonomy/term/12"> duyuru </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/11"> paketleyiciler </category>
 <pubDate> 25 Temmuz 2018 Çar 17:07:44 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 132, https://quassel-irc.org </guid> adresinde
</item>
<item>
 <title> İki Yıl !? - Quassel 0.12.5 </title>
 <link> https://quassel-irc.org/node/130 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
& lt; p & gt; evet, 0.12.4 etiketlendiğinden bu yana bugün tam olarak iki yıl geçti… Geliştirme hızı yakın zamanda tekrar artmış olsa da (çoğunlukla bazı çok aktif yeni ve eski katılımcılar sayesinde ve yalnızca küçük bir dereceye kadar Kendim sayemde) ve 0.12 ayrıldığından beri ana geliştirme dalına birkaç yüz kaydetme eklendi, yeni bir özellik sürümünden hala birkaç hafta uzaktayız. & lt; / p & gt;
& lt; p & gt; Ancak, & lt; a href = & quot; https: //twitter.com/chaign_c/" & gt; chaign_c & lt; / a & gt; yakın zamanda 0.12.4 çekirdeğinde iki güvenlik açığı keşfetti, bu nedenle & lt; a href = & quot; /pub/quassel-0.12.5.tar.bz2" & gt; yeni bir bakım sürümü & lt; / a & gt; garantilidir (ve 0.12.4 çekirdeğin derhal yükseltilmesi şiddetle tavsiye edilir!). Son sürümden bu yana çok uzun zaman geçtiği için, zamanınıza değer bir yükseltmeye değecek şekilde yüzlerce işlem değerinde hata düzeltmesi ve yaşam kalitesi iyileştirmelerini desteklemeye karar verdik. Quassel 0.12.5'i & lt; a href = & quot; / indirmeler & quot; & gt; indirmeler sayfasından & lt; a & gt;! & Lt; / a & gt; & lt; / a & gt; & lt; / p & gt;
& lt; p & gt; Her zamanki politikamızı izleyerek, önceki 0.12.x sürümlerine kıyasla yapılandırma dosyası biçimini veya veritabanı şemasını değiştirmedik ve dize ve kullanıcı arayüzü değişikliklerinden kaçındık. Bu nedenle, yükseltme güvenli olmalı ve herhangi bir şey ters giderse önceki 0.12.x sürümüne geri dönmek mümkündür. Lütfen & lt; a href = & quot; https: //github.com/quassel/quassel/blob/0.12.5/ChangeLog#L16" & gt; ChangeLog & lt; / a & gt; bu sürüme giren önemli şeylerin listesi için veya & lt; a href = & quot; https: //github.com/quassel/quassel/compare/0.12.4...0.12.5" & gt; full kaydetme listesi & lt; / a & gt; son sürümden beri. & lt; / p & gt;
& lt; p & gt; Bu fırsatı, ister çekme talepleri, topluluk desteği, çeviriler, testler sunarak veya sadece aktif olarak çalışarak, Quassel'i kendi zamanım eksikliğine rağmen canlı tutan ve tekmeleyen tüm katılımcılara teşekkür etmek için kullanmak istiyorum IRC kanallarımız. Bu sürüm için, & lt; a href = & quot; https: //github.com/justjanne" & gt; Janne & quot; justJanne & quot; 'e özellikle teşekkür etmek istiyorum. Koschinski & lt; / a & gt ;, & lt; a href = & quot; https: //github.com/mamarley" & gt; Michael & quot; mamarley & quot; Marley & lt; / a & gt; ve & lt; a href = & quot; https: //github.com/digitalcircuit" & gt; Shane & quot; digitalcircuit & quot; Synan & lt; / a & gt; yukarıda belirtilen güvenlik açıklarının bu kadar profesyonelce ele alınmasında zamanında destek verdikleri için, hem düzeltmeler hem de çok kapsamlı testler sağlıyor! Harikasınız! & Lt; / p & gt;
& lt; p & gt; Sonraki durak (umarız): Quassel 0.13. İki yıl önce duyurulduğu gibi, bu, Qt 4 ve KDE 4'ü destekleyen son sürümümüz olacak. Daha sonra, derleme gereksinimlerimizi de önemli ölçüde karşılayacağız. & Lt; / p & gt;
& lt; p & gt; O zamana kadar, en iyisi, & lt; br / & gt;
• Sput & lt; / p & gt;
& lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/130" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <category domain = "https://quassel-irc.org/taxonomy/term/12"> duyuru </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/11"> paketleyiciler </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/7"> serbest bırak </category>
 <pubDate> 24 Nisan 2018 Salı 21:28:42 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 130, https://quassel-irc.org </guid>
</item>
<item>
 <title> Hataları Düzeltme - Quassel 0.12.4 </title>
 <link> https://quassel-irc.org/node/129 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
& lt; p & gt; özellik geliştirme hala yavaş olsa da - kendi zevkime göre çok yavaş, gerçekten, ama ne yapabilirsiniz - başka bir bakım sürümünü garanti eden oldukça can sıkıcı hatalar düzeltildi. En önemlisi, Tucos (çok teşekkürler!), Geçersiz el sıkışma verilerinin çekirdeğin çökmesine neden olabileceğini anladı. Bir diğer can sıkıcı sorun, bazı IRC ağlarında bulunan STATUSMSG özelliği için destek eksikliğiydi. Bu, kısa süre önce idio ^ Wpeople tarafından bazı kullanıcılarımız için tonlarca spam sorgusu açmak amacıyla kötüye kullanıldı. & Lt; / p & gt;
& lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/129" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <category domain = "https://quassel-irc.org/taxonomy/term/12"> duyuru </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/11"> paketleyiciler </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/7"> serbest bırak </category>
 <pubDate> 17 Mayıs 2016 Salı 20:47:07 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 129, https://quassel-irc.org </guid> adresinde
</item>
<item>
 <title> Long Time No See - Quassel 0.12.3 </title>
 <link> https://quassel-irc.org/node/128 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
& lt; p & gt; bir süredir & lt; a href = & quot; /pub/quassel-0.12.3.tar.bz2" & gt; yeni bir sürüm & lt; / a & gt; ve & # 039; hala & quot; sadece & quot; bu sefer bir hata düzeltme sürümü. Gerçek hayatın bizi hala meşgul ettiği ortaya çıktı ... ama bu iyi bir meşgul, bu yüzden orada & # 039; Neyse ki, çekirdek geliştirme ekibi yarı yarıda iken, toplulukta yamalara, düzeltmelere ve özelliklere katkıda bulunan bir grup havalı insanımız var - hepinize çok teşekkürler! & Lt; / p & gt;
& lt; p & gt; Her neyse, & lt; a & gt; Quassel 0.12.3 & lt; / a & gt; 'ye merhaba deyin. Bunda birçok düzeltme yapıldı ve sizi yükseltmenizi öneririz! Özellikle kötü bir hata düzeltildi: Tek bir Quassel Core üzerinde birden fazla kullanıcınız varsa ve veritabanı arka ucu olarak PostgresQL kullanıyorsanız, önceki 0.12.x sürümlerinde mesajlar kaybolabilirdi. Dolayısıyla, 0.12. {0..2} çalıştırırsanız ve birden çok kullanıcı için bir çekirdek çalıştırırsanız, kesinlikle yükseltmelisiniz. Daha kapsamlı bir düzeltme listesi & lt; a href = & quot; https: //github.com/quassel/quassel/blob/0.12.3/ChangeLog" & gt; ChangeLog & lt; / a & gt; & lt; / p & gt; adresinde bulunabilir. ;
& lt; p & gt; Kısa bir uyarı: Bir sonraki özellik sürümü (0.13.x), hala Qt 4'ü ve dolayısıyla KDE 4'ü destekleyen son sürüm olacak. farklı masaüstü ortamları (KDE 4 ve Plasma 5) giderek daha zorlu hale geliyor. Ek olarak, Qt 4 resmi olarak şimdiye kadar kullanım ömrünün sonuna ulaştı. Dolayısıyla, 0.13 yayınlandıktan sonra, kod tabanını temizleme ve birkaç yüz #ifdef, sarmalayıcı ve geçici çözümü kaldırma fırsatını değerlendireceğiz! Bu hala birkaç ay uzakta ve bir sonraki sürüme uzun süredir arzu edilen bir veya iki özelliği eklemeyi planlıyoruz - ancak artık biliyorsunuz ve Qt 4'ten sonraki hayata hazırlanabilirsiniz! & Lt; / p & gt;
& lt; p & gt; İşte & # 039; bugünlük bu kadar. Lütfen & lt; a href = & quot; / indirmeler & quot; & gt; indirmeler sayfasına & lt; / a & gt; gidin yeni kaynak tarball'unu kapmak için. Çeşitli platformlar için ikili paketler önümüzdeki birkaç gün içinde orada görünecek ve Linux çalıştırırsanız, eminim ki dost canlısı paket bakımcınız yakında yakınınızda güncellenmiş bir paket almak için çalışıyor! & Lt; / p & gt;
& lt; p & gt; İyi günler! & lt; br / & gt;
• Sput & lt; / p & gt;
& lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/128" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <category domain = "https://quassel-irc.org/taxonomy/term/12"> duyuru </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/11"> paketleyiciler </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/7"> serbest bırak </category>
 <pubDate> 10 Şubat 2016, Çarşamba 20:59:58 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 128, https://quassel-irc.org </guid>
</item>
<item>
 <title> Engebeli Bir Yol - Quassel 0.12.2! </title>
 <link> https://quassel-irc.org/node/127 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
& lt; p & gt; Quassel IRC 0.12.2 sürümünün yayınlandığını duyurmaktan mutluluk duyuyorum! Bu sürüm artık KDE Çerçevelerini tam olarak desteklediğinden Quassel, Plazma 5 ortamında düzgün davranır. Diğer yeni özellikler arasında iyileştirilmiş bir parola karma algoritması, hem normal hem de CTCP mesajları için uygun unicode duyarlı mesaj bölme, PostgreSQL veritabanı bağlantılarının iyileştirilmiş kullanımı, bir dizi hata düzeltmesi ve güncellenmiş çeviriler yer alıyor. 0.12.x çekirdeğine bağlanırsanız, artık çekirdek şifrenizi istemciden de değiştirebilirsiniz. Lütfen & lt; a href = & quot; http: //git.quassel-irc.org/? P = quassel.git; a = blob; f = ChangeLog; h = 244824f03e443c1b73c8add0aee446ddd6ca9780; & lt ;03e6c666d5faa976eec2 & lt; a & gt; daha eksiksiz bir liste için. & lt; / p & gt;
& lt; p & gt; Şimdi sorabilirsiniz: 0.12.0 ve 0.12.1'e ne oldu? Bu yazıyı & quot; Engebeli Bir Yol & quot; olarak adlandırmamın nedeni budur. 0.12.0 sürümünü etiketledikten çok kısa bir süre sonra, PostgreSQL veritabanlarında saat dilimi işleme açısından Qt5'te bir davranış değişikliği keşfettik. Bu, bazı sunucu kurulumları için bekleme listesi mesajlarının yanlış saat dilimi bilgileriyle depolanmasına neden oldu. Bunun düzeltmesi 0.12.1 sürümüne gitti. Ne yazık ki, bu düzeltme aynı zamanda uzun süredir var olan daha ciddi bir sorunu da ortaya çıkardı: Quassel Core çalışırken bir PostgreSQL veritabanını yeniden başlatmak, Quassel içindeki veritabanı oturumunu düzgün şekilde yeniden başlatmayarak eski bir & lt; a href = & quot ; http: //cve.mitre.org/cgi-bin/cvename.cgi? name = CVE-2013-4422 & quot; & gt; güvenlik sorunu & lt; / a & gt; sabit olduğunu düşündüğümüz. Bu da bizi başka bir sürüm oluşturmaya zorladı, bu yüzden artık 0.12.2 sürümündeyiz. Yeni sorun & lt; a href = & quot; https: //marc.info/? L = oss-security & amp; amp; m = 143014582328491 & amp; w = 2 & quot; & gt; CVE-2015-3427 & lt; / olarak izleniyor a & gt ;. Bunu kaydettirdiği için Pierre Schweitzer'e teşekkürler! & Lt; / p & gt;
& lt; p & gt; Açık olmak gerekirse: & lt; em & gt; Eski sürümlerdeki güvenlik açıkları nedeniyle Quassel'i 0.12.2'ye yükseltmenizi veya ilgili CVE girişlerinde atıfta bulunulan yamaları geri aktarmanızı şiddetle tavsiye ediyoruz! & lt; / em & gt; Ayrıca bir & lt; a href = & quot; http: //quassel-irc.org/pub/quassel-0.11.1.tar.bz2" & gt; 0.11.1 sürümü & lt; / a & gt; güvenlik düzeltmelerini içeren ancak yeni özellikler içermeyen. Daha eski sürümler artık desteklenmemektedir. & Lt; / p & gt;
& lt; p & gt; Bunun dışında, Quassel'in yeni sürümünü beğeneceğinizi umuyoruz! & Lt; a href = & quot; / indirmeler & quot; & gt; indirmeler sayfamıza & lt; / a & gt; gidin kapmak için veya favori dağıtımınızın paketleri sağlamasını bekleyin! & lt; / p & gt;
& lt; p & gt; Şerefe, & lt; br / & gt;
• Quassel Ekibi adına Sputnick & lt; / p & gt;
& lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/127" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <pubDate> 01 Mayıs 2015, Cum 13:17:32 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 127, https://quassel-irc.org </guid>
</item>
<item>
 <title> Yeni Tatlılar - Quassel 0.11.0 </title>
 <link> https://quassel-irc.org/node/126 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
& lt; p & gt; Başka bir Quassel sürümü & lt; / a & gt; & lt; a href = & quot; / downloads & quot; & gt; için yine yılın o zamanı! 0.11.0 için, esas olarak Qt 5.2+ için tam desteğe odaklandık (şimdilik birlikte desteklenecek olan Qt 4.6+ 'e ek olarak). Qt 4.x bir süredir çok fazla geliştirme görmediğinden ve ardından Qt geliştiricileri tarafından yapılan birçok işi kaçırdığımız için, bu özellikle Windows ve Mac kullanıcılarımız için büyük bir gelişmeye işaret ediyor OSX. Her iki platform için destek, Qt 5'te birçok iyileştirme gördü ve bu nedenle & lt; a href = & quot; / downloads & quot; & gt; resmi paketlerimiz & lt; / a & gt; bu platformlar artık Qt 5'e karşı oluşturulmuştur. Özellikle Mac kullanıcıları artık çok daha mutlu olmalı! & lt; / p & gt;
& lt; p & gt; KDE kullanıcıları için, Qt 4'e karşı oluşturulan Quassel'i kullanmaya devam etmeleri önerilir, çünkü KDE entegrasyon desteği henüz yeni KDE Çerçevelerine taşınmamıştır. Bu, Quassel 0.12 için planladığımız bir şey, bu yüzden bizi izlemeye devam edin! & Lt; / p & gt;
& lt; p & gt; Dual-Qt desteğini kolaylaştırmak için inşa sistemini tamamen yeniledik, bu çoktan gecikti. Mevcut yapı sistemi hala karanlık CMake 2.6 çağından geliyordu ve bakımı gittikçe zorlaşıyordu. Yani şimdi her şey yeni CMake özellikleri dikkate alınarak yeniden yazıldı. Sonuç olarak bazı yapı seçenekleri değişti; özellikle, artık CMake tanımları yerine isteğe bağlı bağımlılıkları bulmak için paket özelliklerini kullanıyoruz. Yapıyı yapılandırdıktan sonra CMake, belirli bir bağımlılığın ne yaptığı ve nerede bulacağıyla ilgili bilgilerin yanı sıra bulunabilen veya bulunamayan gerekli ve isteğe bağlı paketlerin bir özetini çıkaracaktır. & Lt; a href = & quot; http: //git.quassel-irc.org/? P = quassel.git; a = blob; f = INSTALL; h = a9dc9e2b3762f09c08761550cc03812099ac1768; hb = HEAD & quot; & gt; YÜKLE & lt; / a & gt;
& lt; p & gt; 0.11'den başlayarak, derleme gereksinimlerini de artırdık. Quassel'i kaynaktan derlemek için artık gcc 4.7+, Clang 3.1+ veya Visual Studio 2013 (en azından Kasım CTP'si) gibi C ++ 11 uyumlu bir derleyiciye ihtiyaç vardır. Ek olarak, en az CMake 2.8.9 gereklidir. Bunların, mevcut dağıtımların çoğu tarafından desteklenmesi gereken makul gereksinimler olduğunu düşünüyoruz (ve sorduğumuzda herhangi bir itiraz olmadı). & Lt; / p & gt;
& lt; p & gt; Bu büyük değişikliklerin yanı sıra, bu sürüm, en cömertçe harika topluluğumuz tarafından sağlanan bir dizi hata düzeltmesi de içeriyor. Diğer şeylerin yanı sıra, veritabanı hatalarının işlenmesi iyileştirildi, artık çok uzun olan CTCP satırlarını böldük (bana / beni çok kullanan rol oyuncuları için önemli, söyledim) ve QuasselDroid ile ilgili bazı sorunlar düzeltildi. Sistem değişikliklerini, Qt 5 desteğini ve artan yapı gereksinimlerini değil, yalnızca bu düzeltmeleri almak isteyenler için & lt; a href = & quot; /pub/quassel-0.10.1.tar.bz2" etiketini ekledik. ; & gt; Quassel 0.10.1 & lt; / a & gt ;. Bu hata düzeltme sürümü, 0.10.x sürümlerinin sonunu işaret ediyor; bu dal için daha fazla destek sağlamayacağız (her zamanki gibi). & lt; / p & gt;
& lt; p & gt; Ve şimdi, dost paket bakıcınız bu işi sizin için halihazırda yapmadıysa indirin! & lt; / p & gt;
& lt; p & gt; Şerefe, & lt; br / & gt;
• Sput & lt; / p & gt;
& lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/126" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <category domain = "https://quassel-irc.org/taxonomy/term/12"> duyuru </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/11"> paketleyiciler </category>
 <category domain = "https://quassel-irc.org/taxonomy/term/7"> serbest bırak </category>
 <pubDate> 06 Ekim 2014, Pzt 18:10:41 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 126, https://quassel-irc.org </guid>
</item>
<item>
 <title> Kanayan Bir Kalp </title>
 <link> https://quassel-irc.org/node/125 </link>
 <description> & lt; p & gt; Merhabalar, & lt; / p & gt;
& lt; p & gt; şimdiye kadar duymuş olmanız gerektiği gibi, bir & lt; a href = & quot; http: //heartbleed.com/" & gt; büyük bir güvenlik açığı & lt; / a & gt; OpenSSL'de keşfedildi. Quassel istemcisi ile çekirdek arasındaki bağlantı varsayılan olarak SSL (veya daha doğrusu TLS) kullanılarak şifrelenmiş olduğundan, bu Quassel'i de etkiler; özellikle, SSL'yi destekleyen ve genel internete maruz kalan bir çekirdek çalıştırırsanız sizi etkiler (hem monolitik hem de bağımsız istemciler, SSL şifreli bir hizmet sunmadıkları için etkilenmezler). & lt ; / p & gt;
& lt; ul & gt;
& lt; / ul & gt; & lt; p & gt; & lt; a href = & quot; https: //quassel-irc.org/node/125" target = & quot; _blank & quot; & gt; daha fazlasını okuyun & lt; / a & gt; & lt; / p & gt; </description>
 <pubDate> Çarşamba, 09 Nisan 2014 21:11:50 +0000 </pubDate>
 <dc: creator> Sputnick </ dc: creator>
 <guid isPermaLink = "false"> 125, https://quassel-irc.org </guid>
</item>
</channel>
</rss>
