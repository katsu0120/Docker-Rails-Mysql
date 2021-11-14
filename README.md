# Ruby on Rails チュートリアルのサンプルアプリケーションをDocker化してDBをMysqlにしました。

## 使い方

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。
$ git clone https://github.com/katsu0120/rails-docker-mysql1111.git

その後、imageをbuildして下さい

```
$ docker-compose build
```

yarnをインストールして下さい

```
$ docker-compose run web yarn install --check-files
```

コンテナを立ち上げて下さい

```
$ docker-compose up
```

コンテナを閉じたい時は下記コマンドで閉じて下さい

```
$ docker-compose down
```
