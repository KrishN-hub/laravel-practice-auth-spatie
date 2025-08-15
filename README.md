# laravel-practice-auth-spatie
practice manage auth permission using spatie 

1. pull alreadey created auth-app project
2. install spatie package based on spatie installation laravel- https://spatie.be/docs/laravel-permission/v6/installation-laravel
3. added the hasRole- use Spatie\Permission\Traits\HasRoles; in user model( Basic usage - in spatie documentation)
4. added oackage middle ware code into app.php (Basic usage -> Using a middleware->Package Middleware- in spatie documentation)
5. create Role seeder - php artisan make:seeder RoleSeeder
6. create Admin seeder - php artisan make:seeder AdminSeeder
7. create role in seeder - in RoleSeeder.php -  spatie documentation -> Basic usage
