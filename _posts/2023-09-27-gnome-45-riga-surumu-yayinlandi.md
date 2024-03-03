---
title: 'GNOME 45, “Rīga” Sürümü Yayınlandı'
date: '2023-09-27T17:03:37+03:00'
author: 'GNOME Türkiye'
layout: post
permalink: /gnome-45-riga-surumu-yayinlandi/
enclosure:
    - "/media/2023/09/activities-loop.webm\r\n275689\r\nvideo/webm\r\n"
    - "/media/2023/09/loupe.webm\r\n10176419\r\nvideo/webm\r\n"
categories:
    - Haberler
tags:
    - GNOME
    - 'GNOME 45'
    - 'Linux Masaüstü Ortamı'
    - 'Yeni Sürüm'
---

![GNOME 45](/media/2023/09/45.webp "GNOME 45")

GNOME projesi, en son GNOME sürümü olan GNOME 45’i sunmaktan heyecan duyuyor. Yeni sürümde günlük etkileşimlerinizi geliştirmeye, başarımı arttırmaya ve genel deneyimi daha akıcı ve verimli kılmaya odaklandık. GNOME 45 özünde, ufak tasarım değişikliklerinden işlevsel yükseltmelere kadar güvendiğiniz temel masaüstü ortamını iyileştirmekle ilgilidir.

GNOME 45, bu yılki GUADEC konferansının düzenleyenlerce yapılan çalışmaların anısına “Rīga” kod adını taşıyor.. Yardım eden herkese teşekkür ederiz!

Gelin yenilikleri birlikte keşfedelim!

## Etkinlikler Göstergesi

<video class="wp-video-shortcode" controls="controls" height="142" id="video-556-1" preload="metadata" width="100%"><source src="/media/2023/09/activities-loop.webm?_=1" type="video/webm"></source></media/2023/09/activities-loop.webm></video>

GNOME 45’teki en dikkat çekici değişikliklerden biri yeni etkinlikler göstergesidir. Üst çubuğun sol köşesinde yer alan bu düğme daha önce “Etkinlikler” olarak etiketlenmişti. GNOME 45’te bu sabit yazının yerini dinamik çalışma alanı göstergesi aldı.

Yeni göstergenin tasarımı, son yıllarda yapılan kullanıcı testi sonuçlarına yanıt olarak geliştirildi ve yeni GNOME kullanıcıları için amacının daha açık olacağına inanıyoruz. Bu değişikliğin bir parçası olarak, (odaklanılan uygulamanın adını gösteren) eski uygulama menüsü (App Menü) de emekli edilip kullanımdan kaldırıldı. Bu da kullanıcı testi sonuçlarına yanıt olarak ve yeni tasarıma yer açmak için gerçekleştirildi.

## Hızlı Arama

Arama başarımı GNOME 45 için önemli çalışma alanlarından biri oldu. Başarım iyileştirmeleri “Yazılımlar”, “Karakterler”, “Saatler”, “Dosyalar” ve “Hesap Makinesi” de dahil bir dizi uygulamaya uygulandı. Tüm bu değişikliklerin sonucunda, hem tek tek uygulamalarda hem de sistem aramalarında gözlemlenebilen hız artışı yaşandı.

## Kamera Kullanım Göstergesi

GNOME 45 ile üst sistem çubuğuna eklenen yeni Kamera Göstergesi hoş bir eklenti oldu ve memnuniyetle karşılandı. Kamera kullanımda olduğunda gösterilen bu gösterge, bu sürümde biçemi de güncellenen önceki mikrofon göstergesine katılıyor.

Kamera kullanım göstergesi; ekran paylaşım ve kayıt göstergeleri, uygulama izinleri ile aygıt güvenlik ayarları da dahil olmak üzere diğer GNOME gizlilik özelliklerine katılan önemli bir gizlilik özelliğidir.

Bu gösterge yalnızca en son kamera teknolojilerini (yani, [**Pipewire**](https://pipewire.org)) kullanan uygulamalar için gösterilir.

## Yeni Sistem Özellikleri

![](/media/2023/09/super-s.webp)

GNOME 45, yeni sistem özellikleri ve iyileştirmeleri de içeriyor. Söz konusu özellikler şunlardır:

- **Klavye arka ışığı hızlı ayarı**: Hızlı ayarlar menüsü artık klavye arka ışıklarını denetlemek için bir düğme içeriyor.
- **Verimli video oynatma**: Mümkünse, GNOME artık video oynatırken donanım kaynaklarını kullanacak. Bu daha hızlıdır ve daha az güç tüketir.
- **Hızlı ayarlar için yeni klavye kısayolu**: Super+S kısayolu ile hızlı ayarlar menüsünü artık açıp kapatabilirsiniz.
- **Güncellenmiş işaretçi görselleri**: GNOME’un işaretçileri (imleçler olarak da bilinir) GNOME 45 ile harika yeni bir görünüm kazandı.
- **Açık sistem biçemi**: GNOME, öntanımlı koyu görünümün aksine sisteme açık görünüm kazandırmak için yeni bir seçenek sunuyor. Bu seçenek, ([**Light Theme uzantı**](https://extensions.gnome.org/extension/6198/light-style/)) kullanılarak ya da komut satırından aşağıdaki komut ile etkinleştirilebilir: ```
    gsettings set org.gnome.desktop.interface color-scheme prefer-light
    ```
    
    . Gelecek sürümler için daha fazla tümleştirme seçeneği araştırılmaktadır.
- **Yeni duvar kağıtları**: GNOME’un arka plan koleksiyonuna iki yeni güzel resim eklendi.
- [**Input Leap**](https://github.com/input-leap/input-leap) için Wayland desteği: Bu, birden fazla bilgisayarın tek bir klavye ve fareyle denetlenmesine izin veren KVM anahtarı benzeri işlevselliğin yazılım gerçeklemesini sağlar. GNOME 45, bu yazılımın modern Wayland oturumlarıyla kullanılabilmesine izin verir.
- **Daha düzgün işaretçi hareketi**: Başarım iyileştirmeleri, bilgisayar meşgulken bile işaretçinin düzgün şekilde hareket etmesini sağlar.

## Yeni Resim Görüntüleyici

<video class="wp-video-shortcode" controls="controls" height="450" id="video-556-2" preload="metadata" width="100%"><source src="/media/2023/09/loupe.webm?_=2" type="video/webm"></source></media/2023/09/loupe.webm></video>

GNOME 45, yeni bir öntanımlı resim görüntüleme uygulaması sunuyor. Hızı ve yalınlığı ile öne çıkan Loupe, resimleri hızlıca görüntülemenin yeni yolunu sunuyor. Bir resimden diğerine geçiş de yakınlaştırma ve döndürme işlemlerindeki gibi akıcı ve kusursuzdur.

Yeni resim görüntüleyici tümüyle uyarlanabilirdir ve mobil form faktörlerini destekler. Dokunmatik ekranda veya dokunmatik yüzeyde geri/ileri gezinmek için iki parmakla kaydırarak, yakınlaştırmak ve uzaklaştırmak için iki parmakla germek ya da iki parmakla çimdik, ya da resimleri döndürmek için ya da iki parmakla çevirmek de kullanılabilir.

Yeni resim görüntüleyicinin öne çıkan diğer özellikleri arasında, resim özellikleri kenar çubuğu, resimleri görüntülerken kolayca kopyalamak veya silmek için düğmeler, yerleşim üzerinde kolay denetime izin veren yazdırma penceresi yer alıyor.

## Yeni Kamera Uygulaması

Yeni resim görüntüleyiciye ek olarak, GNOME 45 ayrıca yeni kamera uygulaması Snapshot’ı da içeriyor. Snapshot uygulaması son derece yalın ve modern bir kullanıcı arayüzüne sahiptir ve tüm denetimler görüntüleme alanının üzerine yerleştirilmiştir. Yeni resim görüntüleyici gibi, yeni kamera uygulaması da hem mobil hem de masaüstünde harika çalışıyor.

![](/media/2023/09/snapshot-screenshot.webp)

Yeni kamera uygulaması, fotoğraf veya video çekebilme, farklı kameralar arasında geçiş düğmesi ve yeni çekilen fotoğraf ve videolara hızlıca bakabilmeniz için yerleşik görüntüleme işlevi de dahil bir dizi temel özellikle geliyor.

## Görünümleri Yenilenmiş Uygulamalar

Birçok temel GNOME uygulaması 45 sürümünde yeni arayüz bileşenleri kullanıyor. Bu yeni bileşenler hem yenilenmiş bir görünüm getiriyor hem de farklı pencere boyutları ve aygıt form faktörlerinde daha iyi çalışıyor.

Belirgin bir biçem değişikliği, pencerenin tam yüksekliğini kaplayan yeni kenar çubuklarıdır. Bunlar hem harika görünüyor hem de uyarlanabilirler: pencere genişliği değiştirdiğinizde uygulama düzeni kendiliğinden ayarlanıyor. Yeni kenar çubukları **Takvim**, **Karakterler**, **Saatler**, **Kişiler**, **Dosyalar** ve **Ayarlar** uygulamalarında görülebilir.

**Konsol**, **Metin Düzenleyici**, **Disk Kullanımı İnceleyici**, **Yazı Tipleri**, **Gezinti** ve **Web** dahil birçok temel uygulama da başlığı altındaki içerikten hafif bir gölgeyle ayıran güncellenmiş başlık çubuklarına GNOME 45 ile kavuştu.

**Takvim**, **Haritalar**, **Dosyalar** ve **Hesap Makinesi** uygulamalarındaki birçok küçük biçem güncellemesi de belirgin biçem değişikliklere eşlik ediyor.

[![](https://apps.gnome.org/icons/scalable/org.gnome.Console.svg)](https://apps.gnome.org/Console/ "Konsol")[![](https://apps.gnome.org/icons/scalable/org.gnome.TextEditor.svg)](https://apps.gnome.org/TextEditor/ "Metin Düzenleyici")[![](https://apps.gnome.org/icons/scalable/org.gnome.Calendar.svg)](https://apps.gnome.org/Calendar/ "Takvim")[![](https://apps.gnome.org/icons/scalable/org.gnome.Characters.svg)](https://apps.gnome.org/Characters/ "Karakterler")[![](https://apps.gnome.org/icons/scalable/org.gnome.clocks.svg)](https://apps.gnome.org/Clocks/ "Saatler")[![](https://apps.gnome.org/icons/scalable/org.gnome.Contacts.svg)](https://apps.gnome.org/Contacts/ "Kişiler")[![](https://apps.gnome.org/icons/scalable/org.gnome.baobab.svg)](https://apps.gnome.org/Baobab/ "Disk Kullanımı İnceleyici")[![](https://apps.gnome.org/icons/scalable/org.gnome.Nautilus.svg)](https://apps.gnome.org/Nautilus/ "Dosyalar")[![](https://apps.gnome.org/icons/scalable/org.gnome.font-viewer.svg)](https://apps.gnome.org/FontViewer/ "Yazı Tipleri")[![](https://apps.gnome.org/icons/scalable/org.gnome.Tour.svg)](https://apps.gnome.org/Tour/ "Gezinti")[![](https://apps.gnome.org/icons/scalable/org.gnome.Epiphany.svg)](https://apps.gnome.org/Epiphany/ "Web")

## Dosyalar Uygulaması İyileştirmeleri

**Dosyalar** uygulamasındaki arama üzerinde de çok çalışıldı. Bunun sonucunda uygulamada gözle görülür hız artışı sağlandı. Artık milyonlarca dosya içinde aranırken bile sonuçlar milisaniyeler içinde gösterilebiliyor. Dosya aramalarındaki diğer iyileştirmeler şunlandır:

- Arama sonuçlarının daha hızlı ve sorunsuz görüntülenmesi.
- Arama sonuçlarının daha kullanışlı ve tahmin edilebilir sıralanması.
- Arama kapsamını genişletmeye izin veren yeni düğmeler.

![](/media/2023/09/search-screenshot-dark.png)

Dosyalar’ın yeni sürümündeki diğer geliştirmeler arasında liste görünümünde hangi sütunların gösterileceğini seçmek için yeni pencere, liste görünümünde daha tutarlı tarih ve saat biçimleri, simge görünümünde yıldızlı dosyalar için göstergeler ve küçük resimlerin daha hızlı oluşturması yer alıyor.

## İyileştirilmiş Ayarlar

Ayarlar, GNOME 45’te bir dizi iyileştirme içeriyor:

- **Tarih ve Saat** ayarları artık üst çubuktaki saat ve tarihin biçimini yapılandırmak için seçenekler içeriyor. Daha önceden bu iş için GNOME İnce Ayar uygulamasının kullanılması gerekiyordu.
- **Gizlilik** ve **Paylaşım** alt sayfalarının tamamına eklenen açıklamalar ve kendiliğinden giriş ve yönetici kullanıcı ayarlarına eklenen bilgi baloncukları ile birçok ayarın anlaşılması artık çok daha kolay.
- **Erişilebilirlik**, arama girişinden daha iyi klavye gezinimi ile geliştirildi. Ayrıca, *Esc* tuşuyla artık daha fazla pencere kapatılabiliyor.
- **Hakkında** sayfasında yeni *Sistem Ayrıntıları* penceresi eklendi ve **Klavye** ayarlarından açılabilen yeni klavye düzeni görüntüleyicisi de dahil birçok ayar panelinin tasarımı iyileştirildi.

![](/media/2023/09/settings-date-format-screenshot-dark.png)

## Geliştirilmiş Uygulamalar

GNOME’un diğer temel uygulamaları da 45 sürümü için birçok yeni özellik ve iyileştirme içeriyor.

### Yazılımlar’da:

- Flatpak uygulaması kaldırılırken, artık uygulamanın verilerinin silinmesine izin veren bir seçenek gösteriliyor.
- Kullanılabilir yeterli uygulama olmadığında, uygulama gezgini arayüzü bunu telafi edecek şekilde ayarlandı.
- Oyunlar çalışırken güncellemelerin indirilmesi ve yüklenmesinden önlendi.

### Takvim’de:

- Ay görünümü artık aydan aya geçmek yerine her seferinde bir satır olacak şekilde sorunsuzca kaydırılabiliyor. Bu, nerede olduğunuzu kaybetmeden takviminize göz atmanıza imkan verir ve herhangi bir zamanda hangi tarihlerin ve etkinliklerin gösterileceği konusunda daha fazla esneklik sağlar.
- Takvimleri eşzamanlamak (F5), takvimler menüsünü açmak (F8) ve takvimleri yönetmek (Ctrl+Alt+M) için yeni klavye kısayolları eklendi.
- Arama artık daha geniş tarih aralığındaki etkinlikleri getiriyor.
- Ayrıca bir dizi başarım iyileştirmesi de yapıldı.

### Haritalar’da:

- Yönü gösteren ve haritayı kuzeye çevirmeyi sağlayan bir düğme eklendi.
- Arama açılır penceresinden yakındaki ilgi çekici noktaları keşfetmek de mümkün.
- Yakınlaştırma düğmeleri artık başlık çubuğunda değil, haritanın üzerinde yer alıyor.

### Diğer uygulamalardaki kimi geliştirmeler de şunlardır:

- **Bağlantılar** artık RDP bağlantılarını kullanırken uzak bilgisayar ile ana bilgisayar arasında metin, resim ve dosya kopyalamaya izin veriyor.
- **Konsol**, GNOME uçbirim uygulaması, özel yazı tipi ayarlama ve sistem uyarı sesini devre dışı bırakmak seçenekleri içeren yeni tercihler penceresine sahip.
- **Hesap Makinesi** Tayvan Doları, Ukrayna Grivnası, Nijerya Nairası ve Jamaika Doları dahil ek para birimlerini dönüştürebiliriyor.

## Yeni Çevre Uygulamaları

[**GNOME Çevre**](https://circle.gnome.org), GNOME projesinin teşvik ettiği ve desteklediği GNOME için bir dizi şahane uygulamadır. GNOME 44 sürümünün yayınlanmasından bu yana 6 yeni uygulama GNOME Çevre’ye eklendi. Bu uygulamaları ve temel özelliklerini şöyle sıralayabiliriz:

- [**Telegraph**](https://apps.gnome.org/Telegraph/), mors kodu çeviricisidir.
- [**Kartuşlar**](https://apps.gnome.org/Cartridges/), Steam, Lutris, Heroic ve çok daha fazlasını destekleyen bir oyun başlatıcıdır.
- [**Ear Tag**](https://apps.gnome.org/EarTag/), ses dosyası etiketleri düzenleyicisidir.
- [**Paper Clip**](https://apps.gnome.org/PdfMetadataEditor/), PDF üst veri düzenleyicisidir.
- [**Forge Sparks**](https://apps.gnome.org/ForgeSparks/), Github, Gitea ve Forgejo için bildirim uygulamasıdır.
- [**Impression**](https://apps.gnome.org/Impression/), disk görüntülerini çıkarılabilir sürücülere yazan bir uygulamadır.

## GNOME 45 Çeviri Durumu

GNOME 45 kullanıcı arayüzü, GNOME çevirmenlerinin üstün gayretleri ve süregiden emeklerinin bir meyvesi olarak %100 olarak Türkçe yayınlanmıştır. Belgelendirme çevirilerinde de ilerleme sağlanmış ve çeviri oranı %33’e ulaşmıştır. Bu artışta GNOME oyunları gibi çeşitli uygulamaların temel dağıtım paketinden çıkarılmasının da rolü büyüktür.

Çeviride karşılaştığınız hataları GNOME Türkiye Telegram kanalından bildirmekten çekinmeyin.

## GNOME 45’i Edinmek

GNOME bir [Özgür Yazılımdır](https://gnu.org/philosophy/free-sw.html): tüm [kodlarımız](https://gitlab.gnome.org/GNOME) indirilebilir ve ilgili lisanslara göre özgürce değiştirilebilir ve yeniden dağıtılabilir. Kurulumu için, resmi paketlerinizi beklemenizi ve dağıtımınız tarafından sağlanan paketleri kullanmanızı öneririz. Popüler dağıtımlar çok yakında GNOME 45 sürümünü kullanıma sunacaklar ve bazıları zaten yeni GNOME sürümünü içeren geliştirme sürümleri sunuyorlar. Ayrıca, [GNOME Kutular](https://apps.gnome.org/app/org.gnome.Boxes/) uygulamasını kullanarak sanal makine olarak [GNOME OS görüntüsünü](https://os.gnome.org/) deneyebilirsiniz.

## GNOME Hakkında

GNOME Projesi, kar amacı gütmeyen GNOME Vakfı tarafından desteklenen uluslararası bir topluluktur. Kullanıcı deneyimi mükemmeliyeti ve birinci sınıf uluslararasılaşma ve erişilebilirlik üzerinde odaklanıyoruz. GNOME, özgür ve açık bir projedir: bize katılmak isterseniz, katılabilirsiniz.

- - - - - -

**Not: [GNOME Sürüm duyurusundan](https://release.gnome.org/45/), Berk Elyesa Yıldırım ve Sabri Ünal tarafından çevrilmiştir. Kimi noktalara ek açıklamalar da eklenmiştir.**

<iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen="" frameborder="0" height="405" loading="lazy" src="https://www.youtube.com/embed/47aZgF6xmS0?feature=oembed" title="Introducing GNOME 45" width="100%"></iframe>