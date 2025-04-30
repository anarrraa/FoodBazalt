<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

---

# FoodBazalt - QR Ресторан Захиалгын Систем

**FoodBazalt** нь хэрэглэгч QR код уншуулан өөрийн ширээнээсээ хоол, ундаагаа шууд захиалах боломжтой **орчин үеийн ресторан захиалгын систем** юм.

## 🥗 Системийн Давуу Тал

- 📱 Хэрэглэгч QR код уншуулаад ямар ч апп татахгүйгээр шууд захиалга хийх боломжтой
- 🧾 Захиалгын мэдээлэл бодит цагийн горимоор гал тогоо болон ажилтнуудад дамжина
- 👨‍👩‍👧‍👦 Интерфейс энгийн бөгөөд бүх насны хэрэглэгчдэд ойлгомжтой
- 🔓 Хэрэглэгч бүртгүүлэлтгүйгээр захиалга өгөх боломжтой
- ⚡ Автоматжуулалт нь үйлчилгээний хурд, чанарыг нэмэгдүүлнэ

## 💡 FoodBazalt гэж юу вэ?

### 1. Тодорхойлолт

**FoodBazalt** нь рестораны ширээ бүр дээрх QR кодыг уншуулах замаар хэрэглэгчдэд өөрийн гар утсаар захиалга өгөх боломж олгодог Laravel суурьтай вэб систем юм.

### 2. Ажиллах зарчим

1. Хэрэглэгч ширээн дээрх QR кодыг гар утсаараа уншуулна.
2. Рестораны меню хэрэглэгчийн дэлгэцэнд гарч ирнэ.
3. Хэрэглэгч хүссэн хоол, ундаагаа сонгон, захиалгаа баталгаажуулна.
4. Захиалга бодит цагийн мэдээллээр гал тогоо болон хариуцсан ажилтанд дамжина.
5. Захиалга бэлдэгдэж, хэрэглэгчид хүргэгдэнэ.

## ⚙️ Технологи

- [Laravel](https://laravel.com) - Backend Framework
- MySQL - Өгөгдлийн сан
- Blade/React - Хэрэглэгчийн интерфейс (сонгосон хувилбараасаа шалтгаална)
- RESTful API

## 🛠 Төслийг Хөгжүүлэх

```bash
git clone https://github.com/AnarTHEmegamind0/FoodBazalt.git
cd FoodBazalt
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm run build
npm run dev
php artisan serve
