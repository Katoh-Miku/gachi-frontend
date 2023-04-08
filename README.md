# gachi-frontend

## npmをインストール
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

prettierとonchangeをインストール
```
npm i -D prettier onchange
```

## package.js内のscriptを編集
プロジェクトに応じて調節
```
"start": "reload -d ./src",
"sass": "sass --watch ./src/styles/:./src/styles/"
```

## scriptの起動
```
npm run start
npm run sass
```

## node_moduleファイルをダウンロードする
```
npm i
```
