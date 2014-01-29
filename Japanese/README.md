#Front-end Job Interview Questions
#フロントエンドの就職試験の問題集

@version 2.0.0

このレポジトリには、候補者の能力を測ることができる、フロントエンドに関する問題がたくさんの存在します。実力を計るために、1人の候補者にすべての問題を問う必要はありません（数時間かかってしまいます）。いくつかの問題を選んで候補者に質問することで、候補者のスキルを測ることができます。

面接に臨む前に、[Rebecca Murphey](http://rmurphey.com/)の [Baseline For Front-End Developers（英語）](http://rmurphey.com/blog/2012/04/12/a-baseline-for-front-end-developers/)を読むと良いでしょう。

**Note:** ここに示した問題の多くは、Yes/Noでは答えられないオープンクエスチョンです。そのため、回答そのものから発展させて問題について議論することで、候補者のポテンシャルをより深く知ることができるでしょう。

####Contributors

問題の多くは、[Paul Irish](http://paulirish.com) ([@paul_irish](http://twitter.com/paul_irish))によって作成された[oksoclap](http://oksoclap.com/) のスレッドから作成されました。Contributerは、以下の方々です。

* [@bentruyman](http://twitter.com/bentruyman) - http://bentruyman.com
* [@cowboy](http://twitter.com/cowboy) - http://benalman.com
* [@ajpiano](http://ajpiano) - http://ajpiano.com
* [@SlexAxton](http://twitter.com/slexaxton) - http://alexsexton.com
* [@boazsender](http://twitter.com/boazsender) - http://boazsender.com
* [@miketaylr](http://twitter.com/miketaylr) - http://miketaylr.com
* [@vladikoff](http://twitter.com/vladikoff) - http://vladfilippov.com
* [@gf3](http://twitter.com/gf3) - http://gf3.ca
* [@jon_neal](http://twitter.com/jon_neal) - http://twitter.com/jon_neal
* [@wookiehangover](http://twitter.com/wookiehangover) - http://wookiehangover.com
* [@darcy_clarke](http://twitter.com/darcy) - http://darcyclarke.me
* [@iansym](http://twitter.com)

また、翻訳は以下の人が行いました。
* [@yoheiMune](http://twitter.com/yoheiMune) - http://yoheim.net


### 問題（全般）

* 昨日（または今週）、あなたは何を学びましたか？
* コーディングにおいて、熱中することや興味を持つことは何ですか？
* お気に入りの開発環境について教えて下さい。（OS, エディタ, ブラウザ, ツール, 他）
* あるWebページを作る場合に、どのような作業手順（workflow）で取り組むか説明できますか？
* プレグレッシブ・エンハンスメント（progressive enhancement）とグレースフル・デグレデーション（graceful degradation）の違いを説明できますか？
  * ボーナスポイント：それぞれの特徴を使って違いを説明できた場合
* "セマンティックHTML（Semantic HTML）"の意味を説明してください。
* Webサイトのアセットやリソースをあなたはどのように最適化しますか？
  * 以下のような解決策が挙がるかを確認してください。
    * ファイルの結合
    * ファイルのミニファイ
    * CDNの利用
    * キャッシュ
    * 他
* 複数のドメインからアセットを提供することは、なぜ良いのでしょうか？
  * ブラウザが1つのドメインから一度にダウンロードするリソース数は、いくつでしょうか？
* ページ読み込みを減らす方法を3つ挙げてください(体感時間、または実際のロード時間について)
* あるプロジェクトにアサインされた時に、彼らはタブとスペースの両方を使っていました。あなたならどうしますか？
  * EditorConfig（ http://editorconfig.org ）などの何らかのプロジェクト共通設定を提案するか？
  * 現状に従うか？
  * `issue :retab! command`
* シンプルなスライドショーを行うページを実装してください。
  * ボーナスポイント：JSを使わなかった場合
* コードのパフォーマンスをテストするために、どのようなツールを使いますか？
  * Profiler, JSPerf, Dromaeo
* 今年、何か1つ技術を極めるとしたら、それは何ですか？
* 標準化や標準化団体の重要性について説明してください。
* FOUCとは何ですか？どのようにFOUCを回避しますか？

### 問題（HTML編）

* `doctype`とは何ですか？
* 標準モードと互換モードの違いは何ですか？
* What are the limitations when serving XHTML pages?
* XHTMLページを実装するにあたり、どのような制約事項がありますか？
  * `application/xhtml+xml`のページを実装する場合に、どのような問題がありますか？
* 1つのページで複数言語をサポートする場合、あなたならどのように実装しますか？
  * 複数言語をサポートするサイトのデザインや実装をする上で、どのようなことに注意を払いますか？
* `data-`属性は、どのようなことに利用すると良いですか？
* Consider HTML5 as an open web platform. What are the building blocks of HTML5?
* HTML5をオープンWebプラットフォームと考えた場合に、HTML5の構成要素はどのようなものがありますか？
* cookie, sessionStorage, localStorageの違いを説明してください。

### 問題（JS編）

* イベントの委譲（event delegation）について説明してください。
* JavaScriptにおいて`this`がどのように機能するかを説明してください。
* プロトタイプ継承がどのように機能するか説明してください。
* どのようにJavaScriptコードをテストしますか？
* AMD vs. CommonJS？
* 連想配列とは何ですか？
* `undefined`変数と`undeclared`変数とは何ですか？
* クロージャーとは何ですか？どのように使いますか？また、なぜクロージャーを使いますか？
  * あなたのお気に入り書き方には、それらが日常的に使われていますか？（即時関数に適用できる場合に限ります）
* 無名関数の典型的な使い方はどのようなものですか？
* "JavaScriptモジュールパターン（JavaScript module pattern）"について説明してください。またそれを利用した事例を教えてください。
  * ボーナスポイント：名前空間を汚染しない点に言及した場合
  * もしあなたのモジュールが名前空間を必要としないとしたら、、、
* どのようにコードを構成しますか？（モジュールパターン、レガシーパターン？）
* ホストオブジェクト（host objects）とネイティブオブジェクト（native objects）の違いは何ですか？
* 次の違いを説明して下さい。
```javascript
function Person(){} var person = Person() var person = new Person()
```
* `.call`と`.apply`の違いを説明して下さい。
* `Function.prototype.bind`について説明してください。
* いつコードの最適化を行いますか？
* JavaScriptにおいて、どのように継承が機能するかを説明できますか？
* `document.write()`をどのような時に使いますか？
  * 広告を生成する多くの機能は、非難を受けつつも、依然として`document.write()`を利用しています。
* Feature Detection, Feature Inference, UA Detectionの違いを説明してください。
* AJAXについてできるだけ詳しく説明してください。
* JSONPがどのように機能するかについて説明してください。（また、AJAXとどのように違うのかを説明してください）
* JavaScriptテンプレートを使ったことがありますか？
  * もし使ったことがある場合には、どのようなライブラリを使いましたか？（Mustache.js, Handlebars, など）
* varの巻き上げ（hoisting）について説明してください。
 * イベント伝播（Event Bubbling）について説明してください。
* "attribute"と"property"の違いは何ですか？
* 組み込みJavaScriptオブジェクト（built-in objects）を拡張することは、なぜ良くないことなのでしょうか？
* プラグインによる拡張は、なぜ良いことなのでしょうか？
* document loadイベントと、document readyイベントの違いは何ですか？
* `==`と`===`の違いは何ですか？
* ブラウザで表示されているURLからクエリパラメータを取得する場合に、あなたならどのように実装しますか？
* Explain the same-origin policy with regards to JavaScript.
* JavaScriptの観点から、同一生成元ポリシー（Same-Origin Policy）を説明してください。
* JavaScriptにおける継承を用いたデザインパターンを説明してください。
* 次が動作するように実装してください。
```javascript
[1,2,3,4,5].duplicate(); // [1,2,3,4,5,1,2,3,4,5]
```
* JavaScriptにおけるメモ化（同じ計算を何度も行うことを避ける方法）を説明してください。
* なぜ三項演算子と呼ばれるのでしょうか？また、三項が意味することは何ですか？
* 関数の可変引数とは何ですか？
* `"use strict";`とは何ですか？これを使うことでのメリット・デメリットは何ですか？

### JS-Code Examples:
### 問題（JSコード）

```javascript
~~3.14
```
問題：上記のコードを実行して得られる値は何ですか？
**答え：3**

```javascript
"i'm a lasagna hog".split("").reverse().join("");
```
問題：上記のコードを実行して得られる値は何ですか？
**答え："goh angasal a m'i"**

```javascript
( window.foo || ( window.foo = "bar" ) );
```
問題：window.fooの値は何ですか？
**答え："bar"**
（window.fooの判定がfalseの場合のみbarが値に設定され、それ以外の場合にはwindow.fooは変化しません）

```javascript
var foo = "Hello"; (function() { var bar = " World"; alert(foo + bar); })(); alert(foo + bar);
```
問題：2つのalertからの結果はどのようになりますか？
**答え："Hello World"と表示され、続いてReferenceError: bar is not definedと表示される。**

```javascript
var foo = [];
foo.push(1);
foo.push(2);
```
問題：foo.lengthの値は何ですか？
**答え：`2`**

```javascript
var foo = {};
foo.bar = 'hello';
```
問題：foo.lengthの値は何ですか？
**答え：`undefined`**

### 問題（jQuery）

* メソッドチェーン（chaining）について説明して下さい。
* デファード（deferreds）について説明してください。
* あなたが実装できるjQuery特有の最適化をいくつか教えてください。
* `.end()`はどのように機能しますか？
* ☆どのようにイベントハンドラーに設定する名前を決めますか？なぜその名前を使うのですか？
* ☆あなたが利用できるjQueryの機能を4つ上げてください。
  * Selector (string), HTML (string), Callback (function), HTMLElement, object, array, element array, jQuery Object, など.
* キュー（queue）とは何ですか？
* 次の違いを説明してください。`.get()`, `[]`, and `.eq()`?
* 次の違いを説明してください。`.bind()`, `.live()`, and `.delegate()`
* 次の違いを説明してください。`$` and `$.fn`? Or just what is `$.fn`
* 次のセレクターを最適化してください。
```javascript
$(".foo div#bar:eq(0)")
```
* 'delegate()'と'live()'の違いは何ですか？


### 問題（CSS）

* リセットCSSファイルがどのように機能するか、なぜ便利なのかについて説明して下さい。
* フロート（float）について説明してください。また、それがどのように機能するかを説明してください。
* フロートをクリアするにはどのようは方法がありますか。また、どのように使い分けますか？
* CSSスプライトについて説明してください。また、サイトを構築する時に、CSSスプライトをどのように実装しますか？
* お気に入りの画像置換（Image Replacement）テクニックをいくつか教えてください。それらはいつ使いますか？
* CSS property hacks, conditionally included .css files, or... something else?
* CSSファイルに記載するCSSハックがありますが、他にはどのようなハックがありますか？
* 機能制限されたブラウザーに対して、どのようにページを提供しますか？
  * どのようなテクニックや手順を使いますか？
* コンテンツを隠す方法はどのようなものがありますか？また、screenの場合のみそれを適用するにはどうしますか？
* Have you ever used a grid system, and if so, what do you prefer?
* グリッドシステムを使ったことがありますか？もしある場合、どの実装技術をあなたは好みますか？
* メディアクエリやモバイル専用のレイアウト（やCSS）を使ったことはありますか？
* SVGやそれに関連する技術を使ったことはありますか？
* 印刷用にWebページを最適化するにはどうしますか？
* What are some of the "gotchas" for writing efficient CSS?
* ☆効率の良いCSSを書くために、「わかった！」という体験がありましたら教えてください。
* CSSプリプロセッサを使うメリット・デメリットは何ですか？（SASS, Compass, Stylus, LESS）
  * 今までに使ってきたCSSプリプロセッサの好きな点、嫌いな点を教えてください。
* 標準実装されていないフォントを使う場合に、どのようにWebデザインカンプを実装しますか？
  * Webフォント（Google Webfonts, Typekitなど）
* あるCSSセレクタがどの要素に合致するかについて、ブラウザが決める方法を説明してください。

### 問題（番外編）

* 今まで実装したコードで、最も良いと思ったコードは何ですか？また、何に一番誇りを持ちますか？
* あなたの使っているディベロッパーツールで、好んでいる点はどこですか？
* 特に興味のあるプロジェクトはありますか？それはどのような種類のものですか？
* Internet Explorerの機能のうち、好きな機能は何ですか？
