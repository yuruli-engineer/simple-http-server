## 説明
このリポジトリは、Github Actions -> Code deploy -> Fargate を実行するための学習用のリポジトリです。

[ドメイン]/ でhtmlを返すだけのアプリです。

# ローカル環境構築
## ビルド
```
docker compose build
```
## サーバー起動
```
docker compose up
```
## アクセス
http://localhost:9000


# 本番
```
docker build -t simple-http-server
```

