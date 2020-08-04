# grafana env

## コンテナ立ち上げ
```
❯ docker-compose up -d
```

## ブラウザからgrafanaにアクセス

```
http://lodalhost:3000
```
- ID: admin
- Password: admin

## DBインポート
mysqlのdocker内ipアドレス確認

```
❯ docker exec -it mysql_db hostname -i
172.18.0.2
```
- IP Adress: <上記のIP>:3306
- user: root
- password: root
- DB name: world
