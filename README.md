# docker-laravel

Build Laravel's development environment using docker.
PHP7.4/MySQL8.0/nginx/redis/node

## Build
初回起動時、dockerコンテナ立ち上げる

'docker-compose up -d --build'



mysqlコンテナ

'docker-compose exec db bash -c 'mysql -uroot -p${MYSQL_PASSWORD} ${MYSQL_DATABASE}''

PHPコンテナ

'docker-compose exec app ash'

nodeコンテナ

docker-compose exec node ash


ブラウザ
http://127.0.0.1:10080

##SQLクライアント接続設定

Name: docker-laravel(任意)

Host: 127.0.0.1

Port: 13306

User: homestead

Password: secret

Database: homestead
