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
* If you jumped on a project and they used tabs and you used spaces, what would you do?
* あるプロジェクトにアサインされた時に、彼らはタブとスペースの両方を使っていました。あなたならどうしますか？
  * Suggest the project utilize something like EditorConfig (http://editorconfig.org)
  * EditorConfig (http://editorconfig.org）などの何らかのプロジェクト共通設定を提案するか？
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
* Explain how JSONP works (and how it's not really AJAX)
* JSONPがどのように機能するかについて説明してください。（また、AJAXが機能しない理由を説明してください）
* Have you ever used JavaScript templating?
* JavaScriptテンプレートを使ったことがありますか？
  * If so, what libraries have you used? (Mustache.js, Handlebars etc.)
  * もし使ったことがある場合には、どんなライブラリを使いましたか？（Mustache.js, Handlebars, 他）
* Explain "hoisting".
* varの巻き上げ（hoisting）について説明してください。
* Describe event bubbling.
 * イベント伝播（event bubbling）について説明してください。
* What's the difference between an "attribute" and a "property"?
* "attribute"と"property"の違いは何ですか？
* Why is extending built in JavaScript objects not a good idea?
* なぜJavaScriptオブジェクトを拡張することは、良くないことなのでしょうか？
* Why is extending built ins a good idea?
* なぜビルドインの拡張は良いことなのでしょうか？
* Difference between document load event and document ready event?
* document loadイベントと、document readyイベントの違いは何ですか？
* What is the difference between `==` and `===`?
* `==`と`===`の違いは何ですか？
* Explain how you would get a query string parameter from the browser window's URL.
* ブラウザで表示されているURLからクエリパラメータを取得する場合に、どのように実装しますか？
* Explain the same-origin policy with regards to JavaScript.
* JavaScriptの観点から、Same-Origin Policyを説明してください。
* Describe inheritance patterns in JavaScript.
* JavaScriptにおける継承パターンを説明してください。
* Make this work:
* 次が動作するように実装してください。
```javascript
[1,2,3,4,5].duplicate(); // [1,2,3,4,5,1,2,3,4,5]
```
* Describe a strategy for memoization (avoiding calculation repetition) in JavaScript.
* JavaScriptにおけるメモ化のパターン（計算を何度も行うことを避ける）を説明してください。
* Why is it called a Ternary expression, what does the word "Ternary" indicate?
* なぜ三項演算子と呼ばれるのでしょうか？また、三項が意味することは何でしょうか？
* What is the arity of a function?
* 関数の可変引数とは何ですか？
* What is `"use strict";`? what are the advantages and disadvantages to using it?
* `"use strict";`とは何ですか？これを使うことでのメリット・デメリットは何ですか？

### JS-Code Examples:
### 問題（JSコード）

```javascript
~~3.14
```
Question: What value is returned from the above statement?
**Answer: 3**
問題：上記のコードを実行して得られる値は何ですか？
**答え：3**

```javascript
"i'm a lasagna hog".split("").reverse().join("");
```
Question: What value is returned from the above statement?
**Answer: "goh angasal a m'i"**
問題：上記のコードを実行して得られる値は何ですか？
**答え："goh angasal a m'i"**

```javascript
( window.foo || ( window.foo = "bar" ) );
```
Question: What is the value of window.foo?
**Answer: "bar"**
only if window.foo was falsey otherwise it will retain its value.
問題：window.fooの値は何ですか？
**答え："bar"**
window.fooの判定がfalseの場合のみ、barが設定され、其れ以外はwindow.fooが既に保持している値がそのまま残ります。

```javascript
var foo = "Hello"; (function() { var bar = " World"; alert(foo + bar); })(); alert(foo + bar);
```
Question: What is the outcome of the two alerts above?
**Answer: "Hello World" & ReferenceError: bar is not defined**
問題：2つのalertからの結果はどのようになりますか？
**答え："Hello World"と表示され、続いてReferenceError: bar is not definedと表示される。**

```javascript
var foo = [];
foo.push(1);
foo.push(2);
```
Question: What is the value of foo.length?
**Answer: `2`
問題：foo.lengthの値は？
**答え：`2`**

```javascript
var foo = {};
foo.bar = 'hello';
```
Question: What is the value of foo.length?
**Answer: `undefined`
問題：foo.lengthの値は？
**答え：`undefined`**

### 問題（jQuery）

* Explain "chaining".
* メソッドチェーン（chaining）について説明して下さい。
* Explain "deferreds".
* ディファード（deferreds）について説明してください。
* What are some jQuery specific optimizations you can implement?
* あなたが実装出来るjQuery特有の最適化をいくつか教えてください。
* What does `.end()` do?
* `.end()`はどのように機能しますか？
* How, and why, would you namespace a bound event handler?
* ☆どのように、そしてどのような根拠で、イベントハンドラーのネームスペースを設定しますか？
* Name 4 different values you can pass to the jQuery method.
* ☆あなたが利用出来るjQueryの機能を4つ上げてください。
  * Selector (string), HTML (string), Callback (function), HTMLElement, object, array, element array, jQuery Object etc.
  * Selector (string), HTML (string), Callback (function), HTMLElement, object, array, element array, jQuery Object 他.
* What is the effects (or fx) queue?
* エフェクトキュー（effects queue）や関数キュー（fx queue）は何ですか？
* What is the difference between `.get()`, `[]`, and `.eq()`?
* 次の違いを説明してください。`.get()`, `[]`, and `.eq()`?
* What is the difference between `.bind()`, `.live()`, and `.delegate()`?
* 次の違いを説明してください。`.bind()`, `.live()`, and `.delegate()`
* What is the difference between `$` and `$.fn`? Or just what is `$.fn`.
* 次の違いを説明してください。`$` and `$.fn`? Or just what is `$.fn`
* Optimize this selector:
* 次のセレクターを最適化してください。
```javascript
$(".foo div#bar:eq(0)")
```
* Difference between 'delegate()' and 'live()'?
* 'delegate()'と'live()'の違いは何ですか？


### 問題（CSS）

* Describe what a "reset" CSS file does and how it's useful.
* リセットCSSファイルがどのように機能するか、なぜ便利なのかについて説明して下さい。
* Describe Floats and how they work.
* フロート（float）がどのように機能するかを説明してください。
* What are the various clearing techniques and which is appropriate for what context?
* フロートをクリアする方法をいくつか説明してください。またどのように使い分けるべきか説明してください。
* Explain CSS sprites, and how you would implement them on a page or site.
* CSSスプライトについて説明してください。またページやサイトを構築する上で、CSSスプライトをどのように実装しますか？
* What are your favourite image replacement techniques and which do you use when?
* お気に入りの画像置換（image replacement）テクニックをいくつか教えてください。それらはいつ使いますか？
* CSS property hacks, conditionally included .css files, or... something else?
* ☆.cssファイルに条件付きでCSSプロパティのハックを含むことがありますが、他にはどのようなハックがありますか？
* How do you serve your pages for feature-constrained browsers?
* 機能制限されたブラウザーに対して、どのようにページを提供しますか？
  * What techniques/processes do you use?
  * どのようなテクニックや手順を使いますか？
* What are the different ways to visually hide content (and make it available only for screen readers)?
* コンテンツを隠す方法はどのようなものがありますか（そして、screenの場合のみそれを適用するにはどうしますか）？
* Have you ever used a grid system, and if so, what do you prefer?
* グリッドデザインを使ったことがありますか？もしある場合、あなたはどのような技術を使って実装しますか？
* Have you used or implemented media queries or mobile specific layouts/CSS?
* メディアクエリやモバイル専用のレイアウト（やCSS）を使ったことはありますか？
* Any familiarity with styling SVG?
* SVGや其れに関する技術を使ったことはありますか？
* How do you optimize your webpages for print?
* 印刷用にWebページを最適化するにはどうしますか？
* What are some of the "gotchas" for writing efficient CSS?
* ☆効率の良いCSSを書くために、いくつかの分かった！体験を教えてください。
* What are the advantages/disadvantages of using CSS preprocessors? (SASS, Compass, Stylus, LESS)
* CSSプリプロセッサを使うメリット・デメリットは何ですか？（SASS, Compass, Stylus, LESS）
  * If so, describe what you like and dislike about the CSS preprocessors you have used.
  * 今までに使ってきたCSSプリプロセッサの好む点、嫌う点を教えてください。
* How would you implement a web design comp that uses non-standard fonts?
* 標準実装されていないフォントを使う場合に、どのようにWebデザインカンプを実装しますか？
  * Webfonts (font services like: Google Webfonts, Typekit etc.)
  * Webフォント（Google Webfonts, Typekitなど）
* Explain how a browser determines what elements match a CSS selector?
* ブラウザが、どの要素がCSSセレクタにマッチするかを決める方法について説明してください。

### Optional fun Questions:
### 問題（番外編）

* What's the coolest thing you've ever coded, what are you most proud of?
* 最もカッコいいと思ったコードは何ですか？最も誇りを持つことは何ですか？
* What are your favorite parts about the developer tools you use?
* あなたの使っているディベロッパーツールで、好んでいる点はどこですか？
* Do you have any pet projects? What kind?
* 特に興味のあるプロジェクトはありますか？どのような種類のものですか？
* What's your favorite feature of Internet Explorer?
* Internet Explorerの機能のうち、好きな機能は何ですか？
