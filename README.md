# Laravelの設定済みファイル
* Laravel Framework 6.6.0
* `config\app.php`の設定
```php
'timezone' => 'Asia/Tokyo',
```
* 外部パッケージ`laravel/ui`の導入と認証機能追加
```
$ composer require laravel/ui --dev
$ php artisan ui vue --auth
$ npm install 
$ npm run dev
```