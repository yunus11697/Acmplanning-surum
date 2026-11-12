<div align="center">

# 🧩 ACM Planning

**CorelDRAW için ACM kompozit panel eklentisi**

Açılım · Kesim · Yerleşim · 3B · Render · Desen · Kâğıttan oku · Metraj ve teklif

![Sürüm](https://img.shields.io/badge/s%C3%BCr%C3%BCm-3.10.8-1f6feb)
![CorelDRAW](https://img.shields.io/badge/CorelDRAW-2020%20ve%20sonras%C4%B1-2ea043)
![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078d4)
![Dil](https://img.shields.io/badge/dil-T%C3%BCrk%C3%A7e%20%7C%20English-8250df)

**[⬇️ Son sürümü indir: AcmPlanning_Setup_3.10.8.exe](https://raw.githubusercontent.com/yunus11697/acmplanning-surum/main/kurulum/AcmPlanning_Setup_3.10.8.exe)** <!-- son-kurulum -->

</div>

> [!CAUTION]
> **Sorumluluk reddi.** ACM Planning hesap ve çizimde yardımcı bir araçtır. Programın ürettiği açılım, ölçü, kesim planı, yerleşim, metraj ve teklifleri **imalata ya da müşteriye vermeden önce kendiniz kontrol edin.** Hatalı ölçü, kesim, malzeme ya da iş kaybı ve bunlardan doğan dolaylı zararlardan **sorumluluk kabul edilmez.** Ayrıntı kurulumdaki lisans sözleşmesinin 6. maddesindedir.

---

## ✨ Ne işe yarar?

Tabela ve cephe kaplamasında kullanılan ACM (alüminyum kompozit) levhaların açılımını, kesimini ve maliyetini CorelDRAW'un içinden, birkaç tıklamayla çıkarır.

| | Bölüm | Ne yapar |
|---|---|---|
| 📐 | **Açılım** | Tek levha, ara bükümlü, Single, Border, Edge, trapez ve çizilen şekil açılımları; V-kanal ve ters büküm çizgileri, köşe kesimleri, derz ve pas. Ölçü net, dış ya da **iç (kolon/kasa)** olarak yazılır. |
| 🧱 | **Kompozit Profil** | Plan ve kesitten çok parçalı profil açılımı; köşede bölünen parçalar, kulaklar. |
| 🔩 | **Perçin** | Açılıma perçin delikleri; kaset köşesinde **Köşe L parçası**, delikler birebir çakışır. |
| 🌀 | **Kıvrım** | Kavisli yüz ve yuvarlak köşe için V kanal sayısı, aralığı ve açılımı. |
| 🪧 | **Birleşik tabela** | Uzun tabelayı yan yana birleşen parçalara böler (dış derz ve birleşim derzi). |
| 🧩 | **Yerleşim** | Açılımları standart levhalara dizer (nesting); gerçek şekil, renge göre ayrım, **fire deposu** (F001, F002 …). |
| 🪚 | **Kesim** | Parça listesini stok levhalara panel testeresiyle (giyotin) yerleştirir: kesim sırası, sığmayanlar, fire, PDF rapor, proje kaydı, renk ayrımı, atık deposu. |
| 📷 | **Kâğıttan oku** | Ölçü kâğıdının fotoğrafından parça listesi: Windows yazı tanıma (internetsiz) ya da seçtiğiniz yapay zekâ ile **Güçlü oku**. Yan ve üst/alt derz ayrı. |
| 🧊 | **3B** | Açılımın katlanmış hâli: canlı katlama (0°–90°), 4 mm kalınlık, çarpışma ve kapanmayan köşe uyarısı, büküm yönü değiştirme, resim olarak kopyalama. |
| 🎨 | **Render** | Gerçekçi ışık, gölge ve yansıma; RAL renk, ahşap/mermer yüzey, LED ve spot, cadde ortamında dükkân cephesi, kabartma kutu harf, kendi fotoğrafınıza oturtma; PNG, video, tek sayfa sunum PDF. |
| 🕳️ | **Desen** | Levhanın ya da açılımın içini delik desenleriyle doldurur: 46 hazır desen, 17 dizilim, fade (geçiş), resimden yarım ton, 🎲 Zar at; delik sayısı, açık alan, kesim boyu ve CNC süresi. |
| 🏷️ | **Pozla ve İmalat** | Cephe pozlama, toplu imalat çizimi, parça ve fire etiketleri. |
| 📊 | **Metraj ve teklif** | Excel metraj, isteğe bağlı **TEKLİF** sayfası (alan × m² fiyatı, KDV, toplam), para birimi seçimi, kesim föyü, iş kaydı, WhatsApp özeti, DXF. |
| 🌐 | **Dil** | Türkçe ve English: panel, mesajlar ve bütün çıktılar. |

> 🔜 **Yakında:** Kutu harf (kompozit yanak açılımı). Denemede; atölye denemesi bitince kararlı sürümde açılacak.

---

## 💾 Kurulum

1. Yukarıdaki **Son sürümü indir** bağlantısından ya da [`kurulum`](kurulum) klasöründen `AcmPlanning_Setup_X.Y.Z.exe` dosyasını indirin.
2. Tarayıcı "yaygın olarak indirilen bir dosya değil" derse dosyanın yanındaki **⋯ → Sakla → Daha fazla göster → Yine de sakla** deyin. Yeni sürümler az indirildiği için Edge ve Chrome bu uyarıyı verir; dosyanın özeti (SHA-256) [`surum.txt`](surum.txt)'de yazılıdır.
3. Dosyayı çalıştırın. Windows "bilgisayarınızı korudu" ya da "bilinmeyen yayımcı" derse **Ek bilgi → Yine de çalıştır** deyin.
4. Lisans sözleşmesini okuyup kabul edin; yönetici izni istenir.
5. CorelDRAW'u açın, ACM Planning paneli gelir.

> [!TIP]
> Panel bazı bilgisayarlarda menüde çıkmaz ya da her açılışta kaybolursa [`kurulum/acilista_ac.txt`](kurulum/acilista_ac.txt) içindeki **tek seferlik** adımı uygulayın. Kurulum programındaki **Tanı raporu** sorunun yerini gösterir.

**Gereken:** Windows 10 ya da 11, CorelDRAW 2020 ve sonrası (2024, 2025 ve 2026'da denendi). CorelDRAW 2020 ve öncesinde DXF'i Corel'in dışa aktarımıyla değil, panelin **DXF KAYDET** düğmesiyle alın.

---

## 🔄 Güncelleme

Program yeni sürümü kendisi bulur. Panel günde bir kez yalnız bu depodaki [`surum.txt`](surum.txt) dosyasını okur; yeni sürüm varsa panelin üstünde **İndir** şeridi çıkar ve bu sayfayı açar.

> [!WARNING]
> **Güncellemeye başlamadan önce CorelDRAW'daki açık dosyalarınızı kaydedin ve CorelDRAW'u kapatın.** Kurulum CorelDRAW açıkken yapılamaz; kaydedilmemiş çalışma kaybolabilir.

1. Açık dosyalarınızı kaydedip CorelDRAW'u kapatın.
2. Yukarıdaki **Son sürümü indir** bağlantısından yeni kurulumu indirin. Tarayıcı uyarısı çıkarsa [Kurulum](#-kurulum) bölümündeki 2. adıma bakın.
3. Kurulumu çalıştırın. Lisansınız ve ayarlarınız silinmez.
4. CorelDRAW'u açın; yeni sürümün yenilikleri panelin üstünde bir kez gösterilir.

- Kurulum dosyası dijital imzalı olunca panel güncellemeyi kendisi indirip kuracak (**Güncelle** düğmesi). O zamana kadar indirme bu sayfadan yapılır.
- Denetim Ayarlar'dan kapatılabilir; **Şimdi denetle** düğmesiyle elle de bakılır.
- Güncelleme hakkınızın süresi bittiyse panel, yeni sürümün anahtarınızla açılmayacağını söyler.
- Yeni sürümde de çizim, ölçü, kesim ve teklifleri kullanmadan önce kendiniz kontrol edin.

---

## 🔑 Lisans

- Kurulumdan sonra **7 gün deneme** süresi başlar. Sonra çalışmak için lisans anahtarı gerekir.
- **Ayarlar** sayfasındaki **makine kodunu** satıcınıza gönderin; size o bilgisayara özel anahtar verilir. Her anahtar **tek bir bilgisayar** içindir.
- Lisans **süreli** ya da **süresiz** olabilir. Süreli lisansın bitmesine 5 gün kala panelin üstünde uyarı çıkar.
- Anahtarda **güncelleme süresi** yazar. Bu süre içinde çıkan sürümler ek ücretsiz kullanılır. Süre bittikten sonra çıkan sürümler o anahtarla açılmaz; kurulu sürümünüz çalışmaya devam eder.
- Bilgisayar ya da donanım değişirse yeni makine kodu için satıcınıza başvurun.
- Program ve lisans anahtarı kopyalanamaz, satılamaz, kiralanamaz, başkasıyla paylaşılamaz; tersine mühendislik yapılamaz, lisans koruması devre dışı bırakılamaz. Sözleşmeye aykırı kullanımda lisans iptal edilebilir.
- Bağlayıcı metin, kurulumda kabul ettiğiniz **Son Kullanıcı Lisans Sözleşmesi**'dir. Türkiye Cumhuriyeti hukuku uygulanır.

---

## 🔒 Gizlilik

- Çizimleriniz, fire deponuz ve iş kaydınız hiçbir yere gönderilmez.
- Güncelleme denetimi bilgisayarınızdan hiçbir bilgi göndermez; yalnız `surum.txt` okunur.
- **Kâğıttan oku**'da **Oku** ve **Bilgisayarımda (Ollama)** fotoğrafı bilgisayardan çıkarmaz. **Güçlü oku** seçilirse fotoğraf, sizin seçtiğiniz yapay zekâ platformuna sizin anahtarınızla gönderilir ve o platformun koşullarına tabidir. Fotoğrafta kişisel veri varsa göndermeden önce gerekli izni almak kullanıcının sorumluluğundadır.

---

## 📜 Sürüm geçmişi

★ öne çıkan yenilik.

### 🆕 Son sürümler

<!-- yeni-surum: tools/yayinla.sh yeni sürüm satırını bunun altına ekler -->
- **3.10.8** (2026-11-12): Harf, logo ve çerçeveler çok daha doğru dizilir: çerçevenin içine parça girer, yanlış 'kendini kesiyor' uyarısı çıkmaz, levhaya sığmayan parçanın adı ve ölçüsü yazılır; boş stok listesinde en uygun standart levha seçilir.
- **3.10.6** (2026-11-06): Harf, logo ve yazılar çok daha sıkı dizilir (parça içinde parça, ilerleme çubuğu ve Durdur); Kesim'de kroki ve canlı kesim ölçüsü; Tabela gönye, Desen fade, Render fotoğrafı ve Fotoğrafa oturt düzeltmeleri.
- **3.10.2** (2026-11-05): Güncellemeden önce açık dosyalarınızı kaydetme uyarısı (panelde ve kurulumda); kod imzası gelene kadar yeni sürüm bu sayfadan indirilir; çıktıları kullanmadan önce kendiniz kontrol edin.
- **3.10.1** (2026-11-05): Güncelleme altyapısı: panel yeni sürümü bildirir; kurulum imzalı olunca indirip doğrulayacak ve CorelDRAW kapanınca kendisi kuracak. Kâğıttan oku'da yan ve üst/alt derz ayrı (7+5 gibi iki katlı derz de). Yerleşim'de ayrı nesnedeki büküm çizgileri parçayla birlikte gelir.
- **3.10.0** ★: Kâğıttan oku'da Kesim'deki gibi iki derz sütunu: yan derz ve üst/alt derz. Yapay zekâ kenarlardaki derz yazılarını ayrı okur, Düzelt/Denetle ikisini ayrı denetler; "Listeye ekle" ikisini Kesim'e ayrı yazar.

### 3.9: Render, Desen, Ters büküm

- **3.9.9** ★: Yerleşim: büküm çizgileri ayrı nesnede olsa da parçayla dizilir, poz yazısı parçanın üstüne gelir. Kesim: "Corel'e çiz" planı yeni sayfa açmadan çizimlerin sağına çizer; Corel'den alınan açılımlar planda gerçek şekliyle görünür. 3B: ara büküm çentiği derz profilini izler.
- **3.9.8** ★: Desen: 46 hazır desen, 6 grup (Havalandırma, Hoparlör, Geçiş, Dekoratif, Geometrik, Doğal). 7 yeni dizilim (dalgalı ızgara, balıksırtı, üçgen ızgara, kenara paralel, kabarcık, eğri boyunca, hasır örgü), 11 yeni eleman şekli, türbin ve Truchet döndürmeleri, 🎲 Zar at.
- **3.9.7** ★: Render: Corel'deki yazı ve logolar levhadaki yerleriyle gelir. Kabartma (ışıklı ya da ışıksız kutu harf), Fotoğrafa oturt (kendi fotoğrafınızda 4 köşeye tıklayın, levha perspektifle oturur), hazır görünümler (gündüz cadde, gece ışıklı, neon, katalog, stüdyo), sahne kaydet/aç, müşteriye tek sayfa sunum PDF.
- **3.9.6** ★: Yeni **Render** penceresi (3B sekmesinde): gerçekçi ışık, gölge ve yansıma; RAL renk, ahşap/mermer yüzey; LED, spot, ışıklı yazı, halo ve neon; cadde ortamında dükkân cephesi; PNG, video ve teklife resim.
- **3.9.5**: Kutu harf altyapısı (denemede; kararlı sürümde kapalı).
- **3.9.4** ★: Kesim, Desen ve Kâğıttan oku pencereleri laptop ekranına sığar. Kesim'de derz ikiye ayrıldı: yan derz ve üst/alt derz, "7+5" gibi çok katlı yazılabilir.
- **3.9.3**: Desen düzeltmeleri: küçük kendi nesneleriniz silinmez, perçin delikleri korunur, yalnız V-kanal ve Ters çizgiler büküm sayılır.
- **3.9.2**: Desen penceresi kapatılıp yeniden açılınca çıkan hata düzeltildi.
- **3.9.1** ★: Yeni **Desen** penceresi: levhanın ya da açılımın içi delik desenleriyle dolar. 10 dizilim, 11 eleman şekli ve kendi Corel şekliniz, 14 fade yönü, resimden yarım ton, 15 hazır desen ve Desenlerim. Delikler kenar payından ve V kanallardan uzak durur; delik sayısı, açık alan, kesim boyu ve CNC süresi yazılır.
- **3.9.0** ★: **Ters** renk: dışa katlanacak derzlerin büküm çizgisi mavi çizilir. 3B: kırmızı işarete tıklayınca çarpışan parçalar yazılır, ışık sürüklenir, levhanın rengi (RAL 9006, antrasit…) 3B'de görünür.

### 3.8: Canlı katlama, iç ölçü, sade panel, güncelleme denetimi

- **3.8.9** ★: Levha sayfasında **İç (kolon/kasa)** ölçü seçeneği: kaplanacak kolonun ya da kasanın ölçüsünü yazın, program bükümlü her kenara 5 mm ekler.
- **3.8.8** ★: 3B'de levha 4 mm kalınlığıyla çizilir, çarpışma kalınlıkla denetlenir; iç ölçüler atölye kuralıyla gösterilir.
- **3.8.7** ★: Canlı katlama: "Katla" kaydırıcısı ve ▶ ile 0°–90° arası. Çarpışan yer kırmızı, kapanmayan köşe sarı, en büyük boşluk mm olarak yazılır.
- **3.8.6** ★: Açılım test motoru: her açılım türü birçok ölçü, derz ve köşe tipiyle 3B'de denetlendi (364 durum). Düz uçlu derzde dışa dönen parçanın köşede açık kalması düzeltildi.
- **3.8.5**: CorelDRAW 2024, 2025 ve 2026'da denendi. 2020 ve öncesinde DXF'i panelin DXF KAYDET düğmesiyle alma notu.
- **3.8.4** ★: Kopyanız firma adınızla gelir (Ayarlar, kesim föyü, Excel metraj). Lisansta güncelleme süresi; panel, anahtarınızla açılmayacak sürümü kurmadan önce söyler.
- **3.8.3** ★: Program yeni sürümü kendisi bulur (günde bir kez yalnız sürüm bilgisi okunur, Ayarlar'dan kapatılabilir). Deneme süresi 7 gün. Lisans sözleşmesi yenilendi. Eklenti daha küçük.
- **3.8.2** ★: Kesim ve Yerleşim tek fire deposunu kullanır (F001, F002 …). Yerleşim'de az kullanılan ayarlar katlanır bir bölümde.
- **3.8.1** ★: Panel sadeleşti: yedi açılım simgesi tek **Açılım** simgesinde, tür şeritten seçilir. Simge sayısı 16'dan 10'a indi.
- **3.8.0** ★: Makine kodu Ayarlar'da bulanık görünür, tıklayınca açılır. Kesim tablolarında toplu yazma: Ctrl+Enter hepsine aynı değeri, Shift+Enter sıra numarasıyla yazar.

<details>
<summary><b>3.7: Kesim'de renk ve atık deposu, Güçlü oku</b></summary>

- **3.7.9** ★: Kesim'de renk ayrımı: Renk sütunu; bir levhaya tek malzeme ve tek renk dizilir, fireler rengiyle saklanır.
- **3.7.8**: Atık deposu artık Not Defteri dosyası (Belgelerim\AcmPlanning\atik_deposu.txt), elle düzeltilebilir.
- **3.7.7** ★: Atık deposu: kullanılabilir artıklar etiketlenip saklanır, sonraki işte stok levha olur, kesim onaylanınca depodan düşer.
- **3.7.6**: Kesim planı daha okunur: düz gri atık, artık ölçüleri, renkli parçalar; sığmayan parçalar ayrı kartta.
- **3.7.5**: Güçlü oku (Gemini): uygun modeller sırayla denenir; yoğun ya da kotası biten modelden kendiliğinden sonrakine geçilir.
- **3.7.4**: Güçlü oku: sunucu yoğunsa bekleyip yeniden dener. "77x79 = 2 K2" yazımında adet ve etiket doğru okunur.
- **3.7.3**: Güçlü oku: CorelDRAW'un interneti güvenlik duvarıyla kesikse ayrı yoldan bağlanır; hata, hangi sunucuya bağlanılamadığını söyler.
- **3.7.2**: Güçlü oku: Gemini'nin varsayılan modeli değişti (Google AI Studio anahtarıyla ücretsiz).
- **3.7.1** ★: Kesim motoru: stok yetmediğinde farklı sıralamaları da dener, en çok parçayı sığdıran yerleşimi seçer.
- **3.7.0** ★: Kesim planında atık parçalar yazılı ve vurgulu. PDF raporunda bir sayfaya birden çok levha sığar.

</details>

<details>
<summary><b>3.6: Kesim penceresi, Kâğıttan oku, Kıvrım, Birleşik tabela</b></summary>

- **3.6.9** ★: **Kâğıttan oku**: ölçü kâğıdının fotoğrafından parça listesi (Windows yazı tanıma ya da yapay zekâ ile Güçlü oku); emin olunamayan satırlar sarı. Yeni **Kıvrım** simgesi: kavisli yüz için V kanal sayısı, aralığı ve açılım.
- **3.6.8** ★: Kesim penceresinde fare tekerleğiyle yakınlaştırma, sürükleyerek kaydırma; "Levha parçaları" ve "Artık parçalar" kartları.
- **3.6.7**: Kesim planında yakınlaştırma, yazı boyu, renkli parçalar, kenar ölçüleri ve 90° döndürme düğmeleri.
- **3.6.6** ★: Kesim ayarları: mm/cm, ondalık, boyut sırası, aynı planlı levhaları gruplama, optimizasyon önceliği, kesim yönü.
- **3.6.5**: Kesim'de satır silme ve üst sıra rakam tuşlarıyla yazma düzeltildi.
- **3.6.3** ★: Kesim sırası planın altında geniş liste; testere ve kenar payında mm/cm; PDF raporu iyileşti.
- **3.6.2** ★: Kesim satırlarında etkin/devre dışı ✓ ve sil ✖; başlık menüsünden satır ekleme ve liste yükleme.
- **3.6.1** ★: Parçalar ve stok aynı sayfada; sığmayan parçalar kırmızı kutuda; PDF yazıcı penceresi açmadan kaydedilir.
- **3.6.0** ★: Yeni **Kesim** penceresi: parça listesi stok levhalara panel testeresiyle (giyotin) yerleşir; testere kalınlığı, kenar payı, en az fire ya da en az kesim; levha levha plan, kesim sırası, PDF ve proje kaydı. Yeni **Tabela** simgesi: birleşik tabela.

</details>

<details>
<summary><b>3.5 ve 3.4: 3B görünüm</b></summary>

- **3.5.0** ★: Panel bazı bilgisayarlarda ilk açılışta gelmiyordu, düzeltildi.
- **3.4.9**: Kurulumdaki Tanı raporu eklentiyi CorelDRAW dışında da dener; panel gelmeyen bilgisayarda sorunun yeri görünür.
- **3.4.8**: 3B'de çevrilen büküm yönü açılıma geçer, köşe kesimleri o yöne göre çizilir.
- **3.4.7**: Büküm yönlerinde "Varsayılan" düğmesi.
- **3.4.6**: 3B görüntüyü kopyala: WhatsApp'a, e-postaya ya da teklife yapıştırın.
- **3.4.5**: 3B çakışma uyarısı: seçilen büküm yönleriyle birbirine giren parçalar kırmızı.
- **3.4.4**: Yenilikler şeridi kısaldı (en çok 4 sürüm, tek satır).
- **3.4.3**: 3B görünüm arkadan başlar, bükümler hemen görünür; önizleme alanları büyüdü.
- **3.4.2**: Lisans iptali desteği (satıcı tarafı).
- **3.4.1** ★: Levha sayfalarında "Açılım | 3B" sekmeleri; seçtiğiniz sekme hatırlanır.
- **3.4.0** ★: **3B görünüm**: bütün levha sayfalarında açılımın bükülmüş hâli; döndürme, yakınlaştırma, Ön/Arka.

</details>

<details>
<summary><b>3.3 – 3.0: Köşe L parçası, İngilizce, teklif sayfası</b></summary>

- **3.3.7** ★: Perçin → **Köşe L parçası**: kaset köşesinde flanş delikleri ve L parçası; büküp L'yi alta koyunca delikler birebir çakışır.
- **3.3.6**: Lisans uzatma ve yedekleme (satıcı tarafı).
- **3.3.5**: Lisans bitiyor uyarısı: süreli lisansın bitmesine 5 gün kala panelde kırmızı satır.
- **3.3.4**: Süreli lisansta tarih denetimi; süresi dolan lisansta açık mesaj.
- **3.3.3**: Dar panelde sığmayan yazılar kısaltıldı.
- **3.3.2**: Para birimi ayarı (€, $, R$ …): teklif, maliyet, iş kaydı ve Excel bu birimle yazılır.
- **3.3.1** / **3.3.0** ★: Portekizce dil desteği (3.8.3'te kaldırıldı; program Türkçe ve İngilizce).
- **3.2.2**: Kurulum programı İngilizce; ölçü listesinde İngilizce yazım okunur (qty, return, flange).
- **3.2.1** ★: İngilizce çıktılar: kesim föyü, etiketler, Excel metraj ve teklif, iş kaydı, WhatsApp özeti.
- **3.2.0** ★: **English**: program İngilizce kullanılabilir (Ayarlar'ın en üstünden seçilir).
- **3.1.0**: Perçin: deliğin dönüşe sığmadığı durumlar "Not:" ile söylenir.
- **3.0.9**: Fire deposu: geri alınan işlerde fire kaybı ve yazılamayan depo dosyası düzeltildi.
- **3.0.8**: Metraj: "Gri" ve "GRİ" tek renk sayılır; teklif yuvarlaması Excel'deki gibi.
- **3.0.7** ★: Köşede bölünen Kompozit Profil açılımında alan, metraj ve maliyet bütün parçalarla hesaplanır.
- **3.0.6**: Dosyadan al (CSV): başlığın üstünde açıklama satırı olan dosyalar okunur.
- **3.0.5** ★: Yerleşim (gerçek şekil): bölünen profil açılımı bütün kutusuyla yerleşir.
- **3.0.4**: Perçin: dar üçgen yüzde delik yüzün içinde kalır.
- **3.0.3** ★: Metraj: isteğe bağlı **TEKLİF** sayfası (alan × m² fiyatı, KDV, genel toplam; Excel'de değiştirince yeniden hesaplanır).
- **3.0.2** ★: Ölçü listesi: birim cm ↔ mm değişince listeyi de çevirmeyi sorar.
- **3.0.1** ★: Açılım: dar ara büküm parçasında V-kanal kesim çizgisinde biter; kendini kesen şekilde uyarı çıkar.
- **3.0.0**: Panelde okunamayan sayı yazımı artık her kutuda söylenir, sessizce 0 sayılmaz.

</details>

<details>
<summary><b>2.9 ve 2.8.6 – 2.8.9: Yazım denetimleri</b></summary>

- **2.9.9**: Ayarlar'da "1:10" ölçek, "6 m/dk" ve "1.500 TL/saat" yazımı; okunamayan değer söylenir.
- **2.9.8**: Birim değişince dolu ölçü listesi için uyarı.
- **2.9.7**: Pozla ve İmalat kutularında yanlış yazım hata verir.
- **2.9.6**: Kompozit Profil: birim değişince kulak değeri çevrilir.
- **2.9.5**: Levha ölçüsünde binlik noktalı "1.200" yazımı için uyarı.
- **2.9.4**: Levha ölçüsü "1500 x 4000 mm" ya da "1.500x4.000" yazılabilir; "5 mm" gibi birimli değerler okunur.
- **2.9.3**: Adet alanına "4 ad", "4 adet" yazılabilir; okunamayan adet hata verir.
- **2.9.2** ★: Fiyatlarda "1.250" ve "1.250,50" yazımı doğru okunur; "TL", "₺/m²" yazılabilir.
- **2.9.1**: Kompozit Profil: birleşmemiş ama çok yakın çizgi uçları için uyarı.
- **2.9.0**: Dosyadan al: başlık satırı ilk 30 satırda aranır (üstünde firma bilgisi olan teklif sayfaları).
- **2.8.9**: Excel Yön sütununda ">" ve "^" okunur; UTF-16 metin dosyaları açılır.
- **2.8.8**: Dosyadan al: .xls, .ods ya da PDF seçilince ne yapılacağı yazılır; uzantısı yanlış dosya içeriğine göre okunur.
- **2.8.7**: Ölçü listesi: adet önce yazılınca ("4 x 1200x800") doğru yazımı gösterir.
- **2.8.6**: Ölçü listesinin özeti, cm iken metre yazılmış minicik ölçüyü uyarır.

</details>

---

## 🇬🇧 In English

**ACM Planning** is a CorelDRAW add-on for aluminium composite (ACM) panels: unfolds with V-grooves, cutting optimisation, nesting with an offcut store, live 3D folding, realistic render, perforation patterns, reading size lists from a photo, Excel take-off and quotes. The program runs in Turkish or English.

- **Install:** download the latest `AcmPlanning_Setup_X.Y.Z.exe` from the [`kurulum`](kurulum) folder and run it.
- **Update:** the panel checks [`surum.txt`](surum.txt) once a day and shows **Download**, which opens this page. **Save your open CorelDRAW files and close CorelDRAW before running the new setup.**
- **License:** a 7-day trial, then a license key for one computer (send the machine code from Settings to your seller).
- **Disclaimer:** check every unfold, size, cutting plan and quote yourself before production. No responsibility is accepted for wrong sizes, cuts, material or job losses.

---

<div align="center">
<sub>© 2026 ACM Planning. Tüm hakları saklıdır. Bu depoda yalnız kurulum dosyaları ve sürüm bilgisi bulunur; kaynak kod paylaşılmaz.</sub>
</div>
