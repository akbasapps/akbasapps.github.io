# akbasapps.github.io

Akbas Apps'in web sitesi. Yayında: <https://akbasapps.github.io>

Sitenin tek işi, Play Store'un zorunlu tuttuğu **gizlilik politikası**
sayfalarını barındırmak ve uygulamaları kısaca tanıtmak. Sunucu tarafı yok,
derleme adımı yok: klasördeki dosyalar olduğu gibi yayınlanıyor.

Bu klasör eskiden `Rutinim` deposunun içinde `site/` olarak duruyordu. İkinci
uygulama (Ayla) çıkınca site iki uygulamaya birden hizmet etmeye başladı ve
Ayla'nın gizlilik politikasının Rutinim deposunda durması kafa karıştırıcı
hale geldi. 28 Eylül 2026'da buraya taşındı.

## Dosyalar

```
index.html                 Ana sayfa: iki uygulama + iletişim
style.css                  Tüm sayfaların ortak stili
icon.png                   Rutinim simgesi
ayla-icon.png              Ayla simgesi
rutinim/gizlilik.html      Rutinim gizlilik politikası (TR)
rutinim/privacy.html       Rutinim gizlilik politikası (EN)
ayla/gizlilik.html         Ayla gizlilik politikası (TR)
ayla/privacy.html          Ayla gizlilik politikası (EN)
google...html              Google Search Console doğrulama dosyası — SİLME
```

Harici yazı tipi ya da betik kullanılmıyor. Bu bilinçli: gizlilik politikasını
okuyan biri, okuma eylemiyle başka bir sunucuya (örneğin Google Fonts'a)
gönderilmemeli.

## Play Console'daki adresler

Bu bağlantılar mağaza girişlerinde kayıtlı; **dosya adlarını değiştirme**.

- Rutinim: <https://akbasapps.github.io/rutinim/privacy.html>
- Ayla: <https://akbasapps.github.io/ayla/gizlilik.html>

## Yayına alma

GitHub'daki `akbasapps.github.io` deposuna dosyalar elle yükleniyor. Değişen
dosyaları web arayüzünden yükledikten bir iki dakika sonra site güncelleniyor.

Tarayıcıda eski hâli görünüyorsa önbellek yüzündendir; sayfayı zorla yenile.

## Politika metinlerini güncellerken

Uygulamanın veri işleme biçimi değişirse (reklam, analitik, çökme raporu,
sunucu, uygulama içi satın alma) politika **aynı sürümde** güncellenmeli.
Her sayfadaki "Son güncelleme" tarihini de değiştirmeyi unutma.

Özellikle: Google Play Billing eklenirse `INTERNET` izni gerekir. O an Ayla'nın
"internet izni bile yok" iddiası geçerliliğini yitirir; hem bu metin hem Play
Console'daki veri güvenliği formu yeniden yazılmalıdır.
