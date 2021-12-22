# vue-express-development
このrepositoryはフロントをvue,バックエンドをexpressを使用した環境構築についてmemoしています。
今回はVue-CLI-Plugin-Expressを使用して環境構築を行う。

■環境構築
・vueの環境をvue create で作成する。

・作成後、作成したプロジェクトまで移動し、vue add expressのコマンドを入力する
 質問が2回されるが、基本yesと質問通り回答する。

・上記の方法で環境構築は完了するが、expressのコードはコメントアウトしてあるので
　コメントを解除し使用する。

■ポイント
・環境を立ち上げる際はexpressから先に立ち上げ、その後にvueを立ち上げる。
　この順番で立ち上げないとそれぞれの通信の疎通がうまくいかない。

■参考サイト
https://qiita.com/corestate55/items/81ba50cf33c78b7119fd#vue-cli-plugin-express-%E3%81%A7-api-server-%E3%82%92%E4%BD%9C%E3%82%8B
https://neos21.net/blog/2020/07/06-01.html
https://code-database.com/knowledges/111
