<div align="center">

<img src="banner.svg" alt="cohard32" width="100%">

<br>

![Flutter](https://img.shields.io/badge/Flutter-071A10?style=for-the-badge&logo=flutter&logoColor=B4FF3C&labelColor=0D2818)
![Dart](https://img.shields.io/badge/Dart-071A10?style=for-the-badge&logo=dart&logoColor=B4FF3C&labelColor=0D2818)
![Python](https://img.shields.io/badge/Python-071A10?style=for-the-badge&logo=python&logoColor=B4FF3C&labelColor=0D2818)
![Firebase](https://img.shields.io/badge/Firebase-071A10?style=for-the-badge&logo=firebase&logoColor=B4FF3C&labelColor=0D2818)
![Android](https://img.shields.io/badge/Android-071A10?style=for-the-badge&logo=android&logoColor=B4FF3C&labelColor=0D2818)
![Windows](https://img.shields.io/badge/Windows-071A10?style=for-the-badge&logo=windows&logoColor=B4FF3C&labelColor=0D2818)

</div>

---

Gerçekten kullanılan uygulamalar yazıyorum — demo değil, her gün açılan şeyler.
İki alanda çalışıyorum: **Flutter ile Android** ve **Python ile Windows masaüstü**.

---

## Projeler

<table>
<tr>
<td width="50%" valign="top">

### 📱 ROY MESSANGER

[![sürüm](https://img.shields.io/github/v/release/cohard32/kardes_mesaj?style=flat-square&color=B4FF3C&labelColor=0D2818&label=s%C3%BCr%C3%BCm)](https://github.com/cohard32/kardes_mesaj/releases/latest)

Reklamsız, takipsiz, aile içi kullanım için yazılmış bir Android mesajlaşma uygulaması.

Sesli/görüntülü arama · kilit ekranında gelen arama · orijinal kalitede medya · sesli mesaj · QR ile arkadaş ekleme · engelleme · uygulama içi otomatik güncelleme

`Flutter` `Firebase` `Agora RTC`

[**Depo**](https://github.com/cohard32/kardes_mesaj) · [**APK indir**](https://github.com/cohard32/kardes_mesaj/releases/latest)

</td>
<td width="50%" valign="top">

### 🖥️ Welat Net Tools

[![sürüm](https://img.shields.io/github/v/release/cohard32/welat-net-tools-releases?style=flat-square&color=B4FF3C&labelColor=0D2818&label=s%C3%BCr%C3%BCm)](https://github.com/cohard32/welat-net-tools-releases/releases/latest)

YouTube, TikTok, Instagram ve X gibi platformlardan video/ses indirme, dönüştürme ve kırpma yapan Windows masaüstü uygulaması.

Word için AI destekli belge araçları · AI arka plan kaldırma · otomatik hata raporlama · sürüm güncelleme altyapısı

`Python` `Windows`

[**Sürümler**](https://github.com/cohard32/welat-net-tools-releases) · [**İndir**](https://github.com/cohard32/welat-net-tools-releases/releases/latest)

</td>
</tr>
</table>

---

## Uğraştığım problemler

Küçük projeler bile ilginç kısıtlar getiriyor. ROY MESSANGER'da çözmem gerekenlerden birkaçı:

<table>
<tr><td width="50%" valign="top">

**Sunucusuz bildirim**

Cloud Functions kullanmadan, yani kredi kartı gerektirmeden, uygulama kapalıyken bile anlık bildirim ve gelen arama. FCM HTTP v1 çağrıları doğrudan istemciden yapılıyor.

</td><td width="50%" valign="top">

**Kilit ekranında arama**

Telefon kilitliyken çalan, tam ekran açılan gelen arama ekranı. Android'in arka plan kısıtlarıyla kamera/mikrofon izinlerinin kesiştiği yer, tahmin ettiğimden çok daha derin bir kuyu.

</td></tr>
<tr><td valign="top">

**Kuralların kendisi test edilir**

Veri güvenliği tamamen Firestore kurallarında. Emülatör üzerinde **51 senaryoluk** bir test paketi hem yetkisiz erişimin reddedildiğini hem de meşru kullanımın çalıştığını doğruluyor.

</td><td valign="top">

**Native çökmeleri görmek**

Dart'ın yakalayamadığı native çökmeler için sunucu tarafına "son adım" işaretleri yazan bir teşhis sistemi. Süreç ölse bile kayıt kalıyor, hata nerede olduğunu söylüyor.

</td></tr>
</table>

---

## Nasıl çalışırım

<table>
<tr><td width="34%" valign="top">

**Kök nedeni bulurum**

Belirtiyi bastırmak yerine sebebi ararım. Bir hata düzeldiyse *neden* düzeldiğini de bilirim.

</td><td width="33%" valign="top">

**Kanıtla ilerlerim**

"Çalışıyor" demek yetmez. Test, ölçüm ya da gerçek cihaz kaydı olmadan bitti saymam.

</td><td width="33%" valign="top">

**Kararı koda yazarım**

Zor kazanılmış bilgi yorumda kalır — böylece aynı hata altı ay sonra tekrar yapılmaz.

</td></tr>
</table>

---

<div align="center">
<sub>Kod yazmayı seviyorum, kullanılmayan kodu değil.</sub>
</div>
