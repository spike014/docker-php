# docker-php
Setup php env by Docker

> Especially Laravel, Laravel-admin.

## Config

1. mv

```
cp docker-compose.sample.yml docker-compose.yml
```

2. Config your `php` project directory:

line 11

```
      - "${your_project}:/usr/share/nginx/html"
```

line 21

```
      - "${your_project}:/var/www"
```

## Start

```
docker-compose up -d
```

down

```
docker-compose down
```

## php version

7.3

> change it in ./php/Dockerfile

# LICENSE

MIT
