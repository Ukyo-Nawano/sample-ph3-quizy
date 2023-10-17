# phase3 Quizy sample code

## setup

POSSE課題だよー

`git clone https://github.com/posse-ap/sample-ph3-quizy.git`

`cd sample-ph3-quizy`

`docker-compose up -d`

`docker exec -it <appコンテナID> composer install`

`docker exec -it <appコンテナID> php artisan migrate:refresh --seed`

And you can access `http://localhost`
