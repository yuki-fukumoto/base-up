# base-up
 # 概要と目的
 本アプリケーションは、クリニックで働いている際に患者様から、個別にアドバイスしてもらえるようなサービスはないのかと相談を受け、作ってみようと思い立ちました。
 自分の運動や食事についてどれだけできているか成果の確認を出来ればいいと考えています。
 また、その内容についてセラピストがアドバイスできるようにしていきたいです。
 
 # 機能
https://gyazo.com/46759c56e4560a7a6423cc550af7729b

https://gyazo.com/c67d624411735a159b237d3089f82060

 # 今後の改善点
 現時点では潰れて表示されてしまうため、投稿画像のサイズに合わせて表示されるように変更していきます。
 画像を複数あげれるように改良していきます。
 # 本アプリケーションの問題点
 不特定多数のコメントが可能なため、悪質なコメントができてしまうため、ブロック機能が必要になってきます。
 文面での説明になるため動作方法や改善点がうまく伝わらない可能性があります。
 # 開発環境
フロントエンド(javascript, jQuery, HTML/CSS, HAML, Sass)
バックエンド(Ruby on Rails, 外部 API)
テスト(Rspec)
web サーバ(nginx, unicorn)
データベース(MySQL)

# DB図
<img width="632" alt="スクリーンショット 2020-11-10 8 49 49" src="https://user-images.githubusercontent.com/65587782/98610295-a34cfa00-2332-11eb-996f-2627de608269.png">

# デプロイ
デプロイ方法はAWSを使用し時期11月下旬から12月初旬を予定しています。
