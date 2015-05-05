# logoxnet
Logoxnet-Engelsiz İnternet!
Proje Sayfası: https://code.google.com/p/logoxnet/

Twitter Adresi: https://twitter.com/logoxnet

Facebook Adresi: https://www.facebook.com/logoxnet

Bağış yapıp projenin geliştirilmesinde katkıda bulunabilirsiniz.

logoxnetv1.0.0.6.rar şifresi (günlük): 1523ad616b76a20f70556edc901c6261

Sürüm No / Tarih / Açıklama : 1.0.0.6 / 23.03.2015 / Sertifika Güncellemesi.

Sürüm No / Tarih / Açıklama : 1.0.0.5 / 10.02.2015 / Sertifika Güncellemesi.

Sürüm No / Tarih / Açıklama : 1.0.0.4 / 09.01.2015 / Sertifika Güncellemesi. Bir kaç hata giderildi. Hız optimizasyonu yapıldı.

Sürüm No / Tarih / Açıklama : 1.0.0.3 / 20.12.2014 / Sertifika Güncellemesi. Bir kaç hata giderildi.

Sürüm No / Tarih / Açıklama : 1.0.0.2 / 11.12.2014 / Sertifika Güncellemesi.

Sürüm No / Tarih / Açıklama : 1.0.0.1 / 24.11.2014 / Tray Menu iyileştirmeleri yapıldı, bazı sistemlerde refresh yapamama durumu giderildi. Hız odaklı bir kaç performans optimizasyonu.

Öncelikle herkese merhaba... 

Logoxnet esasında yarım kalmış bir projeydi. Bir çok problemi gidermenin yolu olarak Chromium projesi ile birleştirilerek Logoxnet Browser adı altında https://code.google.com/p/logoxnet yayınlamıştık. Çalışır halde bırakılmış, hatta kurulum profili bile hazırlanmamıştı. "Logoxnet Browser" bir çok açıdan sorunları giderilmiş olmasına rağmen ekosistem olarak daha kapalı bir yapıya sahipti. Güncellenmesi gereken bileşenleri zaman içerisinde oldukça birikmişti.

Kullanımı:
Video
* System tray'a yerleşecek olan yazılımı sol tık ile "Start/Refresh" yazısını tıklayarak başlatabilir/yenileyebilir "Stop" ile durdurabilirsiniz. Bağlantı hızından memnun kalmadığınız durumlarda "Start/Refresh" yazısını tekrar tıklamak bağlantının yenilenmesini sağlar.

* Internet Explorer'da Ayarlar>İnternet Seçenekleri>Bağlantılar (sekmesi)>Yerel Ağ Ayarları>Ara Sunucu bölgesine ip: 127.0.0.1 port:8087 yazılır.

Ayrıca;
Yazılımdan "Exit" ile çıkış yaptıktan sonra yapılan bu değişikliği geri almayı unutmayın. Bunu otomatize eden fonksiyonu yazılıma dahil etmedim. Kullanmanızı tavsiye ettiğim yöntem başka. Tarayıcılar için proxy yönetim eklentileri bu iş için biçilmiş kaftan. Onları kullanmak daha fonksiyonel ve pratik.

* Chrome kullanıcıları için de yöntem üstteki gibi.

* Firefox kullanıcıları için yapılması gereken ayrı bir işlem var, Logoxnet kök sertifika yükleme işlemi. Bu işlemi manuel olarak yapacağız. Proje sayfamızdan ilgili dosyayı indirdikten sonra Firefox>Seçenekler>Gelişmiş>Sertikalar(Sekme)>"Sertifikalar'ı Göster" e basıyoruz.
Yetkili(Sekme) gelip "İçe Aktar" a basıyoruz. Açılan pencerede kök sertifikamızı (CA.crt) seçiyoruz.
Uyarı penceresinde yer alan Siteleri tanımlamak için bu sertifika yetkilisine güven. kutucuğunu işaretledikten sonra "Tamam" deyip onaylıyoruz. Bu aşamadan sonra Logoxnet'i Mozilla Firefox'unuzla birlikte kullanabilirsiniz. Video

* Erişim problemlerine karşı kök sertifikalar belirli periyotlarda güncellenecektir. Logoxnet'in çalışılabilirliği büyük ölçüde bu kök sertifikasına bağlı. Kök sertifikası Logoxnet yazılımının içinde internet explorer'a (aslında sisteme) otomatik olarak yüklenmektedir. Mozilla Firefox ise kendi kök sertifikalarını kendi yönetmektedir. Logoxnet yazılım olarak güncel olsa dahi bu kök sertifikasının güncelleştirilmiş haline ihtiyaç var. Paket olarak Logoxnet'i tekrar indirmek durumunda kalabilirsiniz. (Mozilla Firefox kullanıcıları da Logoxnet ile birlikte harici kök sertifikasını tekrar indirip yüklemeliler.)

* İçerisinde zararlı, bulaşan, bilgi sızdıran bir bileşen yoktur. İnternet trafiğini çok iyi analiz eden yazılımlarla göz atabilirsiniz. Avast "false positive" uyarı verip yazılımın çalışmasını engellemekte. Avast'ı kapatıp yazılımı çalıştırabilirsiniz.

* XP kullanıyorsanız, TCP/IP eş zamanlı bağlantı sayınızı 10'dan 255'e yükseltmeniz performansınıza artı katkı sağlayacaktır. Basit bir araç isterseniz, buradan.

* Eski projemiz "Logoxnet Browser" ile aynı dizinde çalıştırmak hatalara sebep verebilmekte. Aynı port kullanıldığı için aynı anda da iki yazılımı çalıştırmayın!

* Sonuçta bu bir aracı yazılım olduğu için bankacılık, e-devlet vb gibi yüksek güvenlik gerektiren yerler için kullanmanız önerilmez.

* Ayrıca belirtmekte fayda var, kurumunuzun güvenlik kapsamında kullandığı profili aşmak sizin sorumluluğunuz altındadır.

* Önümüzdeki zaman zarfında her zaman olduğu gibi BugFix'ler gelecektir.

* Aklıma geldikçe ve sizlerin geri dönüşleri sayesinde buraya ekleyeceklerim olacaktır. Arada bu iletiyi okumanız nelerin değiştiği konusunda size yardımcı olabilir.
