# WebPDF Studio PRO — Official Downloads

**Zero-upload, client-side PDF & Office suite for Windows.**
Hiçbir PDF/Office dosyanız bilgisayarınızdan çıkmaz.

👉 **Kurulum dosyaları için sağ taraftaki [Releases](../../releases/latest) bölümüne gidin.**

---

## ⬇️ İndirme

| Dosya | Ne zaman kullanılır |
|---|---|
| **WebPDF-Studio-Pro-Setup-x.y.z.exe** | Normal kurulum. Başlat menüsü + masaüstü kısayolu oluşturur, kaldırma desteği vardır. |
| **WebPDF-Studio-Pro-Portable-x.y.z.exe** | Kurulum istemeyenler için tek dosya. USB bellekten bile çalışır. |

### Windows SmartScreen uyarısı — normaldir

Uygulama ticari kod imzalama sertifikası (EV code signing) ile imzalanmadığı için
Windows ilk çalıştırmada şu uyarıyı gösterebilir:

> *"Windows, bilgisayarınızı korudu — Windows Defender SmartScreen tanınmayan bir uygulamayı engelledi."*

Devam etmek için: **Ek bilgi → Yine de çalıştır**.
Bu uyarı, dosyanın zararlı olduğu anlamına gelmez; yalnızca yayıncının Microsoft
tarafından henüz "tanınmadığı" anlamına gelir. İmzalı bir sürüm ileride eklenecektir.

### Dosyanın bozulmadığını doğrulama

Kurulum sayfasında yayınlanan `SHA-256` değeri ile karşılaştırabilirsiniz:

```powershell
Get-FileHash .\WebPDF-Studio-Pro-Setup-2.4.0.exe -Algorithm SHA256
```

---

## 🔒 Neden bu depoda kaynak kod yok?

- Bu depo **yalnızca derlenmiş kurulum dosyalarını** barındırır.
- Kaynak kodu **private** bir depoda tutulur; kopyalanması ve yeniden dağıtılması
  lisans gereği yasaktır.
- Uygulama tamamen **çevrimdışı** çalışır: harici AI/LLM servisi, OCR bulutu veya
  dosya yükleme uç noktası içermez.

## 💳 Lisans

Commercial Lifetime — **€29** · [mavvi.online](https://mavvi.online)

Satın alma sonrası lisans anahtarı uygulama içindeki **License** ekranından
girilir; doğrulama bir kez yapılıp cihazda imzalı olarak önbelleğe alınır.

## 🐞 Sorun bildirimi

Kurulum/çalıştırma sorunları için bu depoda **Issues** açabilirsiniz.
Lütfen sürüm numarasını, Windows sürümünü ve ekran görüntüsünü ekleyin.

---

*Copyright © 2026 mavvi.online / smnlcm — All rights reserved.*
*Kaynak kod yayınlanmaz. Yeniden dağıtım yasaktır.*
