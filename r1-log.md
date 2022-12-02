# #100DaysOfCode Log - Round 1 - [yuria_cats]

The log of my #100DaysOfCode challenge. Started on [November 2, Wendsday, 2022].

## Log

### R1D1 
2022/11/2
23:45 - 0:45
yamanote_wasuremon_node のリファクタリング（DocStringの記載等）

#### 学び

1. JSDOCコメントについて、書き方を学んだ。[[参考](https://ics.media/entry/6789/)]
2. TSの型にはPascalCaseを使うべきらしい [[参考](https://typescript-jp.gitbook.io/deep-dive/styleguide#taipu)] 

　Pythonではどうなのだろうかと疑問に思ったので軽く調べたところ[PEP257](https://peps.python.org/pep-0257/#rationale)
 で定義されているらしい。
 
### R1D2
2022/11/3
19:15 - 20:40
21:00 - 21:23
1. railwayのJavascript部分をすすめた
2. railwayのReactを始めた。

スプレッド構文は初めて使ったがとても便利な構文だなということを感じた。
setTimeout関数はなるほどーとなったが原理的に説明できない部分も多くあるので説明できる様な理解にしていきたい。

### R1D3
2022/11/4
20:04 - 20:49
23:09 - 0:41
1.railwayのReactをすすめた。

感想：　基本的に前半、知っているがいい復習になる。時々手ぐせだけだとかけないもどかしさがまた、私の実力まだまだなんだなということを感じさせるいい教材。
初めて、Javascriptでメモリーエラーに出会した。なぜなのだろうか…

### R1D4
2022/11/5
21:45 - 22:45 
1. yamanote_wasuremon_nodeのAPIの定義をした。
22:45 - 25:18
2. react railwayをおわらせた

感想：そろそろAPIをうまく書くためのフレームワークなどの力を借りた方が良いように感じた。退避のためのDir作成、退避のためのDir移動（のみ）、フレームワークでInitするか？
フレームワークをまだ使うところまでできてない気もするので難しい。
Cron的なもの（定時実行）の方法も検討した方がいい。
### R1D5
2022/11/6
11:49 - 14:05
1. railwayをやっていた。

感想・学んだこと：　useEffectやDOMAPIの理解がまだまだ浅いのだなということを実感しました。Reactのドキュメントは日本語でもしっかり書いてあって親切なのがとてもありがたくも思えます。

### R1D6
2022/11/7
19:00 - 21:00

1. Expressの導入とハリボテサーバーの作成

### R1D7
2022/11/8
22:45 - 23:45

1. Reactの導入
2. json-serverの開発環境への導入

フロントエンドでテストを初めて書いてみようとしたがテストコードが回る状態にはなっていないのでRailwayを参考にしつつその状態まで持っていく。
[create-react-app
](https://create-react-app.dev/docs/running-tests/)にドキュメントが載っているので読む。

[json-serverの導入方法](https://qiita.com/roana0229/items/547437b6314fd283ddca)
json-serverは最初が必ず以下で始めないといけないという癖を見極められず少し苦戦をした

```
{
”エンドポイント”：{
さまざまな中の要素
}
}
```

### R1D8
2022/11/9
21:40 - 22:20
24:40 - 25:00

1. Reactで.envを使う方法を調べて.envからURLをとるような形にした。

### R1D9
2022/11/10
19:30 - 21:00
フロントエンドの整理とComponentJSのとりかた。
コードレビューをもらうための支度。

### R1D10
2022/11/11
22:55 - 23:55
テストライブラリーを導入しテストを記述した。
[rewire](https://github.com/jhnns/rewire/blob/master/lib/rewire.js)というライブラリーが便利そうなので利用

JestとReact-testing-libralyの違いの比較をしていきたい。記法に違いがあるなら興味深いので。

### R1D11
2022/11/12
21:00 - 22:40

atCoderをやった。
https://atcoder.jp/contests/abc277/submissions/36421744
https://atcoder.jp/contests/abc277/submissions/36433650

### R1D12
2022/11/13
14:55 - 15:20
23:40 - 00:41
やったこと
1. voltaのインストール。
https://docs.volta.sh/guide/getting-started
2. テストコードを書いた。

### R1D13
2022/11/14
[Doc] Classのイメージ図をDocに記載した

### R1D14
2022/11/15
22:15-23:05

Windowsのセットアップ
テストコードのテストロジックの修正

### R1D15
2022/11/17
20:35 - 21:35

API エンドポイントの作成とTS化

### R1D16
2022/11/18
21:00-22:00

C#でのパーサーの実装

### R1D17
2022/11/19
22:30 - 24:36
C#でパーサーの実装

### R1D18
2022/11/20
13:00 - 16:00
C#でパーサーの実装

### R1D19
2022/11/21
08:27 - 09:15
22:00 - 0:00
AWSのオペレーション
Dockerfileの作成


### R1D20
2022/11/22
22:00-23:00
AWSへのデプロイコードの設定等

### R1D21
2022/11/23
24:00 - 25:00
atcoder_helperのコードレビュー
yamanote_wasuremonno_nodeのデプロイコードの編集

### R1D22
2022/11/24
22:00 - 23:30
yamanote_wasuremono_frontにTailwindCSSの導入

### R1D23
2022/11/26
21:00-22:20
AtCoder に参加する。

### R1D24
2022/11/2７
18:00-19:00
yamanote_wasuremono_front の改修（ReactのRutor部分の検討）

### R1D25
2022/11/28
20:00-21:00
FinchのインストールとDevContainerで使えないかの試行

### R1D26
2022/11/29
20:00-21:00
RustでDiscordBot

### R1D27
2022/11/30
21:00-23:00
ECSなどのAmazonの設定

### R1D28
2022/1２/１
22:00-24:00
remarkの解説記事のための実装

### R1D29
2022/1２/２
20:00-23:00
remarkの解説記事のための実装
