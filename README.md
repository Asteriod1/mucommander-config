2画面ファイラ「muCommander」の設定
* http://www.mucommander.com

## Getting Started
1. muCommander をインストール
1. muCommander を起動して、いったん閉じる
1. 下記コマンドを実行する

```
cd ~/Library/Preferences/muCommander
git init
git add .
git commit -m "first commit"
git remote add origin git@github.com:inouetakuya/mucommander-config.git
git pull -f origin msater:master
```

## Mountain Lion にインストールできないとき
1. 環境設定 > セキュリティとプライバシー
1. ダウンロードしたアプリケーションの実行許可を「すべてのアプリケーションを許可」にしてから muCommander を起動する
1. いったん起動した後は、上記設定を元に戻して問題ない
1. 公式の案内には、ダウンロードする前に設定変更してねって書いているけど、ダウンロード後でもイケた

* http://mucommander.tumblr.com/post/28828080869/mac-os-x-mountain-lion-now-requires-all

