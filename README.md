# hateb_stylesheet_vol1
はてなブログのテンプレート

## server の起動方法
```
npm run start
```

## 各種コマンドの意味

- "prestart": "start" 前に実行するスクリプト
- "start": "watch" と "server" を並列で実行する
- "server": port:3000 でサーバーを起動する
- "build": 各種ビルド（これで成果物ができる）
- "sass:build": sass から css への変換
- "autoprefixer": css に　postcss　をあてる
- "clean": 成果物を削除する,
- "watch": src/* を監視し、変更があれば "build" を実行する

## はてぶで確認する時
`ブログのデザイン > カスタマイズ > カスタムCSS`に以下を追加する
```
@import url("http://localhost:3000/css/main.css");
```
![image](https://user-images.githubusercontent.com/15308284/78985565-0e97d900-7b64-11ea-82e7-a6be37be52d3.png)
