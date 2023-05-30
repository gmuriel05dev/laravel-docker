# laravel-docker

```
-Nginx
-php 7.3
-laravel 8
```

1 . Configurar base de datos, chequear .env

2 . correr migraciones 


```
ejemplo: "docker-compose exec nombre-de-servicio comando"

docker-compose exec php php /var/www/html/artisan migrate
```