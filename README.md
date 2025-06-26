お問合せフォーム

Docker ビルド
git@github.com:a0620mi/test-1.git
docker compose up -d -build

laravel環境構築
docker-compose exec php bash
composer install
.env.exampleから.env作成と編集
php artisan migrate
php artisan db:seed

使用技術
MySQL ８.0
laravel 8.8
PHP 8.4

URL
開発環境 
phpMyAdmin http://localhost:8080/index.php?route=/
