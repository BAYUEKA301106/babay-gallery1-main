# WEB GALLERY

## Tentang Website

Simpelnya ini hanyalah Web yang saya buat dengan mengikuti style instagram, facebook dan twitter namun versi low budget yang sangat minim. meskipun tidak terlalu mirip, tapi fungsi yang ditonjolkan dari web ini adalah mampu memuat gallery dan user lain bisa melihat gambar apa yang kita posting.

## Fitur

Untuk Fitur masih minim:
- sign up
- log in
- log out
- multiuser
- add poto
- add album
- edit profile
- add comment
- edit comment
- delete comment
- like
- dll

## Tampilan Website

![Screenshot (217)](https://github.com/BAYUEKA301106/babay-gallery1-main/assets/124749217/e7ce9b10-71b6-400a-ac91-a9dc1fd8fc24)

![Screenshot (218)](https://github.com/BAYUEKA301106/babay-gallery1-main/assets/124749217/18c6d7a1-3e1a-4c41-9860-8231bdf5b982)

![Screenshot (215)](https://github.com/BAYUEKA301106/babay-gallery1-main/assets/124749217/f6f18956-de26-46b4-846b-c2079e247e1a)

![Screenshot (216)](https://github.com/BAYUEKA301106/babay-gallery1-main/assets/124749217/d7ca3bab-1965-4e3f-be3f-2eae0413ed0b)


## ERD, Relasi dan UML Use Case

- ERD

![ERD](https://github.com/BAYUEKA301106/babay-gallery1-main/assets/124749217/1cd7405a-5d3d-453e-84b9-f081b458d8e0)

- Relasi

![RELASI](https://github.com/BAYUEKA301106/babay-gallery1-main/assets/124749217/459dbe0e-b3e3-4f9d-8774-2a95799acbc3)

- UML

![UML](https://github.com/BAYUEKA301106/babay-gallery1-main/assets/124749217/6f3d5794-6ba3-4749-aedc-738e9dcfb48b)

## Prasyaratan

- PHP 8.2.8 & Web Server (Apache, Lighttpd, atau Nginx)
- Database (MariaDB dengan v11.0.3 atau PostgreSQL)
- Web Browser (Firefox, Safari, Opera, Microsoft Edge dll)

## Instalasi
1. Clone Repository
```
https://github.com/BAYUEKA301106/babay-gallery1-main
```

2. Install Composer
```
composer install
```
atau
```
composer update
```

3. Copy .Env
```
copy .env.example .env
```

4. Setting database di .env
```
DB_PORT=3306
DB_DATABASE=laravel_gallery
DB_USERNAME=root
DB_PASSWORD=
```

5. Generate key
```
php artisan key:generate
```

6. Jalankan migrate dan seeder
```
php artisan migrate --seed
```

7. Buat Storage Link
```
php artisan storage:link
```

8. jangan lupa menginstall NPM
```
npm install
```
lalu jalankan
```
npm run dev
```

8. Jalankan Serve
```
php artisan serve
```
