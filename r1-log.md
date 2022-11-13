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
