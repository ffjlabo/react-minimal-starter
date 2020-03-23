# react-minimal-starter

React と Redux を利用するための環境

## ディレクトリ構成

```
├── README.md
├── dist
├── node_modules
├── package.json
├── public
│   └── index.html
├── src
│   ├── components
│   └── index.js
├── webpack.config.js
├── .env
└── yarn.lock
```

- `dist`: webpack でビルドしたあとのファイルを配置
- `public`: 静的ファイルなどを配置
- `src`: React のコンポーネントとかを配置
- `.env`: webpack-dev-server に読み込ませる環境変数

基本的に`public`、`src`配下のファイルをバンドルして `dist` に吐き出すようにしている

## 事前準備

### 任意 `touch .env`

webpack-dev-server で環境変数を読み込めるようにしている。
必要な環境変数があれば適宜作成すること。

## 使い方

### `yarn dev`

**development**モードで webpack-dev-server を起動

### `yarn prod`

**production**モードで webpack-dev-server を起動

### `yarn build`

`dist`にビルドしたファイルを吐き出す
