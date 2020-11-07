## Git ve Github Nedir?

Bu satırları okuduğuna göre muhtemelen kendine “her yerde karşıma çıkıyor bu git. Ne acaba?” diye soruyorsundur. Kafandaki bu soruları gidermek amacıyla elimden geldiğince git ve github nedir? anlatayacağım.

Günlük hayatının önemli bir kısmını yazılım ile geçirenler belli bir zaman sonra yazmış olduğu kodların içerisinde boğulmaya başlar. Bu kadar kodları bir arada tutabilsek ve ihtiyacımız olduğu anda istediğimiz yerden doğruca kodlarımıza ulaşabilsek aslında ne güzel olurdu değil mi? İşte bu noktada git, bize bu olanakları sağlayan bir yapı sunuyor. Peki tam olarak git ne demek?

Öncelikle isterseniz wikipedia (özgür ansiklopedi)'nın git hakkında yapmış olduğu tanıma bir bakalım.

> Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, dağıtık çalışan bir sürüm kontrol ve kaynak kod yönetim sistemidir. İlk sürümü Linux çekirdeği'nin geliştirilmesinde kullanılmak üzere 2005 yılında bizzat Linus Torvalds tarafından tasarlanıp geliştirilmiş, son Eclipse kullanıcı topluluğu anketi verilerine göre 2013 yılı itibarıyla %30 pazar payına ulaşmıştır.[1]

> Git sürüm kontrol sistemini kullanan her bir çalışma dizini (proje), internet erişimi ya da merkezi bir depo olmaksızın tüm tarihçeyi tutan ve sürüm kontrol sisteminin tamamını içinde barındıran tam yetkili birer depodur. Ayni çalışma dizininin birçok depodan birindeki kopyasında yapılan değişiklikler diğerlerine güven temelli bir değerlendirmeyle kabul edilir; Güvenilmeyenden değişiklik alınmaz, o kendi ayrı sürümünü geliştirmeye devam eder.

> Git'in şu anki yazılım bakıcılığını Junio Hamano üstlenmiş durumda. Git, GNU Genel Kamu Lisansı'nın 2. sürümüyle lisanslanmış bir özgür yazılımdır.

tanımdan da anladığımız üzere aslında git, yazılım dünyasındaki gelişimleri takip edebilmek için en popüler versiyon kontrol sistemidir.

### Git bize ne gibi faydalar sunuyor?

Örneğin bir proje üzerinde geliştirme yapmaktasınız. Projede defarlarca kodlar yazılıyor. Her yazılan kod satırı belirli bir düzenlemelerden sonra güncellenerek tekrar yazıldığını düşünelim. Bizlerin bu kadar kod güncellemesini aklımızda tutmamızın olanağı yoktur. Bu yüzden git sayesinde daha önce yazmış olduğumuz kodlara erişebilmekteyiz.

Örneğin şu şekilde düşünelim. Arkadaşınız ile proje geliştirmek istediğinizde sizdeki kodları ona, ondaki kodları da sizin almanız, güncelleme yaparak tekrar bu işlemi gerçekleştirmeniz gerekecektir. Bilgisayarınızda muhtemelen şu şekilde dosyalar oluşacaktır; “ProjeYeni, ProjeEnYeni, ProjeSon,ProjeEnson” peki bunların arasında en yeni olan hangisidir? (: bu yüzden git üzerinde projemizin en güncel olan versiyonuna direkt ulaşabiliriz. Hal böyle olunca arkadaşımızın yazdığı kodları doğrudan görüp inceleme fırsatı yakalayabilir, hangi kodların değiştiğini de görebiliriz.

Bir ekip ile yürütülen projelerde her ekip geliştiricisinin kendi bilgisayarı içerisinde kurulumunu yapacağı git sayesinde yine her geliştiricinin kendine ait bir versiyon kontrol ağacı bulunur. Bizler kendi bilgisayarımızdaki kontrol sistemine doğrudan kodları gönderir, bazı noktalara geri döner, kodları değiştirir, değişiklikleri görüp, en güncel versiyonu da genel olarak tutulan bir git deposu(repository)’na göndeririz. Bu git deposu ise github olarak adlandırılmaktadır. 

### Bilmeniz gereken basit ve temel terimler

* *Clone*: Uzak bir depodan yerel depoya kopya alır.

* *Commit*: Yerel bir depoda yapmış olduğunuz değişiklikleri yorum mesajı ile kaydeder.

* *Checkout*: Versiyon ağacının dallarında geçiş yapar.

* *Pull*: Uzak bir depodan kendi yerel deponuza kodları çeker.

* *Push*: Uzak bir depoya yorum mesajı ile yapmış olduğunuz işlemleri gönderir.

