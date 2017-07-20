# dojopaas

このプロジェクトはさくらインターネット様からご提供いただいた「さくらのクラウド」のアカウントを管理するためのプロジェクトです。

## サーバーがほしい方へ

以下のリンク先にあるCSVに対して必要事項を記入したプルリクエストをお願いします。

### 各項目の説明

* name: サーバーの名前。他のものと重複しないようにしてください。FQDNとかがいいかもですね。これはインスタンスの名前に使用されます。
* branch: 道場の名前。アルファベットの小文字でお願いします。これはインスタンスのタグにも使用されます。
* description: サーバーの用途など、後からわかりやすいものをお願いします。
* pubkey: SSHで接続するための公開鍵。秘密鍵とまちがえないようくれぐれもお願いします。

https://github.com/miya0001.keys

### SSHの接続方法

サーバーへの接続方法をご案内する方法が数日以内にご連絡します。

### サーバーの仕様

OS: Ubuntu 16.04
CPU: 1コア
メモリ: 1GB
HDD: 20GB
