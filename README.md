<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## Docker compose

`docker compose up -d db`
`docker compose up --build laravelapp`

## Migrate database

`docker exec laravelapp php artisan migrate`

## Access database

`docker exec -it db mysql -u root -p`

## Remove containers
`docker compose down -v`

## Test the request from Insomnia or something else
`http://localhost:8000/api/player/1`