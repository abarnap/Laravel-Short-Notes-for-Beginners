
# Laravel Short Notes for Beginners

A short hint notes for laravel developer


## Basic Commands

##### 1. Command to create new project using composer
###### &nbsp;&nbsp;&nbsp;Instead of demo give your project name

````
composer create-project laravel/laravel demo
````

##### 2. Command to create new table/migration file
###### &nbsp;&nbsp;&nbsp;Instead of create_products_table give your table name

````
php artisan make:migration create_products_table
````

##### 3. Command to create new model file
###### &nbsp;&nbsp;&nbsp;Instead of Product give your model name

````
php artisan make:model Product
````

##### 4. Command to create new controller file
###### &nbsp;&nbsp;&nbsp;Instead of ProductController give your controller name

````
php artisan make:controller ProductController
````

##### 5. Command to create ( migration, model & controller in one line )
###### &nbsp;&nbsp;&nbsp;Instead of Product give your model name

> **m** - *migration* | **c** - *controller* | **r** - *resource*
````
php artisan make:model Product -mcr
````

##### 6. Command to create seeder
###### &nbsp;&nbsp;&nbsp;Instead of ProductSeeder give your seeder name

````
php artisan make:seeder ProductSeeder -mcr
````

##### 7. Command to migrate table
````
php artisan migrate
````

##### 8. Command to drop all table and migrate
````
php artisan migrate:fresh
````

##### 9. Command to migrate table and insert data from the seeder to database
````
php artisan migrate:fresh --seed
````
