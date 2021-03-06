# Laravel 8
## 1.Cài đặt
### Cú pháp
#### Cài qua composer

>composer create-project --prefer-dist laravel/laravel

#### Cài qua laravel

>composer global require laravel/installer
>laravel new folder_name

#### Khởi chạy
> php artisan serve

## 2.Router

### Cú pháp
* Route::get($uri, $callback) - nhận resquest với phương thức GET.
* Route::post($uri, $callback) - nhận resquest với phương thức POST.
* Route::put($uri, $callback) - nhận resquest với phương thức PUT.
* Route::patch($uri, $callback) - nhận resquest với phương thức PATCH.
* Route::delete($uri, $callback) - nhận resquest với phương thức DELETE.
* Route::options($uri, $callback) - nhận resquest với phương thức OPTIONS.

### Mì ăn liền 

>Route::get('welcome', function () {
    return "Xin chào";
});
>

