Alışveriş ve Harcama Takip Sistemi - Proje Raporu
1. Projenin Amacı
Bu projenin amacı, kullanıcıların kendi alışveriş listelerini oluşturabilmeleri ve alışveriş yaptıkça ürünleri tamamlayarak harcamalarını takip edebilmeleri için bir web uygulaması geliştirmektir. Uygulama, kullanıcı bazlı veri saklama işlemlerini LocalStorage teknolojisi ile gerçekleştirmektedir.
2. Kullanılan Teknolojiler
• HTML5 – Sayfa yapısının oluşturulması için kullanılmıştır.
• CSS3 – Sayfa tasarımı ve stil düzenlemeleri için kullanılmıştır.
• Bootstrap 5 – Arayüzü daha modern, şık ve duyarlı hale getirmek için kullanılmıştır.
• JavaScript  – Uygulamanın dinamik işlevlerini sağlamak için kullanılmıştır.
• LocalStorage – Kullanıcı verilerini (hesap bilgileri, ürün listeleri, harcama kayıtları) tarayıcı üzerinde saklamak için kullanılmıştır.
3. Proje Özeti
Uygulama, kullanıcıların kayıt olabildiği, giriş yapabildiği ve kendi alışveriş listelerini yönetebildiği bir sistemdir. Her kullanıcı, kendine ait ürün listelerini oluşturabilir, satın alınan ürünlerin fiyatlarını kaydedebilir ve günlük harcamalarını görebilir. Buna istinaden aylık harcama takiplerini de yapabilir. Tüm veriler kullanıcı bazlı olarak LocalStorage’da tutulmaktadır.
4. Sistemin Çalışma Mantığı
• Kullanıcı ilk olarak kayıt ekranından kullanıcı adı ve şifre belirleyerek kayıt olur.
• Giriş yapıldıktan sonra kullanıcı kendi alışveriş listesini oluşturabilir.
• Ürünler 'Alınacaklar' listesine eklenir.
• Ürün alındığında fiyat bilgisi girilerek 'Alınmışlar' listesine taşınır.
• Alınmış ürünlerin toplam tutarı ve günlük bazda harcama özeti otomatik olarak hesaplanır.
• Kullanıcı çıkış yaptığında veriler LocalStorage’da saklanmaya devam eder.
5. LocalStorage Kullanımı
Uygulamada LocalStorage, kullanıcı bilgilerini ve ürün listelerini kalıcı olarak saklamak için kullanılmıştır. Her kullanıcı için ayrı bir JSON objesi tutulur. Bu objelerde aşağıdaki bilgiler yer alır:

• Kullanıcı adı ve şifre
• Bekleyen ürün listesi 
• Tamamlanmış ürün listesi 

Bu yapı sayesinde kullanıcı farklı zamanlarda giriş yaptığında bile verileri korunur.
6. Ekranlar ve Fonksiyonlar
Uygulama iki ana ekrandan oluşmaktadır:

• Giriş/Kayıt Ekranı: Kullanıcının sisteme giriş yapması veya yeni bir hesap oluşturması için kullanılır.
• Ana Ekran: Alışveriş listesi yönetimi, harcama takibi ve kullanıcı bilgilerini görüntüleme işlevlerini içerir.
7. Sonuç ve Değerlendirme
Bu proje, JavaScript ve LocalStorage kullanarak kullanıcı bazlı veri yönetimini başarılı şekilde uygulamaktadır. Kullanıcıların alışveriş alışkanlıklarını takip etmesi ve harcamalarını analiz etmesi için pratik bir çözüm


Barış KÜYÜK
2314506030
Bilgisayar Prog.
