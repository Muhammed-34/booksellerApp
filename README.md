# BooksellerApp

BooksellerApp, kitap yönetim sistemidir. Bu uygulama, kitap ekleme, silme, güncelleme, yayınevi ve yazar yönetimi gibi temel işlemleri yapmanıza olanak tanır. Ayrıca, kategoriye göre veya yazara göre raporlama özellikleri de sunar. Uygulama, kullanıcıların veritabanına MS SQL üzerinden bağlanmasını ve Repository Pattern mimarisi ile güvenli ve sürdürülebilir bir yapı oluşturmasını sağlar.

## Özellikler

- **Kitap Yönetimi**: Kitap ekleme, silme ve güncelleme işlemleri yapılabilir.
- **Yayınevi Yönetimi**: Yayınevlerini ekleyebilirsiniz.
- **Yazar Yönetimi**: Yazarları ekleyebilirsiniz.
- **Çalışan Yönetimi**: Çalışan ekleyebilirsiniz.
- **Login Sistemi**: Güvenli giriş yaparak uygulamayı kullanabilirsiniz.
- **Animasyonlu Açılış Ekranı**: Uygulamanın başlangıcında görsel animasyon ile hoş bir kullanıcı deneyimi sağlanır.
- **Raporlama**: Kitaplar, yazarlar ve kategoriler üzerine detaylı raporlama yapılabilir.
- **Repository Pattern**: Veritabanı işlemleri Repository Pattern kullanılarak yapılır.

## Teknolojiler

- **C#**: Uygulama ana dili.
- **Windows Forms**: Kullanıcı arayüzü.
- **MS SQL**: Veritabanı yönetimi.
- **Repository Pattern**: Veritabanı işlemleri için kullanılan mimari desen.
- **Entity Framework**: Veritabanı ile etkileşim için ORM aracı.

## Başlangıç

Bu projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### Gereksinimler

- Visual Studio 2019 veya daha yeni bir sürüm
- .NET Framework 4.7.2 veya daha yeni bir sürüm
- MS SQL Server

### Proje Kurulumu

1. Bu repoyu bilgisayarınıza klonlayın veya indirerek projeyi Visual Studio'da açın.

   ```bash
   git clone https://github.com/Muhammed-34/booksellerApp.git
   
2. Projeyi Visual Studio'da açın.

3. Context dosyasını düzenleyerek MS SQL veritabanı bağlantı dizesini (connection string) yapılandırın.

4. Veritabanını oluşturmak için Entity Framework ile gerekli migrasyonları uygulayın.

   ```bash
   Update-Database

5. Projeyi çalıştırın ve uygulamayı kullanmaya başlayın.

## Kullanıcı Arayüzü

- **Login Ekranı**: Uygulama ilk açıldığında kullanıcı adı ve şifre girilerek sisteme giriş yapılır.
- **Ana Menü**: Kitaplar, yazarlar, yayınevleri ve çalışanlar gibi ana modüllere erişilebilir.
- **Kitap Yönetimi**: Kitap eklemek, silmek veya güncellemek için ilgili ekranlara yönlendirilirsiniz.
- **Raporlama**: Kullanıcılar kategorilere göre veya yazarlara göre raporlama yapabilirler.

## Katkı Sağlama

Eğer bu projeye katkıda bulunmak isterseniz, aşağıdaki adımları takip edebilirsiniz:

1. Repo'yu forkladıktan sonra, kendi dalınızı oluşturun (`git checkout -b feature-xyz`).
2. Yapmak istediğiniz değişiklikleri gerçekleştirin.
3. Değişikliklerinizi commit'leyin ve bir pull request açın.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.
