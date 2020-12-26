# try_webpack_bootstrap5

- [Webpack を使って Bootstrap 5 をインストール（バンドル）](https://www.webdesignleaves.com/pr/plugins/bootstrap5_webpack.html)

1. コンテンツ作成

```bash
$ vi index.html
$ mkdir src
$ mkdir src/images
$ vi src/index.js
$ vi src/custom.scss
```

2. webpack とローダーをインストール

```bash
$ npm init -y
$ npm i -D webpack webpack-cli css-loader file-loader sass sass-loader fibers postcss-loader autoprefixer mini-css-extract-plugin
$ npm i bootstrap@next @popperjs/core
$ vi webpack.config.js
$ vi package.json
```

3. ビルド

```bash
$ npm run build
```
