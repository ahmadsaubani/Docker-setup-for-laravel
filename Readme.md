```Installation```


`` Docker build and run ``
- `` docker-compose build && docker-compose up -d ``
- test run in `` localhost:8088 ``


`` for running php artisan in docker ``
- RUN `` docker-compose exec php php /var/www/html/artisan migrate ``

`` setup laravel environtment ``
- `` cp .env.example .env ``
- `` composer install ``
- `` set DB_HOST in .env to mysql ``
- `` set DB_DATABASE in .env to homestead like in docker-compose.yml ``
- `` set DB_USER in .env to homestead like in docker-compose.yml``
- `` set DB_PASSWORD in .env to secret ``