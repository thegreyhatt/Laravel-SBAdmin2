# Start Bootstrap Admin 2 - Laravel Integration

### Installation

Run
Then, add the service provider to `config/app.php`


## 1. Installation

1. Require the package using composer:

	```
	composer require thegreyhatt/laravel-sbadmin2
	```

2. Add the service provider to the `providers` in `config/app.php`:

	```php
	Thegreyhatt\LaravelSBAdmin2\ServiceProvider::class
	```

3. Publish the public assets:

    ```
    php artisan vendor:publish --provider="Thegreyhatt\LaravelSBAdmin2\ServiceProvider" --tag=assets
    ```