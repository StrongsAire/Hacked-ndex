# Hacked By Strongsaire | Turk Hack Team – Deface Sayfası

Bu proje, **Turk Hack Team** üyesi **Strongsaire** tarafından hazırlanmış, tamamen görsel efektlerle donatılmış bir "deface" simülasyon sayfasıdır.  
Gerçek bir saldırı amacı taşımaz; yalnızca **eğlence**, **farkındalık** ve **yetenek gösterimi** için oluşturulmuştur.

## 🎯 Özellikler

- **🎬 Video arka plan** – `catbox.moe` üzerinden yayınlanan döngülü video
- **🎵 Müzik & efekt sesleri** – İki ayrı ses kanalı (arka plan müziği ve periyodik efekt)
- **💻 Matrix yağmuru** – Kanji ve sayılarla kırmızı tonlu matris efekti
- **🌐 IP yağmuru** – Rastgele IP adreslerinin ekrandan düşüşü
- **🗺️ Dünya haritası ışınları** – İstanbul gibi hedeflere çizilen kırmızı ışınlar
- **✨ Parçacık sistemi** – Müziğe duyarlı hareket eden parçacıklar
- **🖱️ Özel imleç** – Kırmızı artı (+) şeklinde özel cursor
- **🖱️ Tıklama baloncukları** – Tıklanan noktada büyüyüp kaybolan kırmızı artılar
- **🧠 Subliminal mesajlar** – Rastgele beliren korkutucu uyarılar
- **🔔 Bildirim alanı** – Trojan, firewall gibi sahte sistem uyarıları
- **📟 Sürüklenebilir terminal** – Komut satırı simülasyonu (`scan`, `hack`, `ddos`, `whoami`…)
- **💀 Kafatası animasyonu** – Göz kırpan skull
- **🌩️ Ekran çatlaması** – Tıklamada beyaz çatlak efekti
- **📊 DDoS sayacı** – Gerçek zamanlı artan sahte paket sayısı
- **🕐 Görev çubuğu** – Saat ve sistem uyarıları
- **⌨️ Klavye kod yağmuru** – Tuşa basıldığında karakter dökülmesi
- **🔒 Enter kilidi** – Sayfaya girmeden önce "CLICK TO ENTER" perdesi
- **✍️ Typewriter efektleri** – Hem giriş perdesinde hem ana sayfada yazı animasyonu
- **👥 Greetz bölümü** – Teşekkür kartları (scroll ile açığa çıkıyor)

## 🚀 Kurulum & Çalıştırma

Proje tamamen **HTML, CSS ve JavaScript** ile yazılmıştır. Herhangi bir derleme adımına ihtiyaç duymaz.

1. `index.html` dosyasını indirin.
2. Dosyayı herhangi bir tarayıcıda açın (`Chrome`, `Firefox`, `Edge`).
   - **Not:** Video ve ses kaynakları `catbox.moe` üzerinden yüklendiği için **internet bağlantısı** gereklidir.
3. İsteğe bağlı olarak `CONFIG` nesnesini düzenleyerek isim, link, müzik, video ve karşılama listesini özelleştirebilirsiniz.

### ⚙️ Yapılandırma

JavaScript bölümündeki `CONFIG` objesi üzerinden tüm içerik yönetilir:

```js
const CONFIG = {
    hackerName: "Strongsaire",                     // Hacker adı
    hackerProfileUrl: "https://...",               // Profil linki
    bgMusic: "https://.../bg.mp3",                 // Arka plan müziği
    effectMusic: "https://.../effect.mp3",         // Efekt sesi
    video: "https://.../video.mp4",                // Arka plan videosu
    typewriterPhrases: ["...", "..."],             // Dönen yazı metinleri
    greetzList: [{name:"isim1"}, {name:"isim2"}]   // Teşekkür listesi
};
