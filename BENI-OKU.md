# Lamel’i Android’e uygulama olarak kurmak

Bu klasördeki dosyalar Lamel’in kurulabilir (PWA) sürümü. İnternette bir adrese
yüklendikten sonra Android’de Chrome ile normal bir uygulama gibi kurulur:
ana ekranda simgesi olur, kendi penceresinde açılır ve internetsiz de çalışır.
Görüntüleriniz yine hiçbir yere gönderilmez, her şey telefonda işlenir.

## 1. Dosyaları GitHub Pages’e yükleyin (bir kez, bilgisayardan)

1. github.com’da ücretsiz bir hesap açın ya da giriş yapın.
2. Sağ üstteki “+” menüsünden “New repository” seçin. Adı örneğin `lamel` olsun,
   “Public” işaretli kalsın, “Create repository” deyin.
3. Açılan sayfada “uploading an existing file” bağlantısına tıklayın.
4. Bu klasördeki altı dosyanın hepsini (index.html, manifest.webmanifest, sw.js
   ve üç simge dosyası) sayfaya sürükleyip “Commit changes” deyin.
5. Depo sayfasında Settings > Pages bölümüne gidin. “Branch” altında `main`
   ve `/ (root)` seçip “Save” deyin.
6. Bir iki dakika sonra aynı sayfada adresiniz görünür, örneğin
   `https://kullaniciadiniz.github.io/lamel/`

## 2. Telefona kurun

1. Android’de Chrome ile bu adresi açın.
2. Sağ üstteki üç nokta menüsünden “Uygulamayı yükle” (bazı sürümlerde
   “Ana ekrana ekle”) seçin.
3. Lamel artık uygulama listenizde. LIF ve TIFF dosyalarını “Aç” düğmesiyle
   telefonun Dosyalar uygulamasından seçebilirsiniz. Kaydettiğiniz PNG, ZIP ve
   CSV dosyaları İndirilenler klasörüne iner.

Bilgisayarda da aynı adresi Chrome ya da Edge ile açıp adres çubuğundaki
yükleme simgesiyle kurabilirsiniz. Bilgisayarda kurulu sürüm, .lif ve .tif
dosyalarını “Birlikte aç > Lamel” ile doğrudan açabilir.

## Güncelleme

Yeni bir sürüm geldiğinde GitHub’daki `index.html` dosyasını yenisiyle
değiştirmeniz yeterli. Telefondaki uygulama bir sonraki açılışta internete
bağlıysa yeni sürümü alır.

## APK dosyası gerekiyorsa

Uygulamayı Play Store’a koymak ya da APK olarak paylaşmak isterseniz,
GitHub Pages adresinizi pwabuilder.com’a girip “Package for stores > Android”
ile APK ve AAB dosyası oluşturabilirsiniz.
