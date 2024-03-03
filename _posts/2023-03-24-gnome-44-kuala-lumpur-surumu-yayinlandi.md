---
title: 'GNOME 44, “Kuala Lumpur” Sürümü Yayınlandı'
date: '2023-03-24T22:31:07+03:00'
author: 'GNOME Türkiye'
layout: post
permalink: /gnome-44-kuala-lumpur-surumu-yayinlandi/
categories:
    - Haberler
tags:
    - GNOME
    - 'GNOME 44'
    - 'Linux Masaüstü Ortamı'
    - 'Yeni Sürüm'
---

![GNOME 44](/media/2023/03/44.webp "GNOME 44")

6 aylık sıkı çalışmanın ardından, GNOME geliştiricileri ve katkıcıları olarak GNOME masaüstü ortamının 44. sürümünü sunmaktan gurur duyuyoruz. Bu son sürüm, yeni özellikler, yeni geliştirmeler ve birçok hata düzeltme ve önemli iyileştirmeler içeriyor. Öne çıkanlar arasında Ayarlar uygulamasındaki önemli geliştirmeleri, iyileştirilmiş “Hızlı Ayarlar” menüsü ve akıcı Yazılımlar uygulaması bulunuyor. Daha çok detay aşağıdaki sürüm notlarında bulunmaktadır.

GNOME 44, GNOME.Asia 2022 organizatörlerinin yaptığı çalışmaların tanınması için “Kuala Lumpur” kod adını taşımaktadır.

## Dosya Seçici Izgara Görünümü

![](/media/2023/03/file-chooser-screenshot.png)

GNOMEʼun dosya seçici iletişim kutuları yalnızca liste görünümüne izin veriyordu. Dosyayı adıyla seçmek istediğinizde kullanışlı olsa da dosyaları küçük resimlerine göre seçmek istediğinizde bu yöntem verimsiz kalıyordu. Bu sebeple, yıllardır GNOME kullanıcıları, dosya seçicisine ızgara görünümünün eklenmesini defalarca dile getirdiler.

GNOME 44 ile bu istek sonunda karşılandı. Bu, GNOME tarihindeki en olumlu karşılanan değişikliklerden biri oldu, bu sebeple beğeneceğinize eminiz!

Yeni ızgara görünümü, GTK4 kullanan dosya seçicilerde bulunmaktadır. Bazı uygulamalar, yeni ızgara görünümünü kullanmayan eski GTK3 sürümü dosya seçicisini kullanabilir.

## Ayarlar Panelleri Güncellendi

GNOME 44, GNOME Ayarlar uygulaması için büyük bir sürümdür ve dört ayar paneli yeni sürüm için yeniden tasarlanmıştır.

### Aygıt Güvenliği

![](/media/2023/03/device-security-screenshot.png)

Aygıt Güvenliği, GNOME 43 ile Ayarlar uygulamasına ilk defa eklenmişti. O zamandan sonra önemli bir güncelleme alıyor.

Yeni sürüm, aygıtın güvenlik durumunu “Denetimler Başarısız”, “Denetimler Başarılı” ya da “Korumalı” gibi bir açıklamayla gösterir. Bu değişiklikle panel daha anlaşılır bir şekle dönüştürülmüştür.

Teknik ayrıntılara inmek isteyenler ya da aygıtların güvenliğiyle ilgili sorun bildirmek isteyenler için, yeni bir özellik aygıt için tam güvenlik raporu oluşturur. Bu, arka planda neler olup bittiği hakkında genel görünüm sağlar ve sorun raporlarına ve destek taleplerine kolayca kopyalanabilir.

### Erişilebilirlik

![](/media/2023/03/accessibility-screenshot.png)

GNOMEʼun erişilebilirlik ayarları GNOME 44 için yeniden tasarlandı. Ayarların farklı bölümleri daha kolay gezinilebilmesi için ayrıldı. Ayrıca, bağımsız ayarların tasarımı, diğer ayarlarla daha tutarlı ve daha net olacak şekilde iyileştirildi. Ayrıca, birçok ayara açıklama eklendi.

Yeni erişilebilirlik ayarları ayrıca kimi yeni özellikler içeriyor:

- Ses düzeyini normal eşikten çok artırmak için yeni aşırı yükseltme ayarı eklendi.
- Yazarken, erişilebilirlik özelliklerini klavye ile etkinleştirme seçeneği eklendi.
- İmleç yanıp sönmesi ayarı için sınama alanı eklendi.
- Kaydırma çubuklarını her zaman göstermek için Görme bölümüne yeni ayar eklendi.

### Ses

![](/media/2023/03/sound-screenshot.png)

GNOMEʼun ses ayarları da son sürümden sonra iyileştirildi ve genel olarak kullanımı çok daha kolay hale getirdi:

- Ses düzeyi denetimi, daha yaygın kullanılan girdi ve çıktı denetimlerine daha kolay erişilebilmesi için ayrı pencereye taşındı.
- Uyarı sesini devre dışı bırakmak artık mümkün ve yeni uyarı sesi penceresi var olan sesleri kolayca gözden geçirmeyi sağlıyor.
- Ses sınama penceresi, çoklu çıkışlarla ilgili ölçekleme sorunlarını ortadan kaldırmak ve görsel açıdan daha çekici bir arayüz sağlamak için yeniden tasarlandı.

Ses ayarları, yeni ses düzeyi göstergeleri ve eksik aygıtların daha iyi sunumu gibi diğer geliştirmeler de dahil olmak üzere bir dizi diğer iyileştirme de içeriyor.

### Fare ve Dokunmatik Yüzey

![](/media/2023/03/mouse-and-touchpad-screenshot.png)

Fare ve Dokunmatik Yüzey ayar paneli de GNOME 44 için yeniden tasarlananmıştır. En belirgin değişiklik, farklı kullanım biçimlerini gösteren videoların eklenmesidir.  
Bu videolar harika görünmelerinin yanında çeşitli ayarların daha anlaşılır olmasını sağlar

Fare ve Dokunmatik Yüzey ayarlarındaki diğer geliştirmeler, yeni sınama penceresi, yeni Fare Hızlandırma ayarı ve farklı kaydırıcılardaki işaretleme imleridir.

## Hızlı Ayarlar İyileştirildi

Hızlı ayarlar menüsü, önceki sürümde yeni bir özellik olarak tanıtılmıştı ve sonrasında daha da geliştirildi:

- Bluetooth hızlı ayar düğmesine menü eklendi. Bu menü, hangi aygıtların bağlı olduğunu göstermenin yanı sıra aygıtları bağlamaya ve bağlantılarını kesmeyi de sağlıyor.
- Menü, açık pencere olmadan çalıştıkları algılanan uygulamaların listesini artık gösteriyor. Bu özellik, belirli bir uygulamanın arka planda çalışıp çalışmadığını denetlemeyi sağlıyor. Şimdilik, arka plandaki uygulamalar listesinde sadece Flatpak uygulamaları bulunuyor.
- Hızlı ayar değiştirme düğmelerinin her birine açıklama eklendi. Bu şekilde, her ayarın durumunu daha ayrıntılı şekilde gösteriliyor.

## Yazılımlar Uygulaması Artık Daha Akıcı

Yazılımlar uygulaması GNOME 44 altında artık daha akıcı ve daha hızlı bir deneyim sunuyor. Yazılım kategorileri artık daha hızlı görüntüleniyor, bu sayede kesintisiz gezinebilirsiniz. Sayfaların yeniden yüklenmesi de azaltıldı.

Uygulama ayrıca, gelecek nesil yazılım biçimleri için geliştirilmiş destek sunuyor: Flatpak çalışma ortamları artık gerek kalmadığından kendiliğinden kaldırılıyor, böylece disk alanından tasarruf sağlanıyor. Ayrıca görüntü tabanlı işletim sistemi güncellemeleri artık ilerleme bilgisi ve açıklama içeriyor.

Son olarak, Yazılımlar uygulamasının bu sürümü, daha iyi görünen incelemeler ve hata mesajları gibi bir dizi kullanıcı arayüzü iyileştirmesi içerir.

## Dosyalar Uygulamasındaki İyileştirmeler

Dosyalar, GNOME 44 için bir dizi iyileştirme ile birlikte geliyor:

- Dosyalar GTK4ʼe dönüştürüldüğünde, liste görünümünde klasörleri genişletme seçeneği (önceki sürüme yetişmediği için geçici olarak) kaldırılmıştı. GNOME 44 ile, bu seçenek tekrar kullanıma sunuldu. Tercihlerden etkinleştirildiğinde, klasör içeriğini içine girmeden görüntülemeyi sağlar. Bu, özellikle iç içe klasörleri hızlıca keşfetmek için oldukça kullanışlıdır.
- Sekmelere, yeni pencerelere sekme taşıma seçeneği de dahil olmak üzere ek seçenekler eklendi. Ayrıca ögeleri sekme üzerine sürüklemek de mümkün.
- Son olarak, ızgara görünümü boyutları artırıldı.

## Ayarlar Uygulamasındaki Diğer İyileştirmeler

GNOME 44ʼte yeniden düzenlenen çeşitli ayar panellerine ek olarak, Ayarlar uygulamasında pek çok küçük iyileştirme de yapılmıştır:

- Kablosuz (Wi-Fi) ayarlarında, QR kodu kullanarak Kablosuz Bağlantı şifresi paylaşma özelliği eklendi.
- Hakkında bölümüne Çekirdek (Linux Kernel) ve Donanım Yazılımı (firmware) sürüm bilgileri de eklendi.
- Thunderbolt ayarları, sadece Thunderbolt donanımı varsa gösteriliyor.
- Ağ ayarlarında, Wireguard VPNʼleri eklemek ve yapılandırmak artık mümkün.

### Yeni Çevre Üyeleri

GNOME Çevre, GNOME Projesiʼnin parçası olarak geliştirilen harika bir uygulama derlemesidir. GNOME 43ʼün yayınlanmasından bu yana 10 yeni uygulama aramıza katıldı:

[![](https://apps.gnome.org/icons/scalable/fr.romainvigier.zap.svg)](https://apps.gnome.org/app/fr.romainvigier.zap "Zap")[![](https://apps.gnome.org/icons/scalable/com.feaneron.Boatswain.svg)](https://apps.gnome.org/app/com.feaneron.Boatswain "Boatswain")[![](https://apps.gnome.org/icons/scalable/org.gnome.design.Emblem.svg)](https://apps.gnome.org/app/org.gnome.design.Emblem/ "Emblem")[![](https://apps.gnome.org/icons/scalable/org.gnome.design.Lorem.svg)](https://apps.gnome.org/app/org.gnome.design.Lorem "Workbench")[![](https://apps.gnome.org/icons/scalable/re.sonny.Workbench.svg)](https://apps.gnome.org/app/re.sonny.Workbench "Workbench")[![](https://apps.gnome.org/icons/scalable/info.febvre.Komikku.svg)](https://apps.gnome.org/en/app/info.febvre.Komikku/ "Komikku")[![](https://apps.gnome.org/icons/scalable/com.clarahobbs.chessclock.svg)](https://apps.gnome.org/app/com.clarahobbs.chessclock/ "Chess Clock")[![](https://apps.gnome.org/icons/scalable/com.github.finefindus.eyedropper.svg)](https://apps.gnome.org/app/com.github.finefindus.eyedropper/ "Eyedropper")[![](https://apps.gnome.org/icons/scalable/app.drey.Elastic.svg)](https://apps.gnome.org/en-GB/app/app.drey.Elastic/ "Elastic")[![](https://apps.gnome.org/icons/scalable/com.github.cassidyjames.clairvoyant.svg)](https://apps.gnome.org/app/com.github.cassidyjames.clairvoyant/ "Clairvoyant")

## Hepsi Bu Kadar Da Değil…

Bunların haricinde, GNOME 44ʼte birçok küçük gelişme de bulunmaktadır, bunlar arasında:

- GNOMEʼun düşük pil güç bildirimleri yeni simgeler ve güncellenmiş metinlerle yeniden düzenlendi.
- Kişilerʼde bir kişiyi QR kodu kullanarak paylaşmak artık mümkün.
- Web (Eski adıyla Epiphany), GNOME tarayıcısı, GTK4ʼe dönüştürüldü. Bu, GNOME uygulamalarını en son GTK sürümüne dönüştürme çabalarının bir parçası olup başarım ve kullanıcı deneyimi iyileştirmeleri sağlar.
- Arama sonuçları artık Ayarlarʼdan devre dışı bırakılabilir.
- Web (Eski adıyla Epiphany), parolaları kaydetmek için artık yeni açılır pencereye sahip. Bu, önceden kullanılan bilgi çubuklarının yerini alıyor.
- Haritalarʼda, daha fazla yerin, Wikidata ve Wikipediaʼdan görüntülerin alınması sayesinde, fotoğrafı var. Haritalar, klavye kullanarak arama sonuçlarında gezinme gibi küçük geliştirmeler de içeriyor.
- Uygulama ızgarasındaki sürükle ve bırak işlemi iyileştirildi.
- Konsol uçbirim uygulamasına, açık sekmeleri ızgarada göstermek için sekme genel görünümü eklendi.
- Hava durumu uygulamasının sıcaklık grafiği artık daha yumuşak çizgelere sahip ve başlık çubuğu da yeniden tasarlandı.
- Kişilerʼe eksik olan Ctrl+F, Ctrl+, ve Ctrl+Enter gibi çeşitli klavye kısayolları desteği eklendi. Ayrıca çeşitli hatalar da düzeltildi.
- GNOMEʼun duvar kağıdı derlemesi dört harika yeni arka plan içeriyor.  
    ![](/media/2023/03/wallpapers.png)

## GNOME 44 Sürümünü Nasıl Edinebilirsiniz

GNOME bir [Özgür Yazılımdır](https://gnu.org/philosophy/free-sw.html): tüm [kodlarımız](https://gitlab.gnome.org/GNOME) indirilebilir ve ilgili lisanslara göre özgürce değiştirilebilir ve yeniden dağıtılabilir. Kurulumu için, resmi paketlerinizi beklemenizi ve dağıtımınız tarafından sağlanan paketleri kullanmanızı öneririz. Popüler dağıtımlar çok yakında GNOME 44 sürümünü kullanıma sunacaklar ve bazıları zaten yeni GNOME sürümünü içeren geliştirme sürümleri sunuyorlar. Ayrıca, [GNOME Kutular](https://apps.gnome.org/app/org.gnome.Boxes/) uygulamasını kullanarak sanal makine olarak [GNOME OS görüntüsünü](https://os.gnome.org/) deneyebilirsiniz.

## GNOME Hakkında

GNOME Projesi, kar amacı gütmeyen GNOME Vakfı tarafından desteklenen uluslararası bir topluluktur. Kullanıcı deneyimi mükemmeliyeti ve birinci sınıf uluslararasılaşma ve erişilebilirlik üzerinde odaklanıyoruz. GNOME, özgür ve açık bir projedir: bize katılmak isterseniz, katılabilirsiniz.

- - - - - -

**Not: [GNOME Sürüm duyurusundan](https://release.gnome.org/44/) çevirilmiştir.**

<iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen="" frameborder="0" height="405" loading="lazy" src="https://www.youtube.com/embed/N7SGe1MiqNA?feature=oembed" title="Introducing GNOME 44" width="720"></iframe>