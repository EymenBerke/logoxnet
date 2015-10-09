# logoxnet
Logoxnet-Engelsiz İnternet!

(http://www.bilgisayarbilisim.net/network-ag-ve-internet-teknolojileri-f42/logoxnet-engelsiz-internet-t135665.html)

logoxnetv1.0.0.7 : http://bc.vc/3Lz8va veya http://bc.vc/u8CYHT  (1 haftalık, Süre Sonu: 11.10.2015)

Şifresi: 9cd627cb03a173f8c1a0ac866e75e2ab

Mozilla Firefox için root sertifika: http://bc.vc/H92yNe veya http://bc.vc/F6H49m

Şifresi: Şifre yoktur.

Not: logoxnetv1.0.0.7'nın çalışmadığı durumlarda (sertifika süre sonu) yeni sertifikalı paket burada yayınlanmış olacaktır. Takipte kalın.

Bağış yapıp projenin geliştirilmesinde katkıda bulunabilirsiniz. http://goo.gl/MwmF3c

-----------------------------------------------


Kullanımı: http://bc.vc/8suyQC

Firefox için sertifika yükleme: http://bc.vc/vLmDfw

Twitter Adresi: https://twitter.com/logoxnet

Facebook Adresi: https://www.facebook.com/logoxnet

-----------------------------------------------

Öncelikle herkese merhaba... 

Logoxnet esasında yarım kalmış bir projeydi. Bir çok problemi gidermenin yolu olarak Chromium projesi ile birleştirilerek Logoxnet Browser adı altında https://code.google.com/p/logoxnet yayınlamıştık. Çalışır halde bırakılmış, hatta kurulum profili bile hazırlanmamıştı. "Logoxnet Browser" bir çok açıdan sorunları giderilmiş olmasına rağmen ekosistem olarak daha kapalı bir yapıya sahipti. Güncellenmesi gereken bileşenleri zaman içerisinde oldukça birikmişti.

Kullanımı:

Video Anlatım: http://bc.vc/8suyQC
* System tray'a yerleşecek olan yazılımı sol tık ile "Start/Refresh" yazısını tıklayarak başlatabilir/yenileyebilir "Stop" ile durdurabilirsiniz. Bağlantı hızından memnun kalmadığınız durumlarda "Start/Refresh" yazısını tekrar tıklamak bağlantının yenilenmesini sağlar.

* Internet Explorer'da Ayarlar>İnternet Seçenekleri>Bağlantılar (sekmesi)>Yerel Ağ Ayarları>Ara Sunucu bölgesine ip: 127.0.0.1 port:8087 yazılır.

Ayrıca;
Yazılımdan "Exit" ile çıkış yaptıktan sonra yapılan bu değişikliği geri almayı unutmayın. Bunu otomatize eden fonksiyonu yazılıma dahil etmedim. Kullanmanızı tavsiye ettiğim yöntem başka. Tarayıcılar için proxy yönetim eklentileri bu iş için biçilmiş kaftan. Onları kullanmak daha fonksiyonel ve pratik.

* Chrome kullanıcıları için de yöntem üstteki gibi.

* Firefox kullanıcıları için yapılması gereken ayrı bir işlem var, Logoxnet kök sertifika yükleme işlemi. Bu işlemi manuel olarak yapacağız. Proje sayfamızdan ilgili dosyayı indirdikten sonra Firefox>Seçenekler>Gelişmiş>Sertikalar(Sekme)>"Sertifikalar'ı Göster" e basıyoruz.
Yetkili(Sekme) gelip "İçe Aktar" a basıyoruz. Açılan pencerede kök sertifikamızı (CA.crt) seçiyoruz.
Uyarı penceresinde yer alan Siteleri tanımlamak için bu sertifika yetkilisine güven. kutucuğunu işaretledikten sonra "Tamam" deyip onaylıyoruz. Bu aşamadan sonra Logoxnet'i Mozilla Firefox'unuzla birlikte kullanabilirsiniz.
Video Anlatım:http://bc.vc/vLmDfw

* Erişim problemlerine karşı kök sertifikalar belirli periyotlarda güncellenecektir. Logoxnet'in çalışılabilirliği büyük ölçüde bu kök sertifikasına bağlı. Kök sertifikası Logoxnet yazılımının içinde internet explorer'a (aslında sisteme) otomatik olarak yüklenmektedir. Mozilla Firefox ise kendi kök sertifikalarını kendi yönetmektedir. Logoxnet yazılım olarak güncel olsa dahi bu kök sertifikasının güncelleştirilmiş haline ihtiyaç var. Paket olarak Logoxnet'i tekrar indirmek durumunda kalabilirsiniz. (Mozilla Firefox kullanıcıları da Logoxnet ile birlikte harici kök sertifikasını tekrar indirip yüklemeliler.)

* İçerisinde zararlı, bulaşan, bilgi sızdıran bir bileşen yoktur. İnternet trafiğini çok iyi analiz eden yazılımlarla göz atabilirsiniz. Avast "false positive" uyarı verip yazılımın çalışmasını engellemekte. Avast'ı kapatıp yazılımı çalıştırabilirsiniz.

* XP kullanıyorsanız, TCP/IP eş zamanlı bağlantı sayınızı 10'dan 255'e yükseltmeniz (http://support.microsoft.com/kb/926646)  performansınıza artı katkı sağlayacaktır. Basit bir araç isterseniz, buradan.

* Eski projemiz "Logoxnet Browser" ile aynı dizinde çalıştırmak hatalara sebep verebilmekte. Aynı port kullanıldığı için aynı anda da iki yazılımı çalıştırmayın!

* Sonuçta bu bir aracı yazılım olduğu için bankacılık, e-devlet vb gibi yüksek güvenlik gerektiren yerler için kullanmanız önerilmez.

* Ayrıca belirtmekte fayda var, kurumunuzun güvenlik kapsamında kullandığı profili aşmak sizin sorumluluğunuz altındadır.

* Önümüzdeki zaman zarfında her zaman olduğu gibi BugFix'ler gelecektir.

* Aklıma geldikçe ve sizlerin geri dönüşleri sayesinde buraya ekleyeceklerim olacaktır. Arada bu iletiyi okumanız nelerin değiştiği konusunda size yardımcı olabilir.
