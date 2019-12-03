# URL
https://www.youtube.com/watch?v=FS5NYN_n7_k

# Contents
## Japanese
predictive prefetchingを使用したユーザー体験の改善方法について伝えます。

駅の中を想像してみて下さい。
お気に入りのWikipediaAppを開いて、チーズについてもっと知りたいと
決めました。味がどのようなものか学んでいたところ、電車が到着しました。
電車に乗り、出発します。席に座り、さっきの続きをします。
しかし、貧相なシグナルを得ます(シグナルが不十分。電波が悪い)。
リンクを狂ったようにクリックしても、何も動きません。
こういった際、とてもストレスがたまります。
激怒クリックの体験を少なくするために、prefetchingの使い方を学びましょう。

まずはじめにPrefetchingとはなにか説明します。
チーズの記事を読む前のユーザーを想像しましょう。
バックグラウンドでは、コンテンツのダウンロードとキャッシュを
行います。そのコンテンツは、次必要な他のページも関連しています。
そのため、ナビゲーションを開始すると、すぐに体験できます。
異なるprefetching戦略があります。
例えば、そのアプリ内で
・すべてのassetsをprefetchする
・目に見えるリンクに関連したassetsのみprefetchする
・カーソルがリンク上に来たときにはじめてprefetchする
・予測して(predictive)prefetchingする

Predictive prefetchingは、技術で、データ分析や機械学習から
データドリブンアプローチを提供するメソッドを使用します。
Predictive prefetchingの代わりに、
予測学習を提供することでアプリを強化する機械学習モデルに
フィードできるアプリ使用レポートが必要です。
 
 Microsoft's Office 365は、angularでpredictive prefetchingをしている。
 遅延ロードコンポーネントの応答性を改善するため。
 YouTubeは、コンテンツを予測的にprefetchしてます。瞬間的なユーザー体験のため。
 しかし、MicrosoftやGoogleのような技術を利用する必要はない。
 
 Guess.jsはライブラリで、predictive prefetchingをサポートしている。
 有名なフレームワークを使用しているアプリなら。今日こそそれを利用することができます。
１つのページや次に必要な都道府県(???, ページかな)から可能な限りナビゲーションを追跡します。
現在、Naveedというpredictive prefetchingをguess.jsで彼のアプリ上で紹介している人物の
ストーリーを教えます。
Naveedは、10000(何万もの)のユーザがPakistanでジョブを発見するための有名なwebアプリを構築しています。
ぞれはAngularRouterとCLIを使用したAngularAppです。
3つのprefetching戦略の違いをNaveedのWebサイトより比較してみましょう。

すべてのmodulesをprefetchingした場合、2.56MBのデータでした。
一人のユーザがホームページにアクセスした場合。
目に見えるリンクのみprefetchingした場合、1.22MBのデータでした。
Guess.jsを使用した場合、0.18MBのデータでした。
そのため、何万ものユーザがNaveedのwebサイトを毎日訪れていると、
GBのトラフィックを節約しています。
Guess.jsのprefetchingは、90%を超える精度です。
マウスオーバーprefetchingと組み合わせることで、彼のWebサイトのユーザー
すべてに瞬間的体験を提供できます。

さらに、Guess.jsはprefetchアルゴリズムをユーザの接続速度に適合させます。
低速なネットワーク上のユーザよりも、高速なネットワーク上のユーザに対して
積極的にprefetchingを実行している。
Guess.jsは、使用される可能性に応じて、個々のJavaScriptチャンクをprefetchします。
それは、全てのチャンクを容量を計算し、必要なビルド時間を求め、payloadを最小限に
削減することができます。最後にメインスレッドをぶろっくすることはありません。
ブラウザがアイドル状態の場合のみprefetchを実行するためです。
今日では、guest.js with angular, next.js, gatsby, next.jsが使えます。
今日からの最も大切なポイントは、predictive prefetchingはページナビゲーション
の速度を改善し、ユーザー体験をよくすることです。それをするために、ユーザ満足度を
増加させ、塩茹するデータを減らします。angularやreact,vueを使っているなら、
今日からでもguess.jsが使えます。

## English
