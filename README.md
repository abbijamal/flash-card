# flash-card

nuxt.js + netlify + faunadbなサーバーレスWebアプリ

## How to Deploy
netlifyに簡単にデプロイできます。
### 事前準備
- GitHubアカウント
### 手順
#### 1. FaunaDBトークン取得
FaunaDBに登録してください。GitHubアカウントを使ってログインできます。  
キーを取得し、コピーしておきます。
#### 2. netlifyにデプロイ
以下のボタンをクリックします。
<!-- Markdown snippet -->
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/pb10005/flash-card)
#### 3. netlify identityを有効にする
#### 4. 環境変数の設定
netlifyのSettings > Build & Deployから、環境変数を設定します。  
キー：FAUNADB_SECRET  
値：<1で取得したキー>

## Build Setup

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn run dev

# build for production and launch server
$ yarn run build
$ yarn start

# generate static project
$ yarn run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).
#   f l a s h - c a r d  
 