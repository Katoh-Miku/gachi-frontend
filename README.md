# gachi-frontend

## npm をインストール

```
npm init -y
```

## パッケージをダウンロード

reload

```
npm i -D reload
```

sass

```
npm i -D sass
```

prettier と onchange をインストール

```
npm i -D prettier onchange
```

## package.js 内の script を編集

プロジェクトに応じて調節

```
"start": "reload -d ./src",
"sass": "sass --watch ./src/styles/:./src/styles/"
```

## script の起動

```
npm run start
npm run sass
```

## node_module ファイルをダウンロードする

```
npm i
```
