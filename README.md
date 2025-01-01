# Laravel 11 Cheatsheet

---

## Kurulum

### Yeni Laravel Projesi Oluştur

```bash
composer create-project laravel/laravel proje-adi
```

**Açıklama:** Yeni bir Laravel projesi oluşturur. Proje klasörü ve gerekli bağımlılıklar kurulur.

---

## Artisan Komutları

### Controller Oluştur

```bash
php artisan make:controller UserController
```

**Açıklama:** Controller, uygulamanın iş mantığını yönetir. Bu komut, `UserController` adında bir controller oluşturur.

---

### Model Oluştur

```bash
php artisan make:model User
```

**Açıklama:** Model, veritabanı tablolarıyla etkileşimi sağlar. Bu komut, `User` adında bir model oluşturur.
