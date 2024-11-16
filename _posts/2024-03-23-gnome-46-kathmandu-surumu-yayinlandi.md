---
title: 'GNOME 46, “Kathmandu” Sürümü Yayınlandı'
date: '2024-03-23T08:00:00+03:00'
author: 'GNOME Türkiye'
layout: post
permalink: /gnome-46-kathmandu-surumu-yayinlandi/
categories:
    - Haberler
tags:
    - GNOME
    - 'GNOME 46'
    - 'Linux Masaüstü Ortamı'
    - 'Yeni Sürüm'
---

![GNOME 46 Kathmandu afişi](/media/2024/03/46.webp "GNOME 46 Kathmandu afişi")

GNOME projesi, en son GNOME sürümü olan GNOME 46’yı sunmaktan heyecan duyuyor. Bu son sürüm, GNOME topluluğunun 6 aylık sıkı çalışmasının sonucudur. Katkıda bulunan herkese teşekkür ederiz!

GNOME 46, GNOME.Asia 2023 düzenleyenlerinin yaptığı harika çalışmaların takdiri olarak “Kathmandu” kod adını taşıyor.

Gelin GNOME 46 yeniliklerini birlikte keşfedelim!

## Her Yerde Ara

Dosyalar, GNOME 46ʼda yeni **genel arama özelliği** ile geliyor. Özellik oldukça basittir: yeni arama düğmesine tıklayarak ya da <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>F</kbd> kısayolunu kullanarak etkinleştirin, ardından sorgunuzu girerek yapılandırılmış tüm arama konumlarında arayın.

Genel arama, istediğiniz öğelerin nerede bulunduğunu düşünmeden doğrudan aramak için harika bir yoludur.
Yeni özellik ayrıca GNOME'un dosya içeriğini arama ve dosya türü ve değişiklik tarihine göre süzme gibi var olan dosya arama özelliklerinden de yararlanıyor.

Genel aramanın harika bir özelliği de aynı anda birden çok konumda arama olanağı sunmasıdır; bu konumlar ev dizininizde olmak zorunda da değildir. Bunun için, arama konumları ayarlarına gidin ve dahil etmek istediğiniz konumları ekleyin.

<picture class="full rounded">
    <source media="(prefers-color-scheme: dark)" srcset="/media/2024/03/search-everywhere-dark.svg">
    <img src="/media/2024/03/search-everywhere.svg">
</picture>

## İyileştirilmiş Dosyalar Uygulaması

Genel aramanın yanı sıra, Dosyalar uygulaması GNOME 46 için ciddi bir güncelleme aldı. Uzun süren dosya işlemleri hakkındaki geri bildirimler iyileştirildi ve kenar çubuğunun altına yeni dinamik ilerleme bölümü eklendi. Bu, tek tek işlemlerin ilerlemesini görüntülemenin yanı sıra devam eden işlemleri ve biten işlemleri görmeyi sağlıyor.

<picture class="rounded">
    <source srcset="/media/2024/03/file-ops-screenshot-dark.png" media="(prefers-color-scheme: dark)">
    <img src="/media/2024/03/file-ops-screenshot.png">
</picture>

GNOME 46'nın geliştirilmesi sırasında kodun önemli ölçüde yeniden düzenlemesi, Dosyalar uygulamasında hoş başarım yükseltmesi de sağladı. Geçmişte, liste ve ızgara görünümü arasında geçiş yapmak gecikmeli gerçekleşiyordu ve içerik ekrana aşamalı olarak yüklenirdi. GNOME 46'da bunlar yok: görünüm değişimi anında gerçekleşiyor ve daha hızlı ve sorunsuz bir deneyim sunuyor.

<video nocontrols muted autoplay loop class="full rounded">
  <p>Dosyalar 46: Izgara ve liste görünümleri arasında geçiş yaparken iyileştilmiş başarım. GNOME 45, görünümü her seferinde yeniden yüklüyordu.</p>
  <source src="/media/2024/03/files-46.webm" type="video/webm">
  <source src="/media/2024/03/files-46.mp4" type="video/mp4">
</video>

Son olarak Dosyalar, GNOME 46'da bir dizi diğer küçük iyileştirmeyi de içeriyor:

* **Tercihler için arama:** Dosyalar tercihleri içinde belirli ayarları bulmak için arama yapabilirsiniz.
* **Ayrıntılı tarih ve saat:** Dosyalar tercihleri tarihi ve saati daha kapsamlı ve tutarlı bir biçimde gösterme seçeneği içeriyor.
* **Tıklanabilir konum girdisi:** Dosya yolu alanına tıklayarak dosya konumu adres çubuğuna hızlıca erişin.
* **Izgara görünümünde yıldızlı gözdeler:** Izgara görünümünde görsel işaretlerle yıldızlı dosyalarınızı hızlıca tanıyın ve erişin.
* **Geliştirilmiş ağ keşfi:** Diğer Konumlar görünümünde artık çok daha fazla ağa bağlı kullanılabilir aygıt görünüyor.

Dosyalarʼdaki yeni özellikleri keşfetmenizi ve yepyeni dosya yönetimi verimliliğini deneyimlemenizi öneririz!

## Yükseltilmiş Çevrim İçi Hesaplar, Artık OneDrive İle

GNOME Çevrim İçi Hesaplar özelliği, GNOME 46 ile önemli bir güncelleme aldı. En büyük iyileştirme, yeni **Microsoft OneDrive desteği**. Ayarlardan Microsoft 365 hesabı kurduğunuzda OneDrive'ınız Dosyalar kenar çubuğunda görünecek, böylece yerel dosya ve klasörlerinizin yanında kolayca gezinilebilir ve erişilebilir olacak.

Ayrıca, Çevrimi İçi Hesaplar'a ek iyileştirmeler yapılmıştır, bunların finansmanı [Sovereign Tech Fund](https://foundation.gnome.org/2023/11/09/gnome-recognized-as-public-interest-infrastructure/) tarafından sağlanmıştır:

* Hesap kurulumunun bir parçası olarak hesaplara oturum açarken artık öntanımlı web tarayıcısı kullanılıyor. Bu, USB jetonları gibi **daha geniş kimlik doğrulama yöntemi yelpazesinin** kullanılmasına olanak tanıyor.
* Çevrim içi kişileri, takvimleri ve dosyaları GNOME deneyiminize tümleştirmeniz için genel yöntem sağlayan **yeni WebDAV hesap türü** eklendi.
* Çevrim İçi Hesaplar **ayarları tamamen yeniden tasarlandı** ve çağdaş ve güncel tasarımlara kavuştular.

Bu değişikliklerin gereği olarak, Çevrim İçi Hesaplar artık başlangıç sistem kurulumun parçası değiller. _Kurulumdan sonra çevrim içi hesapları elle bağlamanız gerekecektir._

## RDP ile Uzaktan Oturum Açma

GNOME'nin uzak masaüstü deneyimi, 46 sürümü için önemli ölçüde geliştirildi ve yeni **özel uzak oturum açma seçeneği** tanıtıldı. Bu, o an kullanılmayan GNOME sistemine uzaktan bağlanmayı sağlar. Bu şekilde bağlanmak, sistem ekranının uzaktan yapılandırılabilmesini sağlar ve uzak kullanıcı için daha iyi bir deneyim sunar.

Yeni uzak oturum açma özelliği, GNOME sistemlerinin tam teşekküllü uzak kaynaklar olarak kullanılabilmesi anlamına gelir. Nasıl bağlanılacağı hakkında bilgi veren Uzak Masaüstü ayarlarında daha fazla bilgi bulabilirsiniz.

<picture class="full rounded">
    <source srcset="/media/2024/03/remote-screenshot-dark.png" media="(prefers-color-scheme: dark)">
    <img src="/media/2024/03/remote-screenshot.png">
</picture>

## Yükseltilmiş Ayarlar

Ayarlar uygulaması GNOME 46'da kapsamlı şekilde güncellendi.

### Gezinti İyileştirmeleri

Ayarlar uygulaması, GNOME 46 için **gezinmesi daha kolay** olacak şekilde yeniden düzenlendi. *Bölge ve Dil*, *Tarih ve Saat*, *Kullanıcılar*, *Uzak Masaüstü*, *Güvenli Kabuk* ve *Hakkında* tercihleri yeni oluşturulan Sistem bölümüne taşındı. Uygulamalar ayarları da *Öntanımlı Uygulamalar* ve *Çıkarılabilir Ortam* ayarlarını içerecek şekilde birleştirildi.

Bu değişiklikler, Ayarlar uygulamasındaki toplam bölüm sayısını azaltarak, gezinmek için daha az yer ve ihtiyacınız olan ayarlara daha hızlı erişim sağlar.

### Yeni Dokunmatik Yüzey Ayarları

GNOME 46 için dokunmatik yüzey ayarları genişletildi ve iki yeni ayar eklendi. İlk olarak, **İkincil Tıklama** adı verilen ayar, dokunmatik yüzey ile ikincil tıklamaların ("sağ tıklama" olarak da adlandırılır) nasıl yapıldığını yapılandırmayı sağlıyor ve dokunmatik yüzey üzerinde iki parmağın kullanılması ya da dokunmatik yüzeyin köşesine tıklanması ile ilgili seçenekleri içeririyor.

İkinci yeni ayar, **Yazarken Dokunmatik Yüzeyi Devre Dışı Bırak** davranışının kapatılmasını sağlıyor. Bunu yapmak, bazı uygulamalar ve oyunlar için gerekli olan dokunmatik yüzey hareketinin tuş vuruşlarıyla birleştirilmesine izin veriyor.

### Muazzam İyileştirme Çabası

Ayarlar uygulaması, GNOME 46 için geniş çapta iyileştirildi. Bunlar şunları içerir:

* İyileştirilmiş ayar açıklamaları ve araç ipuçları
* Klavye gezinimini geliştirmek için daha fazla klavye anımsatıcısı (bunları görmek için Alt tuşuna basılı tutun)
* Kapsamlı kullanıcı arayüzü güncellemesi ve iyileştirmesi
* Klavye kısayolu ataması oluşturmak için ek seçenekler
* Görünüm ayarlarının daha hızlı yüklenmesi ve daha net ön izlemeler
* Wacom kalem basıncını ayarlarken ek ince ayar seçenekleri

Tüm bu iyileştirmeler sonunda daha net, anlaşılması daha kolay ve kullanımı harika bir Ayarlar uygulamasına yol açar.

## Erişilebilirlik İyileştirmeleri

Erişilebilirlik, GNOME 46 için güçlü bir çalışma teması oldu ve erişilebilirlikle ilgili birçok konu iyileştirildi. Bu çalışmanın büyük bir kısmı Orca ekran okuyucusuna odaklandı:

* Alt yapıda, **önemli bir modernizasyon çabası** devam ediyor. Bu, başarımı geliştirirken güvenilirlik de sağlayacak. Ayrıca gelecekte Wayland ve yalıtılmış uygulamalarla uyumluluğu mümkün kılacak.
* **Yeni uyku kipi** özelliği eklendi. Bu çok talep edilen özellik, <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Q</kbd> kısayolunu kullanarak kullanıcıların geçici olarak Orca'yı devre dışı bırakmasını sağlıyor. Uyku kipi ekran okuyucusu olan sanal makineleri ya da kendi sesini duyuran uygulamaları kullanırken kullanışlıdır.
* Yeni komutlar, Orca'nın batarya durumu, işlemci ve bellek kullanımı da dahil olmak üzere sistem durumunu **bildirmesini** sağlıyor.
* **Tablo gezinimi** önemli ölçüde iyileştirilmiştir ve artık çok daha fazla uygulamayı desteklemektedir. Yeni komutlar da eklenmiştir. Bunlar arasında tablo gezinimini aç/kapat  (<kbd>Orca</kbd>+<kbd>Shift</kbd>+<kbd>T</kbd>) ve son hücreye git (<kbd>Orca</kbd>+<kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>🡰</kbd>/<kbd>🡲</kbd>/<kbd>🡱</kbd>/<kbd>🡳</kbd>) bulunmaktadır.
* Orca artık, heyecan verici gelecek nesil konuşma sentezi API'si **Spiel için deneysel destek** sunuyor. Bu özelliği denemek isteyenler [test etmeye davet edilmektedir](https://gitlab.gnome.org/GNOME/orca#experimental-features).

GNOME 46'da erişilebilirlik iyileştirmelerinin gerçekleştiği tek yer Orca değildi. Diğer erişilebilirlik iyileştirmeleri arasında şimdi daha tutarlı ve kullanılabilir durumda olan **yüksek karşıtlık kipi**, ve **değiştiricilerde açık/kapalı simgelerini göstermek için yeni ayar** yer alıyor.

Bu erişilebilirlik çalışmasının büyük bir kısmı [Sovereign Tech Fund](https://foundation.gnome.org/2023/11/09/gnome-recognized-as-public-interest-infrastructure/) ve [Igalia](https://www.igalia.com/) tarafından finanse edildi.

## Sistem Geliştirmeleri

GNOME 46, temel GNOME deneyiminde birçok küçük iyileştirme ve değişiklik içeriyor:

* **Harika yedek profil resimleri:** Kullanıcı hesabınız için bir profil resmi belirtmezseniz, GNOME sizin için bir tane oluşturur. Bu yedek profil resimleri GNOME 46 için yenilendi ve harika görünüyor. Önceki sürümden yükseltme yapıyorsanız, yeni öntanımlı profil resimlerini görmek için eski profil resminizi temizleyin.
* **Geliştirilmiş bildirimler:** Bildirim düzenleri her bildirimde hangi uygulamanın gönderdiğini gösteren yeni başlıkla iyileştirildi. Bildirim eylemlerini size uygun bir zamanda kullanmak için artık listedeki bildirimleri genişletebilirsiniz.

<picture class="rounded">
    <img src="/media/2024/03/notifications-screenshot.png">
</picture>

* **Yeni uygulama penceresi kısayolu:** Konsola sabitlenen uygulamalar zaten <kbd>Super</kbd>+<kbd>&lt;Sayı&gt;</kbd> kullanılarak başlatılabiliyordu. Örneğin, konsoldaki ilk uygulamayı <kbd>Super</kbd>+<kbd>1</kbd> kısayolu ile başlatabiliyordunuz. GNOME 46, yeni pencere başlatmak için ek kısayolları içerecek şekilde bu kısayolları genişletiyor. Örneğin: Konsoldaki ilk uygulamayı yeni pencerede başlatmak için <kbd>Super</kbd>+<kbd>Ctrl</kbd>+<kbd>&lt;Sayı&gt;</kbd> kısayolunu artık kullanabilirsiniz.
* **Geliştirilmiş ekran klavyesi:** Ekran klavyesi, kendiliğinden büyük harf kullanımı, telefon numaraları, e-posta adresleri ve URL'lerin girilmesi için yeni klavye düzenleri ile geliştirildi.
* **Tıklamak İçin Dokun iyileştirildi:** Daha sezgisel bir dokunma deneyimi için *Tıklamak İçin Dokun* artık öntanımlı olarak etkinleştirildi.

## Daha İyi Uygulamalar

GNOME temel uygulamalarının bir çoğu da GNOME 46 için güncellendi:

* **Geliştirilmiş Yazılımlar uygulaması:** Yazılımlar, yazılımın güvenilir bir kaynaktan sağlandığını göstermek için geliştiricileri doğrulanmış Flathub uygulamaları için doğrulanmış rozetleri gösteriliyor. Yazılım uygulaması ayrıca yeniden tasarlanmış tercihler, daha iyi hata iletileri ve yeni klavye kısayolları penceresi içeriyor.
* **Çeşitli Haritalar iyileştirmeleri:**
   * Güncellenmiş OpenStreetMap ilgi noktası düzenleme deneyiminin yanı sıra kullanıcı arayüzü ve yönlendirme iyileştirmeleri.
   * Yeni harita biçemi ve karanlık kip desteği
   * Birden çok kat hakkında bilgi, bu katları olan ilgi noktaları için artık gösterilir
   * Genişletilmiş toplu taşıma yönlendirmesi (artık Norveç için kullanılabiliyor)
* **Yeniden Tasarlanmış Uzantılar uygulaması:** Daha temiz bir liste, kurulu uzantılarınızı tarayıp değiştirmeyi kolaylaştırır ve modernize edilmiş tasarım aynı zamanda uyarlanabilir. Kendiliğinden devre dışı bırakılan uzantıları kapatmak da artık mümkün.
* **Cilalanmış Takvim uygulaması:** Geliştirilmiş görseller, modernleştirilmiş arayüzler ve başarım iyileştirmeleri.
* **Saatlerde Hızlı Zamanlayıcılar:** Bir zamanlayıcı başlatırken, hızlı başlat bölümündeki bir süreye tıklayarak zamanlayıcıyı hızlıca başlatabilirsiniz.
* **Daha Akıllı Kişiler:** Birden çok VCard dosyası artık aynı anda içe aktarılabilir ve yeni kişiler içe aktarılırken, onay iletişim kutusu içe aktarılacak kişilerin adlarını da önizlemeye yardımcı olur.
* **Disk kullanımını izleme:** Diskler, disk G/Ç için yeni kaynak grafiği kazandı.

<picture class="rounded">
    <source srcset="/media/2024/03/software-screenshot-dark.png" media="(prefers-color-scheme: dark)">
    <img src="/media/2024/03/software-screenshot.png">
</picture>

## Kaputun Altındaki İyileştirmeler

GNOME 46'daki iyileştirmeler sadece yüzeyde değil, ve yeni sürüm daha başarımlı ve rafine deneyimle sonuçlanan derin teknik geliştirmelerle birlikte geliyor.

* **Başarım ve kaynak kullanımı iyileştirmeleri**, Arama için daha az bellek kullanımı, geliştirilmiş ekran kaydı başarımı ve *Resim Görüntüleyici* (loupe) uygulamasının sistem kaynaklarını daha akıllıca kullanımını içerir. GNOME uçbirim uygulamalarında da önemli hız iyileştirmeleri yapılmıştır.
* **Güvenlik iyileştirmeleri**, Resim görüntüleyici (loupe) uygulamasında ve GNOME arama teknolojilerinde kötü amaçlı yazılımlara karşı geliştirilmiş korumayı içerir.
* **Görüntüleme iyileştirmeleri**, Daha keskin uygulama arayüzleri, ekran üzerinde daha net metinler ve kesirli ekran ölçekleri kullanılırken daha net arayüzler içerir. Bu görüntüleme iyileştirmeleri, GTK'nin yeni işleyicileri sayesinde sağlanmış olup, en son GTK sürümünü kullanan GNOME uygulamaları için geçerlidir.
* **Değişken tazeleme hızları (VRR)**, Bazı durumlarda daha düzgün video başaramı sağlayabilen bir özelliktir. Bu, deneysel bir özellik olarak GNOME 46'da bulunur ve aşağıdaki komutu kullanarak komut satırından etkinleştirilmesi gerekir: ``gsettings set org.gnome.mutter experimental-features "['variable-refresh-rate']"``. Bir kez etkinleştirildikten sonra, değişken tazeleme hızı ekran ayarlarından ayarlanabilir.

## Yeni GNOME Çevre Dostları, Hoş Geldiniz!

[GNOME Çevre](https://circle.gnome.org/), GNOME projesinin teşvik ettiği ve desteklediği GNOME için bir grup fantastik uygulamadır. GNOME 45 yayınlandığından beri yedi yeni uygulama daha eklendi:

[![](/media/2024/03/io.github.mrvladus.List.svg)](https://apps.gnome.org/List/ "Errands")
[![](/media/2024/03/io.gitlab.gregorni.Letterpress.svg)](https://apps.gnome.org/Letterpress/ "Letterpress")
[![](/media/2024/03/io.gitlab.adhami3310.Converter.svg)](https://apps.gnome.org/Converter/ "Switcheroo")
[![](/media/2024/03/com.vixalien.decibels.svg)](https://apps.gnome.org/Decibels/ "Decibels")
[![](/media/2024/03/dev.bragefuglseth.Fretboard.svg)](https://apps.gnome.org/Fretboard/ "Fretboard")
[![](/media/2024/03/se.sjoerd.Graphs.svg)](https://apps.gnome.org/Graphs/ "Graphs")
[![](/media/2024/03/de.schmidhuberj.DieBahn.svg)](https://apps.gnome.org/DieBahn/ "Railway")

GNOME topluluğunun yeni üyelerine hoş geldiniz diyoruz!

## GNOME 46 Çeviri Durumu

GNOME 46 kullanıcı arayüzü, GNOME çevirmenlerinin üstün gayretleri ve süregiden emeklerinin bir meyvesi olarak %100 olarak Türkçe yayınlanmıştır. Belgelendirme çevirilerinin oranı %32’ye düşmüştür.

Çeviride karşılaştığınız hataları [anlık iletişim kanallarını](/anlik-iletisim-kanallari.html) kullanarak bildirmekten çekinmeyin.

## GNOME 46’yı Edinmek

GNOME bir [Özgür Yazılımdır](https://gnu.org/philosophy/free-sw.html): tüm [kodlarımız](https://gitlab.gnome.org/GNOME) indirilebilir ve ilgili lisanslara göre özgürce değiştirilebilir ve yeniden dağıtılabilir. Kurulumu için, resmi paketlerinizi beklemenizi ve dağıtımınız tarafından sağlanan paketleri kullanmanızı öneririz. Popüler dağıtımlar çok yakında GNOME 45 sürümünü kullanıma sunacaklar ve bazıları zaten yeni GNOME sürümünü içeren geliştirme sürümleri sunuyorlar. Ayrıca, [GNOME Kutular](https://apps.gnome.org/app/org.gnome.Boxes/) uygulamasını kullanarak sanal makine olarak [GNOME OS görüntüsünü](https://os.gnome.org/) deneyebilirsiniz.

## GNOME Hakkında

[GNOME Projesi](https://www.gnome.org/about/), kar amacı gütmeyen GNOME Vakfı tarafından desteklenen uluslararası bir topluluktur. Kullanıcı deneyimi mükemmeliyeti ve birinci sınıf uluslararasılaşma ve erişilebilirlik üzerinde odaklanıyoruz. GNOME, özgür ve açık bir projedir: bize katılmak isterseniz, [katılabilirsiniz](https://welcome.gnome.org/).

- - - - - -

**Not:** _[GNOME 46 Sürüm duyurusundan](https://release.gnome.org/46/), Deniz Kalma, DeepL, ChatGPT kullanılarak çevrilmiş, Sabri Ünal tarafından kimi ek açıklamalar eklenmiştir._

<iframe width="100%" height="405" src="https://www.youtube-nocookie.com/embed/r_QyRJf3rtQ" title="Introducing GNOME 46" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
