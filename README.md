# README

## 環境構築方法

1. リポジトリをローカル環境にクローンする
```
git clone https://github.com/Hyakusetufutou/rails-docker.git
```

2. `rails-dockerフォルダ`に移動
```
cd rails-docker
```

3. ビルドをする
```
docker-compose build
```

4. データベース作成とWebpackerのインストールを行う
```
docker-compose run web rails db:cretate db:migrate
```

5. コンテナを作成・起動する
```
docker-compose up
```
6. localhost:3000にアクセスし、アプリが起動しているか確認する
```
localhost:3000
```
