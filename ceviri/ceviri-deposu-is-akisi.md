---
layout: post
title: Çeviri Deposu İş Akışı
permalink: /ceviri/ceviri-deposu-is-akisi/
---

Bu belge, GNOME çevirilerine katılacaklar için iş akışının nasıl gerçekleşeceğini ve çevirilerle ilgili temel bilgileri sunmaktadır. Çevirilerin gönderimi ve denetimi için [Damned Lies](https://l10n.gnome.org/) istatistik aracı kullanılmaktadır. Damned Lies; çeviri durumlarını göstermekle birlikte çevirilerin saklanmasını, denetlenmesini ve iş akışını kolaylaştıran araçtır.

---

### GNOME çeviri sistemi

GNOME Projesi, uygulamaların yerelleştirmesine geniş olanaklar sağlayan Gettext sistemini kullanmaktadır. Bu sistem aracılığıyla uygulamalar, sistemin kendi dil ayarına göre uygun çevirilerle görüntülenir. Gettext sistemi, uygulamaların kaynak kodlarında çevrilmesi gereken dizgeleri ayrı bir dosyada (PO dosyası) saklar ve böylece uygulamaların kurulumu sırasında başka dillerin uygulamaca desteklenmesini sağlar. Bu sistem aynı zamanda belgelendirme çevirilerinde de kullanılmaktadır.

GNOME çevirileri, uygulamaların şablon PO (POT) dosyaları üzerinden yapılmaktadır. PO dosyalarını düzenlemek için birçok uygulama bulunur. Değişiklikler, dosyaların belirli sözdizimi özelliklerine sadık kalarak yardımcı programlar aracılığıyla kolayca yapılabilmektedir. Bu dosyaların nasıl çevirileceğinin ayrıntılı anlatımını ‘[Çeviri Nasıl Yapılır?](/ceviri/ceviri-nasil-yapilir)’ sayfasında bulabilirsiniz.

---

### GNOME Türkçe çevirileri iş akışı

Çeviriler dağıtımların ve uygulamaların paketlerine konulabilmesi için GNOME Projesi sürüm denetim sistemine eklenmektedir. Bu sistem, erişim denetimi gerektirdiği için bu işlem çeviri koordinatörleri ve depo yetkililerince gerçekleştirilmektedir. GNOME Türkçe çevirilerinin koordinatörü ve depo yetkilileri [Damned Lies Türkçe Takımı](https://l10n.gnome.org/teams/tr) sayfasında görülebilir.

Çevirilerin ‘Dizge Donması’ sürecinde; paketlerin çevirmenlerce düzenli olarak alınması, denetlenmesi ve sürüm denetim sistemine gönderilmesi için Damned Lies’ın sağladığı izleme sistemi kullanılmaktadır.

Bu sistem; çevrilen paketlerin belirlenmesini, çeviri yapanların yaptığı çevirileri denetim için göndermesini ve denetim sürecinin de izlenmesini sağlamaktadır. Belirli bir iş akışında gerçekleşen sürecin temelleri bu sayfanın devamında anlatılmaktadır.

---

### Çevirmenlerin sisteme kaydolması

Çevirmenler, çalışmalara katılmak için öncelikle Damned Lies sitesine ve [anlık iletişim kanallarına](/anlik-iletisim-kanallari) kayıt olmalıdır. Kayıt olmadan çeviri gönderemezler.

Çeviri dönemlerini izlemeniz, diğer çevirmenler ve GNOME Türkiye üyeleriyle iletişim kurmanız açısından anlık iletişim kanallarına kaydolmanız önemlidir. Kaydolduktan sonra ufak bir tanıtıcı iletiyle ‘Merhaba’ diyebilirsiniz.

Damned Lies sistemine kaydolmak için öncelikle [‘Kayıt’](https://l10n.gnome.org/register/) sayfasından kullanıcı adı ve parolanızı belirlemeniz, sonrasında e-posta adresinize gelecek etkinleştirme postasındaki bağı tarayıcınızda açmalısınız.

Hesabınızı etkinleştirdikten sonra belirlediğiniz kullanıcı adı ve parola ile sağ üst köşede bulunan ‘Giriş yap’ bağı ile giriş yapabilirsiniz.

Giriş yaptıktan sonra sağ üst köşedeki insan simgesine tıklayıp ‘Kullanıcı Ayarları’na girerek ‘Ayrıntılarınızı ve ayarlarınızı değiştirin’ sayfasından profil bilgilerinizi güncellemelisiniz.

Bu sayfada öncelikle ‘Adı’ ve ‘Soyadı’ bölümlerini doldurun, diğer alanları da isteğinize göre doldurabilirsiniz. Ad ve soyad bilgisi sisteme girilmeyenlerin çevirileri reddedilecektir. Yine sağ üst köşedeki insan simgesine tıklayıp ‘Kullanıcı Ayarları’na girerek ‘Takım üyeliğinizi yönetin’ sayfasının ‘Yeni takıma katıl’ bölümünden ‘Türkçe’yi seçerek takımımıza katılabilirsiniz.

---

### Çevirilerin seçilmesi ve gönderilmesi

Kayıt işlemi bittikten sonra çevireceğiniz paketleri seçip çeviriye başlayabilirsiniz. Paket seçimi için anlık iletişim kanallarına başvurmanız önemlidir. Çünkü bazı paketler uzun dönemdir belirli çevirmenlerce çevrilmektedir ve niteliği artıran bu süreklilik nedeniyle kimi paketlerin çevirisi gene aynı çevirmenlerce üstlenilmek istenebilir. Bunu, anlık iletişim kanallarına alacağınız paketi belirttiğinizde öğrenebilirsiz.

[Damned Lies Türkçe Çeviri Takımı](https://l10n.gnome.org/teams/tr) sayfasındaki tablonun ‘Kullanıcı Arayüzü’ ve ‘Belgelendirme’ sütununda bulunan bağlara tıklayarak ilgili sürümün içerdiği paketler görüntülenir. [Modüller](https://l10n.gnome.org/module) sayfasından da sistemdeki tüm paketler görüntülenebilir.

Çevirilerde ‘master’ ya da ‘main’ ana dalları kullanılmalıdır. Yeni sürümler, eski sürümlerdeki çevirilerin yerine geçeceği için eski sürümleri çevirmek anlamsızdır. Dizge donması sürecine girildiğinde en son sürümü çevirmeniz esastır.

En yeni sürüm, listelenenler arasında en üst sırada ve sürüm numarası en yüksek olandır. Hangi sürümü çevireceğinizle ilgili yargıya varamadığınızda bilgi almak için anlık iletişim kanallarına başvurabilirsiniz.

GNOME Projesi’nde GNOME sürüm sürecine giren ve girmeyen paketler bulunmaktadır. GNOME sürüm sürecine girmeyen paketler ‘GNOME Circle’ ve ‘Diğer Uygulamalar’ adı altında yer alır. Çeviri önceliğimiz GNOME sürüm sürecine giren paketlerdedir, ancak bazı yaygın kullanılan paketlerin (örneğin GIMP, Evolution, Geary vb.) çevirileri de önemlidir. Ancak bu paketlerin dizge donma süreçleri belirsiz olduğu için bu paketlerin izlenmesini çevirmen yapmalıdır.

Çevirmek istediğiniz paketin bağını tıkladıktan çeviri sürecini başlatabilirsiniz.

Paketi çeviri için ayıran yoksa sayfadaki ‘Yeni Eylem’ bölümünde eylem olarak ‘Çeviriyi üzerine al’ı seçerek paketin artık sizin tarafınızdan çevirileceğini belirtebilirsiniz. Burada ‘Yorum’ bölümüne çeviriyi ne kadarda tamamlayabileceğinizle ilgili öngörünüzü belirtin.

Yaptığınız paket seçimlerini toplu olarak anlık iletişim kanallarına belirtmeyi unutmayın. İngilizce sözcüklerin yaygın ya da yeğlediğimiz Türkçe karşılıkları için [Sözlük](/ceviri/sozluk) ve [Yazım Kuralları](/ceviri/yazim-kurallari) sayfamıza göz atmalısınız. Çevirilerinizde bu karşılıkları kullanmanız önemlidir.

Çeviriyi tamamladıktan sonra gene aynı sayfaya gelerek eylem olarak ‘Yeni çeviriyi karşıya yükle’yi seçin. ‘Yorum’ bölümüne emin olmadığınız dizgeleri ya da belirteceğiniz başka bilgileri ekleyebilirsiniz. Çevirisini bitirdiğiniz PO dosyasını da seçerek dosyayı gönderin.

---

### Çeviri dosyalarının izlenmesi

Çevirisini gönderdiğiniz ve üzerinizde bulunan paketleri profil sayfanızda görebilirsiniz. Bu sayfada gönderdiğiniz çevirilerin henüz denetlenip denetlenmediğini de izleyebilirsiniz.

Denetçi onayı ve gerekli düzeltmeler sonrasında depo yetkilisi ya da koordinatör çeviriyi sürüm denetim sistemine gönderir. Böylece ilgili paket profilinizden kaldırılır. Çevirilerle ilgili gelişmeler çevirmene sistemce kendiliğinden e-posta olarak gönderilmektedir.

---

*Belgeyi güncelleyen:* Emin Tufan Çetin
