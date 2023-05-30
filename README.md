# laravel-docker

```
-Nginx
-php 7.3
-laravel 8
```

1 . cp ./src/.env.example ./src/.env

2 . Configurar base de datos, chequear ./src/.env.example

3 . docker-compose up -d

4 . correr migraciones 


```
ejemplo: "docker-compose exec nombre-de-servicio comando"

docker-compose exec php php /var/www/html/artisan migrate
```