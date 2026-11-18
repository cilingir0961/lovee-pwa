# LOVEE — demo (PWA)

Bu depo yalnızca LOVEE'nin derlenmiş **tanıtım sürümünü** içerir (kaynak kod değil). Sürüm: **v0.8**
(`0.8.0-f3946cb`, kaynak: `cilingir0961/lovee` @ `f3946cb`).

- Profiller **örnektir**, gerçek kişi değildir. Bazı örnek profilleri beğenince otomatik **demo eşleşmesi** olur;
  bu eşleşmeler gerçek değildir.
- Örnek profiller **cevap vermez** (bot yok): mesaj, davet, Bu mu şu mu ve Üç Soru yanıtsız kalır. Açılış anını
  görmek için kartta **"Örnek · gerçek yanıt değil"** etiketli önizleme vardır; bu, karşı tarafın gerçek cevabı değildir.
- Veriler yalnızca açan kişinin tarayıcısında kalır, hiçbir sunucuya gönderilmez; sayfa yenilenince sıfırlanır.
- Gerçek ödeme yok; krediler yalnızca demo içindir.

Adres: https://cilingir0961.github.io/lovee-pwa/

## v0.8'de yeni: Tanışalım
- **Bu mu, şu mu?** — beş ikili seçim; seçimler iki taraf da seçene kadar gizli kalır. Başlatmak 1 kredi.
- **Üç Soru** — sırayla açılan üç soru; kimse cevap vermeden diğerininkini göremez. Başlatmak 1 kredi.
- **İkimizin Listesi** — birlikte yapmak istedikleriniz (plan listesi; rezervasyon değil). Ücretsiz.
- Cevap vermek, sonuçları görmek ve liste ücretsizdir. Mesaj, davet, sesli mesaj ve damga: 1 kredi.

## Kurulum (PWA)
- iPhone: Safari'de aç → Paylaş → **Ana Ekrana Ekle**.
- Android: Chrome'da aç → menü → **Ana ekrana ekle / Uygulamayı yükle**.

Eski arayüz görünürse: sayfayı yenile (GitHub Pages önbelleği ~10 dk). Ana ekrana eklenmiş eski sürüm varsa
silip yeniden ekle. Sürüm, sayfa kaynağında `<meta name="lovee-version">` olarak yazar.

## Geri dönüş
Önceki demolar aynen dallarda durur: `v0.7.0`, `v0.6.1`, `v0.6.0`, `v0.5`. Geri almak için `main`'e ilgili dalın
içeriği yeni bir commit olarak alınır (geçmiş silinmez, force-push gerekmez).
