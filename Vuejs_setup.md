#Vue.jsのセットアップ法
## 1. web系言語のローカル環境をインストールする
  僕が使っているのはMAMP(WindowsならXAMPP)
  [MAMP](https://www.mamp.info/en/)
  [XAMPP](https://www.apachefriends.org/jp/index.html)
## 2. コントロールパネル（MAMPならMAMPというアプリアイコンが、WindowsならXAMPPコントロールパネルが追加されている）で、サーバーをスタートさせる
webソースファイルは、インストールしたxamppフォルダ、MAMPのエイリアス内のhtdocs内に作成する。

##jsの他に、HTMLやCSSはもちろん、PHPやPerlも使える
Vue.jsはソースファイル内にCDNで設定してもいいし、htdocs内ならダウンロードしたminファイルを置いておいてもよい

VueMemo
インスタンス内の文字列に変数を加えたい場合、文字列をバッククオートで囲み、変数は＄をつけうｒ

`https://twitter.com/${{ screen_name }}`
