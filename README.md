# nolack
slack的なノートアプリ。

## Set Up
* nodeのバージョンを14.19.0に合わせる(nodebrewやnodenvなどのパッケージマネージャ推奨)
```
$ node -v
v14.19.0
```

* rubyのバージョンを3.1.2に合わせる（rbenv推奨）
```
$ ruby -v
ruby 3.1.2
```

* リポジトリのクローン
```
$ git clone https://github.com/jun-sugawara/norack.git
```

* docker起動
```
$ docker-compose up -d
```

* yarnがインストールされていなくてフロントサイトが出ない時は下記を実行
```
$ yarn 
``` 

* APIサーバーポート：localhost:3000
* frontサーバーポート：localhost:8080

## mysql接続

```
docker-compose exec db mysql -u root -p
//password、接続手順はmattermostの「nolack mysql接続メモ」参照
```
