---
layout: default
image: 46.png
languages: languages_46
urlprepend: "../"
redirect_from:
- /latest
- /stable
---

# GNOME&nbsp;46, "Katmandu" ile tanışın

**Mart 20, 2024**

GNOME projesi, en son GNOME sürümü olan 46. sürümü sunmaktan heyecan duymaktadır. Bu son sürüm, GNOME topluluğunun 6 aylık sıkı çalışmasının sonucudur. Katkıda bulunan herkese teşekkür ederiz!

GNOME 46, GNOME.Asia 2023 organizatörleri tarafından yapılan harika çalışmaların anısına "Katmandu" kod adını taşıyor.

Hadi içeri dalalım ve GNOME 46'daki yenilikleri keşfedelim.

## Her Yerde Arama Yapın

Files, GNOME 46'da yeni **küresel arama özelliği** ile birlikte gelir. Bu özellik basittir: yeni arama düğmesini tıklatarak veya <kbd>Ctrl</kbd>+<kbd>Shift</kbd> tuşlarını kullanarak etkinleştirin. >+<kbd>F</kbd> kısayoluna tıklayın, ardından tüm yapılandırılmış arama konumlarınızı aramak için sorgunuzu girin.

Küresel arama, istediğiniz öğelerin nerede olduğunu düşünmek zorunda kalmadan doğrudan aramaya atlamak için harika bir yoldur. Yeni özellik aynı zamanda GNOME'un dosya içeriğini arama ve dosya türü ve değişiklik tarihine göre filtreleme gibi mevcut dosya arama özelliklerinden de yararlanıyor.

Genel aramanın bir başka güzel yanı da, aynı anda birden fazla konumda arama yapmayı mümkün kılmasıdır; bu konumlar ev dizininizde olmayan konumları da içerebilir. Bunu ayarlamak için, yeni rafine edilmiş arama konumları ayarlarına gidin ve dahil edilmesini istediğiniz konumları ekleyin.

<picture class="full">
    <source media="(min-width: 800px) and (prefers-color-scheme: light)" srcset="search-everywhere-large.svg">
    <source media="(min-width: 800px) and (prefers-color-scheme: dark)" srcset="search-everywhere-large-dark.svg">
    <source media="(prefers-color-scheme: dark)" srcset="search-everywhere-dark.svg">
    <img src="search-everywhere.svg">
</picture>


## İyileştirilmiş Files Uygulaması

Genel aramaya ek olarak, Files uygulaması GNOME 46 için ciddi bir yükseltmeye sahip oldu. Kenar çubuğunun altındaki yeni bir dinamik ilerleme bölümü ile uzun süren dosya işlemleri hakkında geri bildirim iyileştirildi. Bu, tek tek işlemlerin ilerlemesini görüntülemenin yanı sıra hangi işlemlerin devam ettiğini ve hangilerinin bittiğini görmeyi mümkün kılıyor.

<picture class="rounded">
    <source srcset="file-ops-screenshot-dark.png" media="(prefers-color-scheme: dark)">
    <img src="file-ops-screenshot.png">
</picture>

GNOME 46'nın iyileştirilmesi sırasında kodun önemli ölçüde yeniden düzenlenmesi, Files uygulamasında da memnuniyet verici bir performans yükseltmesi sağladı. Geçmişte, liste ve ızgara görünümü arasında geçiş yapmak bir gecikme içerirdi ve içerik ekrana aşamalı olarak yüklenirdi. GNOME 46'da bu durum ortadan kalktı: görünümü değiştirmek anında gerçekleşiyor ve daha hızlı ve sorunsuz bir deneyim sunuyor.

<video nocontrols muted autoplay loop class="rounded">
  <p>Dosyalar 46: Izgara ve liste görünümleri arasında geçiş yaparken performans iyileştirildi. Files 45, görünümü her seferinde yeniden yüklemek için kullanılır.</p>
  <source src="files-46.webm" type="video/webm">
  <source src="files-46.mp4" type="video/mp4">
</video>

Son olarak, GNOME 46'daki Files, fantastik bir dizi başka küçük iyileştirmeyle birlikte geliyor:

* **Tercihler için arama:** Artık belirli ayarları bulmak için Files tercihleri içinde arama yapabilirsiniz.
* **Detaylı tarih ve saat:** Files tercihleri artık tarih ve saati daha kapsamlı ve tutarlı bir biçimde gösteren bir seçenek içeriyor.
* **Tıklandığında konum girişi:** Dosya yolu alanına tıklayarak dosya konumu adres çubuğuna hızlıca erişin.
* **Izgara görünümünde yıldızlı favoriler:** Izgara görünümünde görsel işaretçilerle yıldızlı dosyalarınızı hızlı bir şekilde tanımlayın ve bunlara erişin.
* **İyileştirilmiş ağ keşfi:** Diğer Konumlar görünümünde artık daha fazla kullanılabilir ağa bağlı cihaz görünüyor.

Files'daki yeni özellikleri keşfetmenizi ve yepyeni bir dosya yönetimi verimliliği düzeyini deneyimlemenizi öneririz!

## Yükseltilmiş Çevrimiçi Hesaplar Artık OneDrive'da

GNOME'un Çevrimiçi Hesaplar özelliği, GNOME 46 için büyük bir yükseltmeye sahip oldu. En büyük iyileştirme **Microsoft OneDrive için yeni bir destek**. Ayarlardan bir Microsoft 365 hesabı oluşturduğunuzda OneDrive'ınız Files kenar çubuğunda görünecek ve burada yerel dosya ve klasörlerinizin yanında kolayca taranıp erişilebilecektir.

[Egemen Teknoloji Fonu](https://foundation.gnome.org/2023/11/09/gnome-recognized-as-public-interest-infrastructure/) tarafından sağlanan finansman sayesinde Çevrimiçi Hesaplarda bir dizi ek iyileştirme de yapılmıştır:

* Hesap kurulumunun bir parçası olarak hesaplarda oturum açarken artık varsayılan web tarayıcısı kullanılıyor. Bu, USB belirteçleri gibi **daha geniş bir kimlik doğrulama yöntemi** yelpazesinin kullanılmasına olanak tanır.
* Çevrimiçi kişileri, takvimleri ve dosyaları GNOME deneyiminize entegre etmek için genel bir yöntem sağlayan yeni bir **WebDAV hesap türü** eklendi.
* **Çevrimiçi Hesaplar** ayarları da tamamen yenilendi ve artık modern ve güncel tasarımlara sahip.

Bu değişikliklerin gerekli bir sonucu, Çevrimiçi Hesapların artık ilk sistem kurulum asistanının bir parçası olarak dahil edilmemesidir.

## RDP ile Uzaktan Oturum Açma

GNOME'un uzak masaüstü deneyimi, yeni bir **özel uzaktan oturum açma seçeneği** ile 46 sürümü için önemli ölçüde iyileştirilmiştir. Bu, halihazırda kullanımda olmayan bir GNOME sistemine uzaktan bağlanmaya izin verir. Bu şekilde bağlanmak, sistemin ekranının uzak taraftan yapılandırılabileceği anlamına gelir ve uzak kullanıcı için daha iyi bir deneyim sağlar.

Yeni uzaktan oturum açma özelliği, GNOME sistemlerinin tam teşekküllü uzak kaynaklar olarak kullanılabileceği anlamına gelmektedir. Nasıl bağlanılacağı hakkında bilgi veren Uzak Masaüstü ayarlarında bulunabilir.

<picture>
    <source srcset="remote-screenshot-dark.png" media="(prefers-color-scheme: dark)">
    <img src="remote-screenshot.png">
</picture>

## İyileştirilmiş Ayarlar

Ayarlar uygulaması GNOME 46'da kapsamlı bir güncelleme aldı.

### Navigasyon İyileştirmeleri

Ayarlar uygulaması, GNOME 46 için **gezinmesi daha kolay** olacak şekilde yeniden düzenlenmiştir. Bu amaçla, *Bölge ve Dil*, *Tarih ve Saat*, *Kullanıcılar*, *Uzak Masaüstü*, *Güvenli Kabuk* ve *Hakkında* için tercihleri içeren yeni bir Sistem bölümü oluşturuldu. Uygulamalar ayarları da birleştirildi ve artık Varsayılan Uygulamalar ve Çıkarılabilir Medya ayarlarını içeriyor.

Bu değişiklikler, Ayarlar uygulamasındaki toplam bölüm sayısını azaltarak size göz atmanız gereken daha az yer ve ihtiyacınız olan ayarlara daha hızlı bir yol sunuyor.

### Yeni Touchpad Ayarları

Touchpad ayarları GNOME 46 için iki yeni ayarla genişletildi. Birincisi, **İkincil Tıklama** olarak adlandırılan, ikincil tıklamaların (genellikle "sağ tıklama" olarak adlandırılır) touchpad ile nasıl gerçekleştirileceğine ilişkin yapılandırma sağlar ve ped üzerinde iki parmağı kullanma veya pedin köşesine tıklama seçeneklerini içerir.

İkinci yeni ayar **Yazarken Dokunmatik Yüzeyi Devre Dışı Bırak** davranışının kapatılmasını sağlar. Bunu yapmak, touchpad hareketinin bazı uygulamalar ve oyunlar için gerekli olabilen tuşlara basma ile birleştirilmesine olanak tanır.

### Muazzam Polonya Çabası

Ayarlar uygulaması da GNOME 46 için büyük miktarda cila aldı. Buna şunlar dahildir:

* İyileştirilmiş ayar açıklamaları ve araç ipuçları
* Klavye gezinmesini iyileştirmek için daha fazla klavye anımsatıcısı (bunları görmek için Alt tuşuna basılı tutun)
* Kapsamlı kullanıcı arayüzü modernizasyonu ve iyileştirmesi
* Tuş ataması oluşturmak için ek seçenekler
* Görünüm ayarlarının daha hızlı yüklenmesinin yanı sıra daha keskin önizlemeler
* Wacom kalem basıncını ayarlarken ek ince taneli kontrol

Tüm bu iyileştirmeler sonucunda daha net, anlaşılması daha kolay ve kullanımı harika bir Ayarlar uygulaması ortaya çıktı.

## Erişilebilirlik İyileştirmeleri

Erişilebilirlik, GNOME 46 için güçlü bir çalışma teması oldu ve erişilebilirliğin birçok yönü iyileştirmeler gördü. Bu çalışmaların çoğu Orca ekran okuyucusuna odaklanmıştır:

* Kaputun altında **önemli bir modernizasyon çalışması** yürütülüyor. Bu, performansın ve güvenilirliğin artmasını sağlayacak ve gelecekte Wayland ve korumalı alan uygulamalarıyla uyumluluğu mümkün kılacaktır.
* **Yeni bir uyku modu** özelliği eklendi. Çok istenen bu özellik, kullanıcıların <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Q</kbd> kısayolunu kullanarak Orca'yı geçici olarak devre dışı bırakmasına olanak tanır. Uyku modu, kendi ekran okuyucularına sahip sanal makinelerin yanı sıra kendi kendini seslendiren uygulamaları kullanırken kullanışlıdır.
* Yeni komutlar Orca'nın pil durumu, CPU ve bellek kullanımı da dahil olmak üzere **sistem durumunu** rapor etmesine olanak tanır.
* **Tabloda gezinme**, daha fazla uygulamanın desteklenmesi ve tablo gezinmesini değiştirme dahil yeni komutların eklenmesiyle çok daha iyileştirildi (<kbd>Orca</kbd>+<kbd>Shift</kbd>+<kbd>T</kbd>) ve son bölüme gidin (<kbd>Orca</kbd>+<kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>🡰</kbd>/<kbd> 🡲</kbd>/<kbd>🡱</kbd>/<kbd>🡳</kbd>).
* Orca artık heyecan verici bir yeni nesil konuşma sentezi API'si olan **Spiel** için deneysel desteğe sahip. Bu özellikle ilgilenenler [test edilmesine yardımcı olmaya davetlidir](https://gitlab.gnome.org/GNOME/orca#experimental-features).

Orca, GNOME 46 için erişilebilirlik iyileştirmelerinin yapıldığı tek yer olmadı. Diğer erişilebilirlik iyileştirmeleri arasında artık daha tutarlı ve kullanılabilir olan **yüksek kontrast modu** ve **anahtarlarda açık ve kapalı sembolleri göstermek için yeni bir ayar** yer alıyor.

Bu erişilebilirlik çalışmasının büyük bir kısmı [Sovereign Tech Fund](https://foundation.gnome.org/2023/11/09/gnome-recognized-as-public-interest-infrastructure/) ve [Igalia](https://www.igalia.com/) tarafından finanse edilmiştir.

## Sistem İyileştirmeleri

GNOME 46, çekirdek GNOME deneyiminde birçok küçük iyileştirme ve değişiklikler içeriyor:

* **Güzel yedek avatarlar:** Kullanıcı hesabınız için bir avatar belirtmezseniz, GNOME sizin için bir tane oluşturur. Bu yedek avatarlar 46 için yenilendi ve harika görünüyor. Önceki bir sürümden yükseltme yapıyorsanız, yeni varsayılan avatarları çalışırken görmek için eski avatarınızı temizleyin.
* **İyileştirilmiş bildirimler:** İyileştirilmiş düzenler ve her bildirimde hangi uygulamanın gönderdiğini gösteren yeni bir başlık. Bildirim eylemlerini size uygun bir zamanda kullanmak için artık listedeki bildirimleri genişletmek de mümkün.

![Enhanced Notifications](notifications-screenshot.png){:.rounded}

* **Yeni uygulama penceresi kısayolu:** Kontrol paneline sabitlenmiş uygulamalar zaten <kbd>Super</kbd>+<kbd>&lt;Number&gt;</kbd> kullanılarak başlatılabilir. Örneğin, <kbd>Super</kbd>+<kbd>1</kbd>, kontrol panelindeki ilk uygulamayı başlatacaktır. GNOME 46 artık <kbd>Ctrl</kbd> değiştiricisini ekleyerek yeni bir pencere açmaya izin veren ek kısayollar içeriyor; örneğin: <kbd>Super</kbd>+<kbd>Ctrl</kbd>+<kbd> Kontrol panelindeki ilk uygulama için yeni bir pencere açmak için &lt;Number&gt;</kbd>'a basın.
* **Geliştirilmiş ekran klavyesi:** Otomatik büyük harf kullanımı ve telefon numaraları, e-posta adresleri ve URL'leri girmek için yeni klavye düzenleri.
* **Tıklamak için dokunma artık varsayılan olarak etkin:** Daha sezgisel bir dokunma deneyimi için.

## Daha İyi Uygulamalar

GNOME'un çekirdek uygulamalarının birçoğu da GNOME 46 için yükseltildi. Buna şunlar dahildir:

* **Geliştirilmiş Yazılım uygulaması:** artık geliştiricileri doğrulanmış Flathub uygulamaları için doğrulanmış rozetleri göstererek yazılımınız için güvenilir bir kaynak sağlar. Yazılım uygulaması ayrıca yeniden tasarlanmış tercihlere, daha iyi hata mesajlarına ve yeni bir klavye kısayolları penceresine sahiptir.
* **Çeşitli Haritalar iyileştirmeleri:**
   * Güncellenmiş OpenStreetMap ilgi noktası düzenleme deneyiminin yanı sıra diğer kullanıcı arayüzü ve yönlendirme iyileştirmeleri
   * Yeni harita stili ve karanlık mod desteği
   * Birden fazla kata ilişkin bilgiler artık bu katlara sahip ilgi noktaları için gösterilmektedir
   * Genişletilmiş toplu taşıma yönlendirmesi (artık Norveç için mevcut)
* **Yeniden Tasarlanan Uzantılar uygulaması:** Daha temiz bir liste, yüklü uzantılarınızı taramayı ve değiştirmeyi kolaylaştırır ve modernize edilmiş tasarım da uyarlanabilir. Artık otomatik olarak devre dışı bırakılan uzantıları kapatmak da mümkün.
* **Gösterişli Takvim uygulaması:** İyileştirilmiş görseller, modernleştirilmiş arayüzler ve performans iyileştirmeleri.
* **Saatlerdeki hızlı zamanlayıcılar:** Bir zamanlayıcı başlatırken, hızlı başlatma bölümündeki bir süreye tıklayarak zamanlayıcıyı hızlıca başlatabilirsiniz.
* **Daha Akıllı Kişiler:** Birden fazla VCard dosyası artık aynı anda içe aktarılabilir ve yeni kişiler içe aktarılırken, onay iletişim kutusu içe aktarılacak kişilerin adlarını da yardımcı bir şekilde önizleyecektir.
* **Disk kullanımını izleyin:** Diskler, disk G/Ç için yeni bir kaynak grafiği kazandı.

<picture>
    <source srcset="software-screenshot-dark.png" media="(prefers-color-scheme: dark)">
    <img src="software-screenshot.png">
</picture>

## Kaputun Altındaki İyileştirmeler

GNOME 46'daki iyileştirmeler sadece dış görünüşle sınırlı değil ve yeni sürüm, daha performanslı ve rafine bir deneyimle sonuçlanan derin teknik iyileştirmelerle birlikte geliyor.

* **Performans ve kaynak kullanımı iyileştirmeleri:** Arama için daha az bellek kullanımı, gelişmiş ekran kayıt performansı ve resim görüntüleyici uygulaması tarafından sistem kaynaklarının daha akıllı kullanımı dahil. GNOME'un terminal uygulamalarında da önemli hız iyileştirmeleri yapılmıştır.
* **Güvenlik iyileştirmeleri:** Resim görüntüleyici uygulamasında ve GNOME'un arama teknolojilerinde kötü amaçlı yazılımlara karşı gelişmiş koruma içerir.
* **Rendering iyileştirmeleri:** Daha keskin uygulama arayüzleri, daha net ekran metinleri ve kesirli ekran ölçekleri kullanıldığında daha net kullanıcı arayüzleri içerir. Bu işleme iyileştirmeleri GTK'nın yeni işleyicileri sayesindedir ve en son GTK sürümünü kullanan GNOME uygulamalarında bulunur.
* **Değişken yenileme hızları (VRR):** bazı durumlarda daha akıcı video performansı üretebilen bir özelliktir. Bu, GNOME 46'ya deneysel bir özellik olarak dahil edilmiştir ve komut satırından aşağıdakileri girerek etkinleştirilmesi gerekir: ``gsettings set org.gnome.mutter experimental-features "['variable-refresh-rate']"``. Etkinleştirildikten sonra, ekran ayarlarından değişken bir yenileme hızı ayarlanabilir.

## Welcome, Circle Friends!

[GNOME Circle](https://circle.gnome.org/), GNOME projesinin teşvik ettiği ve desteklediği GNOME için bir grup fantastik uygulamadır. GNOME 45 yayınlandığından beri yedi yeni uygulama eklenmiştir:

- [![Errands](io.github.mrvladus.List.svg){: .icon-dropshadow} <br>Errands](https://apps.gnome.org/List/)
- [![Letterpress](io.gitlab.gregorni.Letterpress.svg){: .icon-dropshadow} <br>Letterpress](https://apps.gnome.org/Letterpress/)
- [![Switcheroo](io.gitlab.adhami3310.Converter.svg){: .icon-dropshadow} <br>Switcheroo](https://apps.gnome.org/Converter/)
- [![Decibels](com.vixalien.decibels.svg){: .icon-dropshadow} <br>Decibels](https://apps.gnome.org/Decibels/)
- [![Fretboard](dev.bragefuglseth.Fretboard.svg){: .icon-dropshadow} <br>Fretboard](https://apps.gnome.org/Fretboard/)
- [![Graphs](se.sjoerd.Graphs.svg){: .icon-dropshadow} <br>Graphs](https://apps.gnome.org/Graphs/)
- [![Railway](de.schmidhuberj.DieBahn.svg){: .icon-dropshadow} <br>Railway](https://apps.gnome.org/DieBahn/)
{: .icon-grid}

GNOME topluluğunun bu yeni üyelerine hoş geldiniz!

## Geliştirici Deneyimi

GNOME 46, GNOME platformunu kullanan geliştiriciler için yeni özellikler ve iyileştirmeler içeriyor. Daha fazla bilgi edinmek için geliştiriciler bölümünü okuyun.

<ul class="linkdiv">
  <li>
    <a href="developers/index.html"><span class="title">Geliştiriciler için Yenilikler</span>
    <span class="description">GNOME teknolojileri ile çalışanlar için yeni özellikler.</span>
    </a>
  </li>
</ul>

## GNOME 46'yı Edinme

GNOME'un yazılımı [Özgür Yazılımdır](https://gnu.org/philosophy/free-sw.html): tüm [kaynak kodu](https://gitlab.gnome.org/GNOME) indirilebilir ve ilgili lisanslara göre serbestçe değiştirilir ve yeniden dağıtılır. Yüklemek için satıcınız veya dağıtımınız tarafından sağlanan resmi paketleri beklemenizi öneririz. Popüler dağıtımlar GNOME 46'yı çok yakında kullanıma sunacak ve bazılarının halihazırda yeni GNOME sürümünü içeren geliştirme sürümleri var. Ayrıca [Boxes](https://apps.gnome.org/Boxes/) uygulamasını kullanarak [GNOME OS imajını](https://os.gnome.org/) sanal makine olarak deneyebilirsiniz.

## GNOME Hakkında

[GNOME Projesi] (https://www.gnome.org/about/) kar amacı gütmeyen bir Vakıf tarafından desteklenen uluslararası bir topluluktur. Kullanıcı deneyimi mükemmelliğine ve birinci sınıf uluslararasılaştırma ve erişilebilirliğe odaklanıyoruz. GNOME ücretsiz ve açık bir projedir: eğer bize katılmak isterseniz, [katılabilirsiniz](https://welcome.gnome.org/).
