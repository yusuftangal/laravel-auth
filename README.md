# Laravel Auth Example

Bu proje, Laravel framework'ü kullanılarak geliştirilmiş bir kimlik doğrulama (authentication) örneğidir.

## Özellikler

- Kullanıcı kaydı
- Kullanıcı girişi
- Şifre sıfırlama
- Email doğrulama
- Kullanıcı profili yönetimi

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/yusufangel/laravel-auth.git
cd laravel-auth
```

2. Bağımlılıkları yükleyin:
```bash
composer install
```

3. `.env` dosyasını oluşturun:
```bash
cp .env.example .env
```

4. Uygulama anahtarını oluşturun:
```bash
php artisan key:generate
```

5. Veritabanı ayarlarını yapın:
- `.env` dosyasında veritabanı bilgilerinizi düzenleyin
- Migrations'ları çalıştırın:
```bash
php artisan migrate
```

6. Uygulamayı çalıştırın:
```bash
php artisan serve
npm run dev
```

## Kullanım

- `/register` - Yeni kullanıcı kaydı
- `/login` - Kullanıcı girişi
- `/password/reset` - Şifre sıfırlama
- `/home` - Kullanıcı paneli

## Teknolojiler

- Laravel 12
- MySQL
- Bootstrap

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.
