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
└── yarn.lock
```

- `dist`: webpack でビルドしたあとのファイルを配置
- `public`: 静的ファイルなどを配置
- `src`: React のコンポーネントとかを配置

基本的に`public`、`src`配下のファイルをバンドルして `dist` に吐き出すようにしている

## Usage

### `yarn dev`

**development**モードで webpack-dev-server を起動

### `yarn prod`

**production**モードで webpack-dev-server を起動

### `yarn build`

`dist`にビルドしたファイルを吐き出す
