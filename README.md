# Docker Compose files for PHP development

## Apache + PostgreSQL + MySQL
    docker-compose -f docker-compose.apache.yml up

## nginx + Apache + PostgreSQL + MySQL
    docker-compose -f docker-compose.nginx+apache.yml up

## nginx + PHP-FPM + PostgreSQL + MySQL
    docker-compose -f docker-compose.nginx+php-fpm.yml up

## How to connect to PostgreSQL
    $db = new PDO('pgsql:host=postgres;dbname=postgres;user=postgres');

## How to connect to MySQL
    $db = new PDO('mysql:host=mysql;dbname=mysql', 'root');

# Notice from Shimanskiy: Should create ./www directory mannualy.
