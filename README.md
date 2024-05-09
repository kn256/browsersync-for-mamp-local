# browsersync-for-mamp-local

## 概要
[XAMPP](https://www.apachefriends.org/jp/index.html)、[MAMP](https://www.mamp.info/)、[Local](https://localwp.com/)などで開発を行う際、[Browsersync](https://browsersync.io/)を使えるようにする為のパッケージです。

## 実行手順
1. 本リポジトリの中身をルートフォルダに置きます。(MAMPの例 → C:\MAMP\htdocs)
2. bs-config.js内のfilesとproxyの部分を適宜変更します。
2. `npm i`でパッケージをインストールします。
3. 各開発ツールを立ち上げている状態で、`npm run start`コマンドを打ちます。

## 備考
- `npm run start`ターミナルに表示されるLocalとExternalのアドレスはどちらも使用できます。
- Externalの方は同じローカルネットワーク接続してあれば、スマホから閲覧することもできます。(セキュリティソフトがブロックして使えないことがあるので、その場合、セキュリティソフトの設定を見直してください。[Browser-syncでExternalのアドレスにスマホからアクセスできない場合の対策](https://keikenchi.com/browser-sync-can-not-access-externals-address))