# Test Senaryoları

## Senaryo 1: İletişim formu hatasız yükleniyor

**Açıklama:** İletişim formu sayfa üzerinde hatasız bir şekilde yüklenmelidir.

**Test Adı:** İletişim formunun hatasız yüklenmesi

**Test Adımları:**
1. Sayfa yüklendiğinde iletişim formu görüntülenir.
2. İletişim formunun tüm bileşenleri (ad, soyad, email, mesaj) görüntülenir.
3. Formdaki bileşenlerin varsayılan değerleri doğru bir şekilde ayarlanmıştır.

**Beklenen Sonuç:** İletişim formu hatasız bir şekilde yüklenir ve bileşenler doğru bir şekilde görüntülenir.

## Senaryo 2: Başlık doğru test içeriğine sahipse

**Açıklama:** Sayfanın başlığı (h1 elementi) doğru test içeriğine sahip olmalıdır.

**Test Adı:** Sayfa başlığının doğruluğu

**Test Adımları:**
1. Sayfa yüklendiğinde başlık (h1 elementi) görüntülenir.
2. Başlık içeriği doğru test içeriğine sahip olmalıdır.

**Beklenen Sonuç:** Başlık (h1 elementi) doğru test içeriğine sahip olmalıdır.

## Senaryo 3: Kullanıcı Ad bölümüne 5 karakterden az bir şey yazarsa hata mesajı içeriyor

**Açıklama:** Kullanıcı Adı (ad) bölümüne 5 karakterden az bir şey yazıldığında bileşen 1 hata mesajı içermelidir.

**Test Adı:** Kullanıcı Adı bölümünde karakter sınırı hatası

**Test Adımları:**
1. Sayfa yüklendiğinde kullanıcı Ad bölümü görüntülenir.
2. Kullanıcı Ad bölümüne 5 karakterden az bir değer girilir.

**Beklenen Sonuç:** Kullanıcı Ad bölümü 5 karakterden az bir değer girildiğinde hata mesajı görüntülenir.

## Senaryo 4: Kullanıcı hiçbir inputu doldurmadıysa ÜÇ hata mesajı render edildiğinde

**Açıklama:** Kullanıcı hiçbir input alanını doldurmadığında üç hata mesajı render edilmelidir.

**Test Adı:** Tüm input alanlarının boş olması durumunda hata mesajları

**Test Adımları:**
1. Sayfa yüklendiğinde iletişim formu görüntülenir.
2. Form gönder butonuna tıklanır.