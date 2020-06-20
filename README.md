# unixsocket-php-fpm

### 試し方

```
$ git clone https://github.com/yCroma/unixsocket-php-fpm.git unixsocket
$ cd unixsocket
$ docker-compose up -d --build

# もし表示されなかったら
$ docker-compose restart

# コンテナの中身が見たい
$ docker-compose exec nginx ash
$ docker-compose exec php_fpm ash
```

[http://localhost:28000](http://localhost:2800) へアクセス
