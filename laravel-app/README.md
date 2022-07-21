1. `composer create-project laravel/laravel laravel-app`

2. `cd laravel-app`

3. `php artisan serve`

4. `composer require bref/laravel-bridge --update-with-dependencies`
   REFER - https://github.com/brefphp/laravel-bridge

5. `php artisan vendor:publish --tag=serverless-config`
   REFER - https://bref.sh/docs/runtimes/https://bref.sh/docs/runtimes/
   Update the layer versions to latest - ${bref:layer.php-81} / ${bref:layer.php-81-fpm}

6. `serverless deploy`
