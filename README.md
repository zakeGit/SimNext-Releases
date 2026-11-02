# SimNext Windows dağıtımları

Bu depo yalnız Windows kurulum paketleri, imzalı güncelleme bildirimi ve kullanıcı notları içerir. Uygulamanın kaynak kodu burada yayınlanmaz.

İlk yayın deneme adayıdır. Yerel testler, temiz Windows kurulumu ve gerçek tesis kabulü ayrı doğrulanır. Kurulum paketinde kalibrasyon vana kontrolü bulunmaz.

Yeni kurulumda tüm cihazlar, sunucu ve Bakanlık gönderimi kapalıdır. Önce tesise ait bağlantı ve istasyon/kanal ayarları yapılır.

Güncelleme kaynağı: `https://raw.githubusercontent.com/zakeGit/SimNext-Releases/main/stable.manifest.json`

Bu imzalı bildirim adresidir; EXE bağlantısı değildir. Tesislerde GitHub hesabı veya erişim anahtarı gerekmez. İndirme ölçüm toplamayı durdurmaz; kurulum operatörün kontrollü çıkışı ve Windows yönetici onayıyla uygulanır.

Windows kod sertifikası bulunmayan ilk adayın dosya adında DRAFT vardır. Manifest imzası ile Windows yayıncı imzası farklı kontrollerdir.

Güncel kurucu: [SimNext 0.14.0 revizyon 4](https://github.com/zakeGit/SimNext-Releases/releases/download/v0.14.0-pilot.4/SimNext-Setup-0.14.0-r4-DRAFT.exe). Windows PowerShell 5.1 masaüstü başlatıcısındaki açılış hatası düzeltildi; kullanıcı hesabının otomatik doldurulması ve önceki ön koşul düzeltmeleri dahildir.
