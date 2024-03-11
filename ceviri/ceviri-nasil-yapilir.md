---
layout: post
title: 'Çeviri Nasıl Yapılır?'
author: 'Barış Çiçek, Sabri Ünal'
permalink: /ceviri/ceviri-nasil-yapilir/
---

## Giriş

Bu belge GNOME Projesi yerelleştirme çalışmalarına katılabilmeniz için yardımcı bilgileri içerir. Bu belgeyle birlikte yerelleştirme çalışmaları için temel bilgileri öğrenebilir ve hatasız çeviriler yapabilmek için gerekli koşulları topluca bulabilirsiniz.

## PO dosyası nedir?

GNOME Projesi içerisindeki uygulamalar kaynak kodunda değişiklik yapmadan ve kolay biçimde çevirilebilmek için GNU kütüphanelerinden **gettext** kütüphanesini kullanır. Gettext kütüphanesi programcıların kod içerisinde çevirisi yapılması gereken metinleri imleyebilmelerini ve bu imlenen metinlerin ayrı bir dosya içerisinde saklanabilmelerini sağlar. Bu kolaylık, İngilizce ya da başka dillerde yazılmış programların diğer dillere yalnızca bir dosyayı düzenleyerek çevirilebilmesini sağlar.

Gettext kullanan bir uygulama kaynak kodu içinde imlenen metinleri MO (makine nesnesi) dosyasından alır. MO dosyaları PO (uyarlanabilen nesne) dosyalarından derlenmiş ikili (binary) dosyalardır.

Düz metin biçimindeki PO dosyaları çeviricilerin herhangi bir metin düzenleyicisi ile daha sonra MO dosyasına derlenmek üzere oluşturabilecekleri dosyalardır.

## Po dosyasının yapısı nasıldır?

PO dosyaları imlenmiş metinlerin **xgettext** aracı ile ayıklanması yolu ile oluşturulabilen düz metin dosyalarıdır.

Bir po dosyası içindeki girdinin (imlenmiş metnin) yapısı aşağıdaki gibidir:

```
boş satır
# çevirici için açıklamalar
#. kendiliğinden oluşturulan açıklamalar
#: çevirinin kod içinde bulunduğu yerler…
#, imler…
msgid çevirilmemiş dizge
msgstr çevirilmiş dizge
```

Örnek:

```
#: lib/error.c:116
msgid “Unknown system error”
msgstr “Bilinmeyen sistem hatası”
```

## PO dosya imleri nelerdir?

PO dosyaları her girdi sonrası girdi ile ilgili olarak imler içerir. Bu imler çevirinin işlenmesi ile ilgili önemli bilgiler içerir. Gettext kütüphanesindeki belli başlı iki im ve açıklamaları şöyledir:

### fuzzy (bulanık imi)

Bulanık imi çevirinin, çevirmence tam olarak kestirilememesi, ikilemde kalınması durumunda kullanılması gereken ya da uygulamanın içindeki metinlerin değişmesi sonucu araçlarca kendiliğinden atan imdir. Bulanık imleri bulunan girdiler çeviri olarak gösterilmezler ve çeviri istatistiklerinde bulanık olarak belirtilirler.

### c-format ve no-c-format

Bu im genelde az rastlanılan ancak çeviri açısından önemli bir imdir.

*c-format*, öntanımlı olarak tüm girdiler için geçerlidir. Metnin C dizge biçiminde olduğu anlamına gelir. C dizge biçimi içerisinde dizge için %s, tam sayı için %d, reel sayı için %f gibi kodlar bulunduran bir yapıdır.

*no-c-format* içeren bir girdi bu kodların işleme koyulmayacağını yani %s kodunun % ve s karakterlerini belirttiğini anlatır. Genel olarak programlama\_dili-format biçimindedir.

İmlerle ilgili daha geniş bilgileri gettext belgelerinden edinebilirsiniz.

## Çoğul biçimlerini tanıyalım

Gettext 0.10.36 sürümüyle birlikte, birden çok çoğul durum içeren diller için “plural forms” eklenmiştir.

Türkçede yalnızca bir adet çoğul durum olması, birden çok çoğul durum çevirisi yapmayı gerektirmez, ancak biçim tümlüğü için diğer çoğul durumlarında birinci ile aynı olması gerekir. Ancak bazen tekil durumda kod içerilmez. Bu durumda ayrı ayrı çeviriler belirtilmelidir. Benzer bir durum Türkçe için örnekteki gibidir.

Çoğul biçim içeren PO girdisi aşağıdaki gibidir:

```
boş satır
# çevirici için açıklamalar
#. kendiliğinden oluşturulan açıklamalar
#: çevirinin kod içinde bulunduğu yerler…
#, imler…
msgid “çevirilmemiş tekil durum içeren dizge”
msgid_plural “çevirilmemiş çoğul durum içeren dizge”
msgstr[0] “ilk durum için çeviri”
…
msgstr[N] “n’nci durum için çeviri”
```

Türkçe için örnek:

```
#: src/msgcmp.c:338 src/po-lex.c:699
#, c-format
msgid “found one fatal error”
msgid_plural “%d fatal errors”
msgstr[0] “Bir önemli hata bulundu”
msgstr[1] “%d önemli hata bulundu”
```

PO dosyasının yapısını bilmek çeviri için güzel bir arka plan bilgisi oluşturur. Her ne kadar çeviri programları çeviriciler için yalnızca çeviriyi yazmaya dek işi kolaylaştırsalar da bazen çeviri programını kullanmadan bir metin düzenleyici ile PO dosyasında değişiklik yapmak gerekebilir. Bunu doğru ve eksiksiz yapabilmek için yukarıda anlatılan bilgiler çoğu zaman yararlı olacaktır.

## POT dosyalarını tanıyalım

Her uygulama için PO dosyalarının çevrilmek için hazırlanmış POT (PO şablonu) dosyası vardır. POT dosyası yeni metinler için msgtr bölümü boş olan bir PO dosyasıdır.

Türkçedeki çoğul biçim PO dosya başlığı “**Plural-Forms: nplurals=1; plural=0;\\n**” biçimdedir ve çoğul biçim bulunan PO dosyaları için PO başlığına eklenmesi gerekir. Bunu çeviri programınıza eklemek kolaylık getirecek, unutmanızı engelleyecektir. Çeviri proramlarında nasıl yapabileceğinizi öğrenmek için çeviri programları belgesini okuyabilirsiniz.

## Çeviri için POT ya da PO dosyası edinmek

Çeviri yapabilmek için öncelikle çevirilecek uygulamanın POT ya da PO dosyası elde edilmelidir. POT dosyası birçok yardımcı uygulama ile uygulamanın kaynak kodlarından edinilebinir. Ancak GNOME için önerilen yol [10n.gnome.org](https://l10n.gnome.org) adresinde yayın yapan GNOME Çeviri Platformu tarafından sağlanan POT ya da PO dosyalarını kullanmaktır.

### Uygulama kaynak kodlarından POT dosyası oluşturmak 

Kaynak kodlarını edindikten sonra **paket\_adi/po** dizinine girmeli, sonrasında aşağıdaki komuta benzer biçimde, POTFILES dosyasının adına ve uzantısına uygun biçimde xgettext komutunu çalıştırmalısınız.

```
xgettext -f POTFILES.in -o main.pot
```

Eğer daha önceden bir çeviri varsa, var olan çeviriyi en son POT dosyası ile birleştirmek, dolayısıyla yalnızca yeni dizgeleri eklemek için PO dosyasını açtıktan sonra POT dosyasından güncelleyebilirsiniz.

### GNOME Çeviri Platformu’nu kullanmak

GNOME Çeviri Takımı, çeviri işlemlerini kolaylaştırmak için GNOME Çeviri Platformu üzerinde günlük olarak POT dosyalarını oluşturmakta ve çeviri dosyalarını güncel POT dosyasına göre güncellemektedir. Böylece kaynak kodlarını indirmeden yalnızca ilgili PO dosyasını GNOME Çeviri Platformundan indirebilirsiniz. GNOME Çeviri Platformuna <https://l10n.gnome.org/languages/tr/> adresinden ulaşabilirsiniz.

Buradan yayınlanmış GNOME sürümlerine ait çevirilere ulaşabileceğiniz gibi güncel çevirileri de bulabilirsiniz. GNOME masaüstü ortamının son sürümü için çeviri yapmaya başlamadan önce almak istediğiniz paket ile ilgili isteğinizi ve ilk kez GNOME çevirisi yapıyorsanız bunu da belirterek anlık iletişim kanallarımıza yazmanız hem sizi tanımamız hem de çevirilerin daha düzenli ilerlemesi için oldukça önemlidir.

## Çeviri için hangi programı kullanmalıyım?

PO dosyalarını düzenlemek için birçok program yazılmıştır. Bunlar arasından GNOME için Gtranslator ile Windows ve macOS işletim sistemlerinde de çalışan Poedit en çok bilinenleridir. Bu programlarla ilgili ayrıntılı bilgiyi [Çeviri Programları](/ceviri/ceviri-programlari) belgesinde bulabilirsiniz.

## Çeviri yaparken önemsenecekler

### Anımsatıcı imi (mnemonic)

Anımsatıcı Tuş uygulama arabirimlerinde gördüğünüz, altı çizgili harf ile belirtilen ve **Alt** tuşu ile kullanılan tuştur. Bu tuş belirtilirken GTK kütüphanesi karekterin önüne alt çizgi (“\_”) kullanımını gerektirir. Çeviri yaparken alt çizgi çeviride de belirtilmelidir.

Çeviri yaparken genellikle aynı karakteri kullanmak, eğer o karakterden çeviride bulunmuyorsa ilk harfin başına alt çizgi eklemek en doğrusudur. Bir dizge içinde birden çok alt çizgi bulunamaz. Elden geldiğince Türkçeye özgü karakterlere (Ç, Ğ, I, L, Ö, Ş, Ü) anımsatıcı atanmamalıdır.

Örnek:

```
#: src/main.c:284
msgid “_About”
msgstr “_Hakkında”
```

### Şema dosyası metinlerinin çevirisi

GNOME uygulamaların yapılandırmalarını düzenlemek için Windows’taki Registry benzeri bir yapı kullanmaktadır. Bu yapıyı kullanabilmek için uygulamalar **.schemas** uzantılı ve yapılandırma ile ilgili bilgileri içeren bir XML dosyasını sisteme yüklerler. Bu dosyalar yapılandırma ile ilgili açıklamaları içerir. Bu dosyaların çevirilmesi konusunda dikkat etmek gereken en önemli konu, açıklamalarda anahtar değerlerini çevirmeden bırakmaktır.

Çünkü bu değerler dilden dile değişmez, ve özgünü dışında kullanıldığında çalışmazlar. PO dosyasında bir girdinin şema dosyası olup olmadığını, metnin bulunduğu dosyanın adına bakarak anlayabilirsiniz. Eğer dosya **.schemas** dosyası ise burada genellikle tırnak içinde bulunan sözcükleri çevirmeden bırakmak gerekir.

Örnek:

```
#: applets/clock/clock.schemas.in.h:15
msgid “”
“This key specifies the format used by the clock applet when the format key “
“is set to \”custom\”. You can use conversion specifiers understood by “
“strftime() to obtain a specific format.”
msgstr “”
“Bu anahtar, format anahtarı \”custom\”a ayarlı olduğunda saat uygulamacığında “
“kullanılacak olan biçimi belirtir. strftime() tarafından algılanabilen “
“biçim belirteçlerini bir biçim belirtmek için kullanabilirsiniz.”
```

### C-format biçimi

Gettext kütüphanesi düz metinlerin çevirisine izin verdiği gibi **c-format** biçimindeki metinlerin de çevirilmesini sağlamıştır. **c-format** biçimi değişkenler içeren metin şablonlarıdır ve sıradan metinlerden başka olarak yalnızca **%** ile başlayan kodlar içerirler. **%** ile başlayan kodların çeviri içinde de aynen bulunması zorunludur.

Aşağıdaki birkaç örnek, kodun kullanımı ve yerlerini çeviri içinde düzenlemeyi göstermektedir:

```
msgid “%d folder and %d file have been deleted. (%s)”
msgstr “%d klasör ve %d dosya silindi. (%s)”
```

Bu örnekte **%d** ve **%s** kodları özgün metinde kullanıldığı sırada kullanılmıştır.

---

Bir başka örnek verelim:

```
mstid “%d folder and %d file have been deleted from folder %s”
mstid “%3$s klasöründen %2$d dosya ve %1$d klasör silindi”
```

Bu örnekte kodların sıraları değiştirilmiştir. Sıra değiştirilirken önce **%** karakteri sonra kullanılacak kodun metin içindeki sırası daha sonra **$** imi ve kodun türü yazılır. **%3$s** kodu, özgün metinde 3. sıradaki kod olan %s’yi belirtir.

---

Tarih ile ilgili bir örnek verelim:

```
msgid “Completed on %B %d, %Y, %l:%M %p”
msgstr “%d %b %l:%M %p tarihinde tamamlandı”
```

Buradaki örnek **c-format** biçiminde tarih ve zaman belirtmektedir. Burada Türkçedeki tarih ve zaman yazımına dikkat edilerek çeviri yapılmalıdır.

---

**no-c-format** imi bulunan PO dosyası girdileri kodları derlemez o yüzden **%** karakterleri metnin bir parçası olarak görülmelidir. Eğer **no-c-format** imi bulunmuyorsa yüzde imini belirtmek için iki kez yazmak gerekir.

Örnek:

```
#, c-format
msgid “%d% completed”
msgstr “%%%d tamamlandı”
```

### Python-format biçimi

Bu biçim **c-format** biçimi için geçerli olan kuralları korur ancak Python ve C programlama dillerini yapılarındaki değişiklikler nedeniyle **python-format** biçiminde olan çevirilerde kullanılan kodlar başkadır. **python-format** biçiminde ‘$’ işareti kodlamalarda kullanılmaz, onun dışında kullanım aynıdır.

Örnek:

```
#, python-format
mstid “%d folder and %d file have been deleted from folder %s”
mstid “%3s klasöründen %2d dosya ve %1d klasör silindi”

#, python-format
msgid “Completed on %B %d, %Y, %l:%M %p”
msgstr “%d %b %l:%M %p tarihinde tamamlandı”
```

### Yeni satır karakteri

Çeviriler içinde, özellikle konsola yazılacak olan metinler için satır sonlarında yeni satır karakteri (\\n) bulunur. Bu karakterler çeviride de aynı oranda bulunmalıdır. Özgün metnin çevirisi daha kısa olsa bile boş satırlara **\\n** eklenerek sayı tamamlanmalıdır. Ayrıca çevirdiğiniz metnin içinde görüneceği pencerenin boyutlarına uygun olması, metnin daha düzgün görüntülenmesini sağlayacağı için satır sonu karakteri ve çevirinin özgün metin ile satır sonu olarak benzer olmasına dikkat etmeniz önerilmektedir.

### UTF-8 kodlaması

GNOME çevirilerinde kullanılan PO dosyaları UTF-8 ile kodlanmalıdır. Günümüzde Linux işletim sistemindeki dosyalar için bu biçim standart durumuna gelmiştir.

### Son denetim

Çeviri bitip GNOME çeviri platformuna göndermeden önce dosya üzerinde son denetimleri yapmalısınız. Bu denetimleri **msgfmt** adlı araç ile yapabilirsiniz. Dosyayı göndermeden önce aşağıdaki komutun hata belirtmediğinden emin olmak isteyebilirsiniz:

```
msgfmt -c -v –check-accelerators=_
```

Bu komut aynı zamanda GNOME Çeviri Platformuna da gömülmüştür.

## GNOME Türkiye Telegram Grubu

Çeviri yapmak GNOME ile ilgili birçok şeyi öğrenmenizi sağlayacak ve Özgür Yazılım için katkıda bulunmanızı sağlayacaktır. Çeviri yaparken burada yazanların dışında yardıma gereksinebilirsiniz. Bu yüzden çeviri yapmadan önce anlık iletişim kanallarını kullanmanız işinizi kolaylaştıracaktır. Böylece diğer çevirmenlerden yardım alabilir, etkinlikleri daha kolay izleyebilirsiniz.

## GNOME-Türk E-posta Grubu’na ne oldu?

Uzun yıllar kullanılan GNOME Türk e-posta grubu, GNOME tarafından, tüm e-posta gruplarıyla birlikte, 2023 yılıyla birlikte emekli edilmiştir ve yalnızca arşiv olarak tutulmaktadır. Arşivlenmiş iletilere <https://mail.gnome.org/archives/gnome-turk/> adresinden erişebilirsiniz.

---

*Yazar:* Barış Çiçek

*Güncelleyenler:* Sabri Ünal, Emin Tufan Çetin
