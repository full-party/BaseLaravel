# Development Laravel
### docker up
```
cd BaseLaravel/
docker-compose build
docker-compose up -d
```
### laravel init
```
cp ./laravel/.env.example ./laravel/.env
docker exec -it baselaravel_web_1 bash
composer install
```

http://localhost:8000
