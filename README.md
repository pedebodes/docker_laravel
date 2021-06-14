# docker-laravel-nginx-mysql-example
Este é um exemplo de como usar docker-compose para criar um ambiente laravel / nginx / mysql.


## Como usar
Execute este programa como segue:
```
$ git clone https://github.com/pedebodes/docker_laravel.git
$ cd docker_laravel
$ docker-compose up -d --build
$ docker-compose exec laravel ash
# No diretorio laravel:
$ sh -x ../laravel_build.sh
```
And then see http://localhost:10080
You can see laravel is working on docker there.
