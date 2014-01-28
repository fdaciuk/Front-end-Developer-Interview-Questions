#Front-end Job Interview Questions

@version 2.0.0

This repo contains a number of front-end interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

このレポジトリには、たくさんのフロントエンドに関する問題を集めており、その問題を使って腕試しすることができます。実力を計るためにすべての問題を行う必要はなく、ここに示すリストからいくつか選定して使ってください。

[Rebecca Murphey](http://rmurphey.com/)'s [Baseline For Front-End Developers](http://rmurphey.com/blog/2012/04/12/a-baseline-for-front-end-developers/) is also a great resource to read up on before you head into an interview.

ここに示した問題に答える前に、[Rebecca Murphey](http://rmurphey.com/)'s [Baseline For Front-End Developers（英語）](http://rmurphey.com/blog/2012/04/12/a-baseline-for-front-end-developers/)で学習すると良いでしょう。

**Note:** Keep in mind that many of these questions are open ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

**Note:** ここに示した問題の多くは、Yes/Noでは答えられないオープンクエスチョンです。そのため、回答そのものから発展させて、この問題について議論することで、より実力を測ることができるでしょう。

####Original Contributors

The majority of the questions were plucked from an [oksoclap](http://oksoclap.com/) thread created originally by [Paul Irish](http://paulirish.com) ([@paul_irish](http://twitter.com/paul_irish)) and contributed to by the following individuals:

問題の多くは、[Paul Irish](http://paulirish.com) ([@paul_irish](http://twitter.com/paul_irish))によって作成された[oksoclap](http://oksoclap.com/) のスレッドから作成されました。以下の人々がContributerです。

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

### General Questions:

### 問題（全般）

* What did you learn yesterday/this week?
* 昨日/この週にあなたは何を学びましたか？
* What excites or interests you about coding?
* コーディングにおいて、何に興奮しましたか？また何に興味を持ちましたか？
* Talk about your preferred development environment. (OS, Editor, Browsers, Tools etc.)
* お気に入りの開発環境について語ってください（OS, エディタ, ブラウザ, ツール, 他）
* Can you describe your workflow when you create a web page?
* Webページを作る際の、あなたの作業の流れ（workflow）を説明してください。
* Can you describe the difference between progressive enhancement and graceful degradation?
* プレグレッシブ・エンハンスメント（progressive enhancement）とグレースフル・デグレデーション（graceful degradation）の違いを説明できますか？
  * Bonus points for describing feature detection
  * 違いについて特徴を説明出来た場合には、ボーナスポイント
* Explain what "Semantic HTML" means.
* "セマンティックHTML（Semantic HTML）"の意味を説明してください。
* How would you optimize a websites assets/resources?
* Webサイトのアセットやリソースをあなたはどのように最適化しますか？
  * Looking for a number of solutions which can include:
  * 以下のような解決策が挙がるかを確認してください。
    * File concatenation
    * ファイルの結合
    * File minification
    * ファイルのミニファイ
    * CDN Hosted
    * CDNの利用
    * Caching
    * キャッシュ
    * etc.
    * 他
* Why is it better to serve site assets from multiple domains?
* なぜ複数のドメインからアセットを提供することが良いのでしょうか？
  * How many resources will a browser download from a given domain at a time?
  * 1つのドメインから一度にブラウザーがダウンロード可能なリソースの数はいくつでしょうか？
* Name 3 ways to decrease page load. (perceived or actual load time)
* ページロードを減らす方法を3つ上げてください(体感時間、または実際のロード時間について)
* If you jumped on a project and they used tabs and you used spaces, what would you do?
* あるプロジェクトにアサインされた時に、彼らはタブとスペースを使っていました。あなたならどうしますか？
  * Suggest the project utilize something like EditorConfig (http://editorconfig.org)
  * EditorConfig (http://editorconfig.org)などの何らかのプロジェクト共通のことを提案するか？
  * Conform to the conventions (stay consistent)
  * しきたりに従うか（現状維持）？
  * `issue :retab! command`
* Write a simple slideshow page
* シンプルなスライドショーを行うページを書いてください。
  * Bonus points if it does not use JS.
  * ボーナスポイント：JSを使わなかった場合
* What tools do you use to test your code's performance?
* コードのパフォーマンステストにはどのようなツールを使いますか？
  * Profiler, JSPerf, Dromaeo
  * Profiler, JSPerf, Dromaeo
* If you could master one technology this year, what would it be?
* 今年なにか1つ技術を極めるとしたら、それは何ですか？
* Explain the importance of standards and standards bodies.
* 標準化や標準化団体の重要性について説明してください。
* What is FOUC? How do you avoid FOUC?
* FOUCとは何ですか？どのようにFOUCを回避しますか？

### HTML-Specific Questions:
### 問題（HTML編）

* What's a `doctype` do?
* `doctype`とは何ですか？
* What's the difference between standards mode and quirks mode?
* スタンダードモードと互換モードの違いは何ですか？
* What are the limitations when serving XHTML pages?
* XHTMLページを提供するにあたり、制限事項は何ですか？
  * Are there any problems with serving pages as `application/xhtml+xml`?
  * `application/xhtml+xml`のページを実装する場合に、どのような問題がありますか？
* How do you serve a page with content in multiple languages?
* 複数の言語のコンテンツを含むページを、あなたならどのように実装しますか？
  * What kind of things must you be wary of when design or developing for multilingual sites?
  * 他言語サイトのデザインや構築をする上で、どのようなことに注意を払いますか？
* What are `data-` attributes good for?
* `data-`は何に効果的なのでしょうか？
* Consider HTML5 as an open web platform. What are the building blocks of HTML5?
* ★HTML5をオープンWebプラットフォームと考えた場合に、HTML5のブロック要素の構築とはどのようなものですか？
* Describe the difference between cookies, sessionStorage and localStorage.
* cookie, sessionStorage, localStorageの違いを説明してください。

### JS-Specific Questions
### 問題（JS編）

* Explain event delegation
* Explain how `this` works in JavaScript
* Explain how prototypal inheritance works
* How do you go about testing your JavaScript?
* AMD vs. CommonJS?
* What's a hashtable?
* What are `undefined` and `undeclared` variables?
* What is a closure, and how/why would you use one?
  * Your favorite pattern used to create them? argyle (Only applicable to IIFEs)
* What's a typical use case for anonymous functions?
* Explain the "JavaScript module pattern" and when you'd use it.
  * Bonus points for mentioning clean namespacing.
  * What if your modules are namespace-less?
* How do you organize your code? (module pattern, classical inheritance?)
* What's the difference between host objects and native objects?
* Difference between:
```javascript
function Person(){} var person = Person() var person = new Person()
```
* What's the difference between `.call` and `.apply`?
* explain `Function.prototype.bind`?
* When do you optimize your code?
* Can you explain how inheritance works in JavaScript?
* When would you use `document.write()`?
  * Most generated ads still utilize `document.write()` although its use is frowned upon
* What's the difference between feature detection, feature inference, and using the UA string
* Explain AJAX in as much detail as possible
* Explain how JSONP works (and how it's not really AJAX)
* Have you ever used JavaScript templating?
  * If so, what libraries have you used? (Mustache.js, Handlebars etc.)
* Explain "hoisting".
* Describe event bubbling.
* What's the difference between an "attribute" and a "property"?
* Why is extending built in JavaScript objects not a good idea?
* Why is extending built ins a good idea?
* Difference between document load event and document ready event?
* What is the difference between `==` and `===`?
* Explain how you would get a query string parameter from the browser window's URL.
* Explain the same-origin policy with regards to JavaScript.
* Describe inheritance patterns in JavaScript.
* Make this work:
```javascript
[1,2,3,4,5].duplicate(); // [1,2,3,4,5,1,2,3,4,5]
```
* Describe a strategy for memoization (avoiding calculation repetition) in JavaScript.
* Why is it called a Ternary expression, what does the word "Ternary" indicate?
* What is the arity of a function?
* What is `"use strict";`? what are the advantages and disadvantages to using it?

### JS-Code Examples:

```javascript
~~3.14
```
Question: What value is returned from the above statement?
**Answer: 3**

```javascript
"i'm a lasagna hog".split("").reverse().join("");
```
Question: What value is returned from the above statement?
**Answer: "goh angasal a m'i"**

```javascript
( window.foo || ( window.foo = "bar" ) );
```
Question: What is the value of window.foo?
**Answer: "bar"**
only if window.foo was falsey otherwise it will retain its value.

```javascript
var foo = "Hello"; (function() { var bar = " World"; alert(foo + bar); })(); alert(foo + bar);
```
Question: What is the outcome of the two alerts above?
**Answer: "Hello World" & ReferenceError: bar is not defined**

```javascript
var foo = [];
foo.push(1);
foo.push(2);
```
Question: What is the value of foo.length?
**Answer: `2`

```javascript
var foo = {};
foo.bar = 'hello';
```
Question: What is the value of foo.length?
**Answer: `undefined`

### jQuery-Specific Questions:

* Explain "chaining".
* Explain "deferreds".
* What are some jQuery specific optimizations you can implement?
* What does `.end()` do?
* How, and why, would you namespace a bound event handler?
* Name 4 different values you can pass to the jQuery method.
  * Selector (string), HTML (string), Callback (function), HTMLElement, object, array, element array, jQuery Object etc.
* What is the effects (or fx) queue?
* What is the difference between `.get()`, `[]`, and `.eq()`?
* What is the difference between `.bind()`, `.live()`, and `.delegate()`?
* What is the difference between `$` and `$.fn`? Or just what is `$.fn`.
* Optimize this selector:
```javascript
$(".foo div#bar:eq(0)")
```
* Difference between 'delegate()' and 'live()'?


### CSS-Specific Questions:

* Describe what a "reset" CSS file does and how it's useful.
* Describe Floats and how they work.
* What are the various clearing techniques and which is appropriate for what context?
* Explain CSS sprites, and how you would implement them on a page or site.
* What are your favourite image replacement techniques and which do you use when?
* CSS property hacks, conditionally included .css files, or... something else?
* How do you serve your pages for feature-constrained browsers?
  * What techniques/processes do you use?
* What are the different ways to visually hide content (and make it available only for screen readers)?
* Have you ever used a grid system, and if so, what do you prefer?
* Have you used or implemented media queries or mobile specific layouts/CSS?
* Any familiarity with styling SVG?
* How do you optimize your webpages for print?
* What are some of the "gotchas" for writing efficient CSS?
* What are the advantages/disadvantages of using CSS preprocessors? (SASS, Compass, Stylus, LESS)
  * If so, describe what you like and dislike about the CSS preprocessors you have used.
* How would you implement a web design comp that uses non-standard fonts?
  * Webfonts (font services like: Google Webfonts, Typekit etc.)
* Explain how a browser determines what elements match a CSS selector?

### Optional fun Questions:

* What's the coolest thing you've ever coded, what are you most proud of?
* What are your favorite parts about the developer tools you use?
* Do you have any pet projects? What kind?
* What's your favorite feature of Internet Explorer?
