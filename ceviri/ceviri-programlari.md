---
layout: post
title: 'Çeviri Programları'
author: 'Sabri Ünal'
---

Linux’un olabildiğince çok kişiye ulaşması için yerelleştirme önemlidir. Bu yüzden Linux için geliştirilmiş başka platformlarda çalışan ve başka özellikler, değişik kullanım seçenekleri sunan çeviri yazılımları vardır. Bu belgede bu yazılımlardan en gözdeleri anlatılmaktadır.

## GNOME Çeviri Düzenleyici

GNOME Çeviri Düzenleyici, (GTranslator adıyla da bilinmektedir) Fatih Demir ve Ross Golder tarafından geliştirilmesine başlanmış, halen GNOME topluluğunca geliştirilen bir GNU gettext çeviri uygulamasıdır. GNOME çevirilerine yardımcı olmak amacıyla geliştirilmiştir. Po uzantılı dosyaların çevirisinde kullanılmaktadır. Çeviri belleği oluşturma desteği de sunan bu uygulamanın kaynak kodları <https://gitlab.gnome.org/GNOME/gtranslator> adresinde bulunmaktadır.

![](/media/2023/03/gtranslator.png)

###### Kurulumu

GTranslator oldukça yaygındır ve bu yüzden çoğu dağıtım içinde gelmektedir. Dağıtımınızla gelen paket yöneticisinden veya yazılım mağazaları üstünden ‘gtranslator’ uygulamasını kurabilirsiniz. Flatpak sürümü de [Flathub](https://flathub.org/apps/details/org.gnome.Gtranslator) üstünden edinilebilir.

###### Kullanım

GTranslator’ı ilk açtığınızda yalın bir arabirim ile karşılaşırsınız. Üstte başka işlevleri olan düğmeler, altında “Özgün ileti” ve “Çevrilmiş ileti”leri içeren bir dizgeler tablosu ve onun altında da seçili “Özgün Dizge” ve “Çevrilmiş Metin” girdi kutuları bulunur. Sağ panelde üstte çeviri belleğindeki karşılıkları, altında ise notlar ve çevirinin yolu yer alır.

GTranslator ilk açılışında PO başlığı için gerekli bilgileri sizden isteyecektir. Bu bilgileri “Ana Menü &gt; Tercihler &gt; Profiller” yolundan daha sonra da yapılandırabilirsiniz. Profiller sekmesinden yoksa yeni bir profil oluşturabilir, varsa ilgili profili seçip bilgilerinizi düzenleyebilirsiniz. Bu bilgiler düzenlediğiniz PO dosyalarının başlık kısmına imzanız olarak eklenecektir.

Profil iletişim kutusunda **Çevirmen Bilgisi** alanına isterseniz gerçek adınızı ya da takma adınızı ve iletişim için e-posta adresinizi ekleyiniz.

**Takım e-postası** alanına, GNOME çeviri ekibimizce kullanılan **takim@gnome.org.tr** e-posta adresini giriniz.

Dil seçeneklerinde GNOME için dili ‘Turkish’ seçmeniz yeterlidir. Dil ayarlarını, aşağıdaki biçimde kendisi oluşturacaktır:  
– Dil kodu: ‘tr’  
– Karakter kümesi: ‘UTF-8’  
– Kodlama: ‘8bit’  
– Çoğul biçimler: ‘nplurals=1; plural=0’

Bu ayarladan sonra çevirinize başlayabilirsiniz.

Dizgeler arasında dolaşmak için klavye kısayollarını kullanabilirsiniz. Örneğin Alt+Sol/Alt+Sağ tuşlarıyla dizgeler arasında ileri/geri gidebilirsiniz. Diğer kısayollar için Ana Menü altındaki Klavye Kısayolları sayfasına bakabilirsiniz.

- - - - - -

## Poedit

###### Genel bilgiler

Poedit, Vaclav Slavic tarafından geliştirilen çapraz platform bir çeviri aracıdır. Windows, Linux ve diğer platformlarda grafik arabirimi değişmeden kullanılabilmektedir. Bu özellikle Windows üzerinde çeviri yapanlar için büyük kolaylıktır. Web sitesi [poedit.net](https://poedit.net) olup uygulamanın kaynak kodları <https://github.com/vslavik/poedit> adresinde bulunmaktadır. Türlü çeviri servisleriyle tümleşik çalışan [Pro sürümü](https://poedit.net/pro) de bulunmaktadır.

![](/media/2023/04/poedit-gnome.png)

###### Kurulum

Poedit pek çok dağıtımın deposunda bulunmaktadır. Windows ve MacOS sürümleri de [indirme sayfasında](https://poedit.net/download) listelenmiştir. Linux için resmi [snap paketini](https://snapcraft.io/poedit), ya da [Flathub üstünden flatpak paketini](https://flathub.org/apps/details/net.poedit.Poedit) indirip kurabilirsiniz.

###### Kullanım

Poedit, kullanımı kolay çeviri programlarından birisidir. İlk açılışta sizi hoş geldiniz ekranı karşılar. Hoş geldiniz ekranından “Yeni oluştur…” diyerek varsa pot dosyasını kullanarak yeni çeviri başlatabilirsiniz. İkinci yöntem ise “Dosya &gt; Aç…” yoluyla çevirisini yapmak istediğiniz po dosyasını açmaktır. Ayrıca po dosyasının üstüne sağ tıklayıp Birlikte Aç ekranından Poedit ile açmayı da seçebilirsiniz.

Çeviriye başlamadan önce “Düzen &gt; Tercihler &gt; Genel” sekmesi altından Adınızı ve E-posta adresinizi çevirmen bilgisi olarak kayıt etmeniz gerekmektedir. Bu ekranın görünmesi için bir po dosyasının açık olması gerekmektedir. Bu ayarları yaptıktan sonra çeviri yapmaya başlayabilirsiniz.

Poedit arabirimi üç alandan oluşur. Üstte çeviri dosyasının dizini, altta ise çeviri yapacağınız alan bulunmaktadır. Sağdaki açılır/kapanır kenar çubuğunda ise çeviri belleğinden sunulan öneriler görünebilir. Ayrıca “Önceki kaynak metin” ile “Çevirmenler için notlar” da ilgili durumlarda burada görünmektedir. Yaptığınız çevirideki önemli noktalar için, ya da gelecek çevirilerde hatırlamak için “Yorum Ekle” düğmesi yoluyla ilgili çeviri satırına not eklenebilir.

Poedit, GTranslator gibi çeviri kütükleri tutmaktadır. Çeviri belleği denilen bu kütükler başlangıçta boştur ancak siz kendi kullanımınız için “Düzenle &gt; Tercihler &gt; ÇBelleği” sekmesinden Yönet düğmesine basarak yönetebilirsiniz. Gerektiği durumda buradan Çeviri Belleği sıfırlanabilir.

Poedit’te dizgeler arasında Ctrl+Yukarı/Ctrl+Aşağı tuşları ile gezinebilirsiniz. Poedit hatalı, eksik ya da bulanık çevirileri üst bölümde bulunan dizinde başka renklerde gösterir.

Poedit görünüm menüsünde çevirileri “Dosya Düzenine Göre Sırala”, Kaynağa Göre Sırala”, “Çeviriye Göre Sırala” seçenekleri bulunmaktadır. Ayrıca “Bağlama Göre Grupla”, “Hataları Olan Dizgeler En Üstte”, “Çevrilmemiş Dizgeler En Üstte” ve “Uyarıları Göster” seçenekleri bulunmaktadır. Bu seçenekleri harmanlayarak verimli biçimde çalışabilirsiniz.

Örneğin yeni çeviri projesinde “Uyarıları Göster” + “Kaynağa Göre Sırala” + “Bağlama Göre Grupla” seçeneklerini kullanabilirsiniz. Üstünde yeni değişiklikler olan çoğu bitmiş çeviride ise “Uyarıları Göster” + “Kaynağa Göre Sırala” + “Bağlama Göre Grupla” + “Çevrilmemiş Dizgeler En Üstte” seçeneklerini birleştirebilirsiniz.

GNOME projelerinde, gerekmemekle birlikte, Poedit ile kaynak koddan çevrilecek değerler de derlenebilir.