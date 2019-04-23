# yokayoka-tpl

## 概要

（調整中）

[node.js](https://nodejs.org/) のインストールが必要です。  
未インストールの場合は LTS 版をインストールしてください。

試していませんが、コマンドラインから入れる場合は [こちら](https://qiita.com/akakuro43/items/600e7e4695588ab2958d) などが参考になるかと思います。

Clone したら、`npm install` で必要なモジュールをインストールしてください。

## スタート

`npm start`

## 初期構築時

HTML のテンプレートエンジンに EJS があります。  
プレーンな HTML で構築するか EJS を利用するか最初に決めてください。

|開発言語| ディレクトリ |処理        |
|------|------------|------------|
|HTML  |`/src/html/`|"watch/html"|
|EJS   |`/src/ejs/` |"watch/ejs" |

混乱を防ぐために不要な開発ディレクトリを削除し、関連処理についても package.json から削除してください。

※ Pug はこれから実装予定です。