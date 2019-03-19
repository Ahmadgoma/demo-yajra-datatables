# demo-yajra-datatables
Demo laravel with yajra datatables package

composer install 
to install laravel and yajra dtatables packages .

php artisan vendor:publish
to copy yajra configuration file in your application from vendor package file

create database and connect in .env 

php artisan migrate

php artisan tinker

factory(App\User::class, 10000)->create();

and try more and more if return duplication error. 

php artisan serve
