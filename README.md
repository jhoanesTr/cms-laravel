## Primeros Comandos
```shell
composer require laravel/ui --dev
composer require laravel-frontend-presets/tailwindcss --dev
php artisan ui tailwindcss --auth
npm install
npm audit fix --force
npm audit fix
npm run dev
```

##Creando ModeloTablaControlador
```shell
php artisan make:model Post -mcr
php artisan make:model Comment -mcr
```

##Comandos
```shell
composer require cviebrock/eloquent-sluggable
php artisan migrate
php artisan make:factory PostFactory -m Post
php artisan db:seed
php artisan make:request Comment
php artisan make:request PostRequest
```



