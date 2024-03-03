---
title: 'GNOME Masaüstü Uygulamaları Nasıl Çevrilir?'
date: '2021-05-18T22:19:00+03:00'
author: 'GNOME Türkiye'
layout: post
permalink: /gnome-masaustu-uygulamalari-nasil-cevrilir/
categories:
    - Makaleler
tags:
    - Çeviri
    - GNOME
---

![](/media/2023/04/gnome-01.jpg)

Özgür yazılımın güzel yanlarından birisi de pek çok şekilde katkı vermenin mümkün olması. Bu yazımda GNOME masaüstü ortamında çeviri macerasını sizinle paylaşmaya çalışacağım.

## Gnome çevirileri nerede?

GNOME masaüstü ortamının ana çeviri deposu [l10n.gnome.org](https://l10n.gnome.org/) sitesi olup, çeviriler bu site üstünden ilgili uygulamaların depolarına aktarılmaktadır.

Siteye girdiğimizde sade bir arayüz bizi karşılıyor. Logonun yanında Takımlar, Diller, Sürüm takımları, Modüller linkleri, sağ üst köşede ise Giriş yap bağlantısı bulunuyor.

![](/media/2023/04/gnome-baslik.png)

- **Takımlar:** Çeviri yapılan diller ve koordinatörleri, ayrıca ilgili çeviri ekibinin profil sayfasına giden bağlantıları bulundurur.
- **Diller:** RSS ile son çeviri değişikliklerini takip etmeye yarayan bağlantıları içerir.
- **Sürüm takımları:** GNOME sürümleri ve çeviri durumlarıyla ilgili kimi bilgilere erişebilirsiniz.
- **Modüller:** Çevirisi yapılan uygulama ve kütüphanelerin adlarını ve bağlantılarını listeler.

Takımlar sayfasından Türkçe sayfasına [tıklıyoruz](https://l10n.gnome.org/teams/tr/).

![](/media/2023/04/gnome-turkiye-takimi.png)

**Gnome Türkiye Twitter hesabı**: Çevirilerin son durumunu ve yeni sürüm duyuruları gibi paylaşımların yapıldığı sosyal medya hesabıdır.**Telegram Kanalı**: GNOME üstüne yardım almak, çeviriye katkı bulunmak gibi konularda soru sorup hızlıca cevap bulabileceğiniz Telegram kanalıdır.

**E-posta Listesi**: Kamuya açık olarak yazışmaların [arşivlendiği](https://mail.gnome.org/archives/gnome-turk/) bir mesaj grubudur. Telegram kanalı ile aynı işlevi görür ve Telegram kanalından daha hızlı sonuç alabilirsiniz ve kamuya açık olarak da arşivlenmez.

**Ayrıntılar** altında görünen bağlantılara gelirsek:

**Çeviride Hata Kaydı Bildir** bağlantısını kullanarak GNOME çeviri sitesinde çevrilen uygulamalarla ilgili hata raporlamak mümkündür.

**Var Olan Hataları Göster** bağlantısından açılmış hata raporlarına bakabilirsiniz.

**Koordinatör** kısmında GNOME çevirilerine uzun süre katkı vermiş Muhammet Kara Bey’in ismini görebilirsiniz.

## Gnome sürümleri ve çeviri süreçleri

Ortada yer alan sol kısımda yazanlar sizin de dikkatinizi çekmiş olmalı. Açıklamaya çalışayım:

![](/media/2023/04/gnome-translate-grafik-1.png)

**GNOME 42/43 (stable/development)**: Güncel ve GNOME çevirilerine katkı verebileceğiniz temel uygulamalar en üstte yer alan ve numarası en büyük olan sürümdür. Bu sürümün yanında çoğu zaman development, arada stable yazmaktadır. GNOME 43 ile ilgili sürüm takvimi işlemeye başlamış olup, [şuradan](https://wiki.gnome.org/FortyThree) görebilirsiniz.

**GNOME 41 (old stable)** / **GNOME 40 (eski kararlı)**: Yanında old stable veya eski kararlı yazan bu sürüm takımları artık çeviri kabul etmeyen GNOME sürümlerini ifade eder. GNOME resmi uygulamalarına ait çevirilerde bulduğunuz hataları stable sürüme raporlamanız gerekir.

[**GNOME Circle**](https://circle.gnome.org/) görece yeni bir oluşum olup, GNOME ekosistemine yeni uygulama ve kütüphaneler kazandırmayı amaçlar. Şimdilik 40 uygulama ve 5 kütüphane bu ekosisteme dâhildir. Bu uygulamaların 14 tanesinin çevirileri l10n (localization) altında yapılmaktadır. Kimi uygulamalar çevrimiçi çeviri platformlarını kullanmaktadır. Circle uygulamalarının l10n üstünde tutulması zorunluluğu bulunmamaktadır.

**GNOME Altyapı** altında l10n.gnome.org sitesi gibi altyapıların çevirileri bulunur. Bu alanda katkı vermek için GNOME uygulamalarını iyi tanımakta yarar var. Ayrıca jhbuild ile lGNOME Library (help.gnome.org) gibi kimi sayfalar ve uygulamalara dair çeviriler de burada bulunur. Bu ikisine çeviri desteği vermek öncelikli yapılacaklar listesinde bulunmuyor.

**GIMP ve Arkadaşları** kısmında GIMP uygulamasının kararlı sürümüne ait çeviriler ile birlikte uzun süredir beklenen Geliştirme sürümüne ait çeviriler burada bulunur.

GIMP çevirilerine katkı vermek için bu uygulamanın uzun zamandır çevirilerini yapmakta olan Sabri Ünal ile iletişime geçmekte yarar var.

**Ekstra GNOME Uygulamaları (kararlı)** kısmı arşiv amaçlıdır ve çeviriler bir altında bulunan Ekstra GNOME Uygulamaları dalında yapılmaktadır.

**Ekstra GNOME Uygulamaları** kısmına çeviri desteği vermek, GNOME ana uygulamalarına çeviri vermekten çok daha kolaydır. Bu kısımdaki uygulamaların bazıları eski GNOME sürümlerinde ana dağıtımın bir parçası da olabilir. Örneğin Gedit uygulaması bu kısma yeni taşınmıştır. Artık GNOME text editor uygulaması Gedit’in yerine tercih edilmektedir.

Ekstra kısmında bulunan uygulamalar GNOME sürüm takvimini takip etmek zorunda değillerdir. GNOME çevirilerine katkı vermek için Circle uygulamaları ile birlikte en isabetli başlangıç noktası burasıdır.

**Librem 5 – Purism** kısmında bulunan çeviriler güvenlik ve gizlilik öncelikli bir telefon projesi olan [Librem 5 Projesi](https://puri.sm/products/librem-5/)’ne aittir.

**freedesktop.org (GNOME olmayan)** kısmında yer alan çeviriler sadece yansı olarak burada tutulmaktadır. Katkı vermek için her projenin kendi sitesindeki talimatları izlemek gerekmektedir.

Görselde görülmeyen **Takım üyeliği** kısmında geçerli Depo yetkilileri, denetmenler ve çevirmenlere ait bağlantılar bulunmaktadır.

## Artık çeviriye geçsek mi?

**Kayıt Olmak**

Çevirilere katkı vermek için önce kayıt olmak gerekiyor. Giriş yap düğmesine gizlenmiş kayıt sayfasına [geliyoruz](https://l10n.gnome.org/register/). Formu doldurup, maile gelen bağlantıya tıklayıp hesabı etkinleştiriyoruz. Sonrasında siteye giriş yapıp profilimizi [tamamlıyoruz](https://l10n.gnome.org/users/detail_change/) (Ad Soyad eklemek önemli). Sonrasında katılmak istediğimiz çeviri takımını seçip [Türkçe](https://l10n.gnome.org/teams/tr/) sayfasına geri dönebiliriz.

**Çevirilecek Uygulama/Modül Bulmak**

Circle uygulamaları görece az çevirilecek değer içermesi sebebiyle çeviriye buradan başlamak daha kolay olacaktır. Giriyoruz ve karşımıza şöyle bir ekran çıkıyor.

![](/media/2023/04/gnome-circle.png)

Ekrana sığsın diye tamamlanan modülleri sağdaki bağlantıdan gizledim. Çeviri katkısı verebileceğimiz çeşitli uygulamalar görülüyor.

İstatistik sütunundaki yüzde işareti çevirinin tamamlanma yüzdesini, yeşil rakamlar kaç dizgenin çevrildiğini, sarı rakamlar kaç dizgenin çevirisinin bulanık/fuzzy (yani gözden geçirilmesi gerekiyor) olduğunu, kırmızı rakamlar ise kaç dizgenin hiç çevrilmediğini gösteriyor. Durum ve Tarih kısmında ise ek bilgiler yer alıyor.

Yeni bir çeviri başlamaktansa eksik çeviriye tamamlamak daha kolay olacaktır. Secrets uygulaması çevrilebilir gibi görünüyor. Uygulamanın üstüne tıklayıp detaylarına geliyoruz.

![](/media/2023/04/gnome-secrets-sayfasi.png)

Uygulama adı, hangi dal olduğu ve dil bilgisi yer alan üst çubuğun altında iki tane indirme simgesi alt alta yer alıyor. Onun altında Dizge ve sözcüklere dair istatistikler yer alıyor.

Eylem kısmından “Çeviriyi üzerine al” seçiyoruz ve yeni dosya eklemeden, isterseniz yorum kısmına kısa bir yorum bırakıp gönder tuşuna basıyoruz. Artık çeviriye başlayabiliriz.

> Çeviriyi üzerinize aldıktan sonra yaptığınız çeviriyi yükleyene veya üzerinizdeki eylemi geri alana dek başka biri bu modülde işlem yapamaz. Bu sebeple üzerinize aldığınız çeviriyi tamamen bitmemiş olsa bile bittiği kadarıyla günün sonunda siteye yüklemeyi tavsiye ederim.

## Po dosyaları nasıl çevrilir?

İkinci indirme düğmesine tıklayıp açılan po uzantılı dosyayı bilgisayara kaydediyoruz. Po uzantılı dosyalarını düzenlemek için yaygın olarak kullanılan uygulamalar arasında Poedit çoklu platform desteği sunması ile öne çıkmaktadır. Ayrıca Gtranslator (GNOME) ve Lokalize (KDE) uygulamaları da bulunmaktadır. Üç uygulamanın son sürümlerini Flathub.org üstünden flatpak olarak indirip kurmak mümkündür. Şahsen Poedit kullanıyorum ve size de tavsiye ederim.

Uygulamayı kurduktan sonra .po dosyasını Poedit ile açıyoruz. İlk iş olarak menüden Düzen &gt; Tercihler &gt; Genel altındaki çevirmen hakkında bilgi kısmına adımızı/soyadımızı ve iletişim için kullanılacak e-posta adresimizi giriyoruz. Bu bilgiler bir nevi bizim imzamız yerine geçecekler. “Kaydederken MO dosyasını otomatik olarak derle” seçeneğini kapatıyoruz. MO dosyaları ile işimiz olmayacak.

Sonrasında yine menüden Görünüm &gt; Çevrilmemiş Dizgeler En Üstte seçeneğini etkinleştiriyoruz. Böylece çevirisi eksik dizgeleri bulmak daha kolay olacak.

![](/media/2023/04/poedit-ekran-1.png)

Mavi ile işaretlenmiş satır, hangi satırda olduğumuzu işaret ediyor. Kaynak metin kısmında çevirisi yapılması gereken metin, çeviri kısmında varsa bulanık olarak işaretlenmiş önceki çeviri yer alıyor. Sağ tarafta alt sütunda önceki kaynak metin yer alıyor.

Karşılaştırınca sadece bir kelimenin büyük harfken küçük harfe dönüştürüldüğünü görebilirsiniz. Çeviride Büyük/Küçük harf düzenine kadar korumak gerekiyor. Yorum ekle düğmesini kullanarak gelecek çevirilere not bırakmak mümkündür. Gerekli çeviri değişikliğini yaptığımızda örneğimizdeki çalışma gerekli düğmesi sarı işaretli olmaktan çıkıp normal düğme haline gelecektir.

Çalışma Gerekli düğmesi çeviriyi fuzzy/bulanık olarak işaretlemek için kullanılır. Çevirisi bitmemiş dizgeler programlar tarafından çevrilmiş olarak görüntülenmez.

> Kalitesiz veya eksik bir çeviri yapmaktansa programların hiç çevrilmemesi veya fuzzy/bulanık kalması daha uygundur. Kötü çevrilmiş bir dizgenin fark edilmesi uzun yıllar sürebilir. Programı kendi dilinde kullanacak kişi, kötü çeviriler yüzünden dil tercihini değiştirmek zorunda kalabilir.

Sağ sütünda Öneriler kısmının boş olduğunu görebilirsiniz. Poedit Çeviri Belleği desteği sunmaktadır. Çeviri destekleri daha önceden çevrilmiş çevirilerden yararlanarak size kısmen veya tamamen çevirileri öneri olarak getirir.

Görselde en üstte görünen translator-credits değerinin karşısında isim ve e-posta adreslerinin bulunduğunu görebilirsiniz. Bu bilgiler uygulamanın çevirmenlerinin listelenmesi için kullanılır. GNOME Türkiye ekibi olarak bu alana bilgilerin çeviriye yüksek oranda katkıda bulunmuş kişilere ait olmasına önem gösteriyoruz.

Çeviri yaparken dikkat edilmesi gereken bir nokta da hızlandırıcılardır. Hızlandırıcılar alt çizgi ile başlayan harfler olup, klavyede bulunan alt tuşuna basınca görünür olurlar. Menülere veya ilgili öğeye ulaşmayı kolaylaştırırlar. Çeviride hızlandırıcı varsa uygun bir harfe atanmaya çalışılmalıdır. Türkçe’ye özgü harflerden veya ı, i, l gibi çok ince harflere atanmamaya çalışılmalı ve mümkünse cümlenin başındaki harflere atanmaya çalışılmalıdır.

Çeviri yaparken kelimenin daha önce aynı uygulama içinde nasıl kullanıldığına dikkat etmek gerekir. Bazen çok yaygın bir kelime bile özel bir anlamda veya daha yaygın olmayan bir başka çevirisiyle kullanılmış olabilir. Bu konuda dosya içinde arama yapmakta yarar vardır. Arama yapmak için çeviri alanına tıkladıktan sonra ctrl+f tuşuna basarak açılan pencereden yardım alınabilir.

Çevirisi yapılmış değerlere önceki çevirmenlere danışılmadan değişiklik yapılmamalıdır. Bariz hata olmadıkça bu tür değişiklikler gereksiz karşılanır. Oturmuş çeviriyi değiştirmek bazen yardım dosyalarının çevirilerinin de güncellenmesini gerektirebilir.

Çeviri işlemi bitince Doğrula düğmesine tıklanıp çeviri doğrulanmalıdır. Bir hata olması durumunda Poedit hata verecektir. Menüden Görünüm &gt; Hataları Olan Dizgeler En Üstte seçeneğini etkinleştirirseniz hatalı olabilecek dizgeler en üstte listelenir. Poedit her zaman doğru sonucu vermeyebilir. Kimi uyarılar önemsiz olabilir. Duruma göre karar vermek gerekecektir.

Son olarak dosyamızı kaydedebiliriz. Çevirileri incelenmek üzere göndermeye neredeyse hazırız.

Po dosyasını bu sefer UTF-8 destekli bir metin editörüyle açıyoruz ve başlık/header bölümündeki çevirmenler listesinin en altına adımızı ekliyoruz. Adımız zaten listedeyse en alta alıp, sonuna çevirinin yapıldığı yılı ekliyoruz. Listede görünen diğer isimler ve e-posta adresleri üstünde değişiklik sakın yapmayın, bunlar çevirmenlerin imzalarıdır.

![](/media/2023/04/gnome-ceviri-ornek-header.png)

l10n.gnome.org sitesine geri geliyoruz ve eylem kısmından “Yeni çeviriyi karşıya yükle” seçeneğini seçip dilersek gerekli yorumu yazıp, dosyayı seçiyor ve gönder düğmesine basıp gönderiyoruz.

![](/media/2023/04/gnome-secrets-son-durum.png)

Yeni ekran görüntümüz yukarıdaki şekilde oluşacaktır.

Eylemler (Önceki eylem geçmişi) kısmından gerçekleşmiş eylemleri takip edebilirsiniz. Genelde çeviriler direk olarak onaylanmaz ve düzeltme için sizden yapmanız istenen iyileştirmeler olacaktır. Bu durumda size e-posta ile bildirim ulaşır.

Yazdığımız yorumun yanında açıklanmaya değer iki indirme dosyası ve yine klasik yeşil, sarı ve kırmızı sayılar bulunmaktadır. İlk dosya sizin gönderdiğiniz dosyadır, ikinci dosya ise zamanla uygulamada yaşanan çeviri değişikliklerinin uygulandığı dosyadır. Sayılar bu duruma göre farklılık gösterecektir. Fark kelimesinin yanındaki sayı ise yapılan değişikliklerin farklarını görmenize izin verir. Çeviriniz onaylandıktan sonra bu farkları kullanarak çeviri üstünde yapılmış değişiklikleri inceleyebilir ve gelecek çevirilerde bu konularda daha dikkatli olabilirsiniz.

## İleri işlemler: çeviri belleği ve çeviri dosyası doğrulama

Poedit için çeviri belleği oluşturmak mümkündür. GNOME kararlı sürüm sayfasına gelip en altta bulunan “Tüm po dosyalarını indir” bağlantısına tıklıyoruz. İnen dosyaları sıkıştırılmış formattan normal klasör haline çıkartıyoruz. Sonra Poedit programında bir tane .po dosyası açıp Menü &gt; Düzen &gt; Tercihler &gt; ÇBelliği &gt; Çeviri belleği kullan seçeneğini etkinleştiriyoruz. Yönet düğmesine basıp “Çeviri Dosyalarını İçe Aktar” yoluyla açılan pencereden GNOME .po dosyalarının hepsini seçiyoruz. Çeviriler içeri aktarılacaktır. Aktarma işlemi sırasında hata almak da mümkündür.

Translate House tarafından sağlanan pofilter uygulaması .po dosyaları üstünde çeşitli testler yapmaya izin verir. Pardus depolarında bulunmaktadır ve Synaptic veya uygulama mağazasında depolarda aranarak kurulabilir. Terminalden sadece şu komutu girmeniz yeterlidir.

```
sudo apt-get install translate-toolkit
```

Sonrasında ev klasörümüz altında bulunan .bashrc dosyasının sonuna şu aliasları ekliyoruz ve kaydedip kapatıyoruz.

```
alias potestgnome="pofilter --gnome -t accelerators $1 --output result.txt.po" 
alias potestgnomebig="pofilter --gnome $1 --output result_big.txt.po"
```

Bu iki alias sayesinde nasıl kullanılıyordu diye şüpheye düşmeden .po dosyalarımızı test edebiliriz. Po dosyasının bulunduğu dizine gelip uçbirim açıyoruz ve komutlarımızı veriyoruz.

```
potestgnome dosyaadi.po
potestgnomebig dosyaadi.po
```

Komutların çalıştığı dizinde iki yeni dosya oluşacaktır. Dosyalar po uzantısına sahip olmasına rağmen metin editörüyle açmayı tercih ediyoruz.

result.txt.po dosyasında hızlandırıcılarla ilgili şikayetleri görüyoruz.

```
# (pofilter) accelerators: Accelerator '_' appears before an invalid accelerator character 'Ö'
#: data/gtk/settings_dialog.ui:155
msgid "_Special Characters"
msgstr "_Özel Karakterler"
```

Bu örnekte hızlandırıcı için Ö harfinin kullanıldığını görüyoruz. Bu hata kendi çevirdiğimiz kısımda yer alıyorsa Ö harfinden sonra gelen z harfine hızlandırıcı atayarak bu sorunu çözebiliriz.

result\_big.txt.po dosyası hızlandırıcılarla ilgili şikayetlerin yanında diğer uyarıları da içeriyor. Bu uyarılar her zaman uyulması gereken kesin doğrular olmayabiliyor.

```
# (pofilter) simplecaps: Different capitalization
#: data/gtk/create_database.ui:57
msgid "_Keyfile"
msgstr "_Anahtar Dosyası"
```

Mesela bu örnekte orijinal dizge tek kelimeden oluşurken çeviri çift kelimeden oluşuyor. Hızlandırıcı kullanılmasından bunun bir menü cümlesi olduğunu veya olabileceğini biliyoruz ve çoğu zaman menülerdeki cümlelerin çevirisinde Başlık Düzeni tercih ediliyor. Bir başka deyişle, bu uyarı çok önemli bir hataya işaret etmiyor.

Aynı şekilde dosyada “Different capitalization” şeklinde uyarılar da görebiliyoruz. Bunlar da duruma göre çoğu zaman önemli olmayabiliyor. “Different spacing around punctuation” çoğu zaman bir anlam ifade etmiyor. “unchanged: Consider translating” uyarısı isimleri, standartları çevirmemiz konusunda bize hatalı uyarılar verebiliyor, önemli değil. Önemli olabilecek uyarılar arasında cümle içinde çift hızlandırıcı kullanılmış olması veya gereksiz yere hızlandırıcı kullanılması veya kullanılmamış olması sayılabilir.

## Sonuç

Yazılım çevirisi eğlenceli olduğu kadar dikkat gerektiren bir sanat. Bu yazımızda GNOME çevirilerine nasıl katkı verebileceğinizi elimden geldiğince anlatmaya çalıştım. Çeviriler konusunda aklınıza takılan sorular olursa GNOME Türkiye Telegram kanalından sormaktan çekinmeyin.

Dipnot:

Bu yazı daha önce [gonullu.pardus.org.tr](https://gonullu.pardus.org.tr/gnome-masaustu-uygulamalari-nasil-cevrilir/) adresinde yayınlanmıştır.