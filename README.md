## Docker with Laravel 8  

Docker clean Laravel 8 installation with PostgreSQL, Redis and nginx

## Installation

1. Setup .env  
2. `docker-compose up -d --build`
3. `docker-compose run --rm composer install`        
4. `docker-compose run --rm artisan key:generate`  
5. `docker-compose run --rm artisan migrate`  
6. `docker-compose run --rm artisan migrate`  
