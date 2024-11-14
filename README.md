# これは何
クライアントからWebSocketで受け取った文字列をクライアントに送り返すだけのサーバープログラムです

これと一緒に使ってね
https://github.com/nexus106/ws_comment_static

# 使い方
## docker-composeで起動
```
docker compose up -d
```
これでバックグラウンドで起動します

## nodeが入っている環境で使う（dockerを使いたくない場合）
```
npm init -y
npm i ws --save
node src/index.js
```