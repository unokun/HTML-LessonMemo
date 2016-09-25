# 序章(5分)
[序章](pre.md)
 序章-6 CodeCampの進め方と目標を話せばOKかな。

　ゴールは、Webアプリが作れること。
　そのために必要なのは以下の技術

* HTML + CSS
* Javascript
* プログラミング言語(PHP/Ruby/Java)

HTML + CSS --> Javascript --> PHP

という順番で学ぶことを推奨している。

料理紹介ページが作れたらかなりなスキルだと思います。

# HTML/CSSとは
[HTML/CSSとは](1.md)
HTML(HyperText Markup Language): パイパーテキスト
テキストの他に、表、リスト、画像、動画、リンクを組み込むことができる。
文書の構造を記述する。
ハイパーリンクは、Webの基本。

HTMLは複数の要素(表、リスト...)で構成される。各要素はタグ、開始タグと終了タグで囲まれる。
※) input要素のようにテキスト要素を子要素として含まない場合、閉じタグの書き方が少し異なる。
`<h1></h1>, <input />`


CSS: 見た目を指定する。

# HTML基礎
[HTML基礎](2.md)

ここで使われる要素は、非常によく使われるので使って見る。
これ以外には、dt(description term), dl(descriptio list)がある。

HTML/CSSは、W3Cという団体で標準化されている。この団体には、Microsoft, Apple, Googleなどブラウザを開発している会社が参加している。
* [W3C](https://www.w3.org/)
* [W3Cの仕様書等の文書の日本語訳集](https://www.w3.org/Consortium/Translation/Japanese)

また、アクセシビリティについても目を通していた方が良い。
ハンディキャップがある人に優しい画面は、健常者にも優しい。
SEO(Google検索エンジンのランク)にも良い効果をもたらす可能性がある。

[Web Content Accessibility Guidelines (WCAG) 2.0](http://waic.jp/docs/WCAG20/Overview.html)

# CSS基礎
CSSが複数ある場合、どれが適用されるかを決める指標にCSSの詳細度がある。
詳細度が同じ場合には後勝ち。
* [Selectors Level 3](https://www.w3.org/TR/2011/REC-css3-selectors-20110929/)
* [詳細度: MDN](https://developer.mozilla.org/ja/docs/Web/CSS/Specificity)
* [エンジニアはもう一度CSSとちゃんと向き合ってみよう - 詳細度編: Qiita](http://qiita.com/izumin5210/items/8ae78cb4f4bd325bccb4)
* [ご存じ、ないのですか？CSSの優先順位: SlideShare](http://www.slideshare.net/yumi-uniq-ishizaki/css-13918388)

# ボックス
ボックス(モデル)は、Webページ(HTML)のレイアウトにする時に非常に重要な概念です。
横幅をブラウザの幅として、上から順に箱をレイアウトしていきます。
ボックスは、表示領域の周りの境界線(ボーダー)、margin(ボックス外側の余白)、padding(ボックス内側の余白)から構成されます。

注意) ボーダーはレイアウトを確認する時によく使われます。
　　　ただし、ボーダーも幅(太さに依存します)を持っているので、レイアウトする場合には注意が必要です。

ボックスは表示プロパティ(ブロック、インライン)によって、レイアウトの仕方を変えることができる。

## div要素とspan要素
共に「自身に意味を持たない」要素となっており、文章の構造を定義するためではなく、CSSを適用するために用いられます。
この2つはdisplayプロパティの初期値が異なり、div要素はブロックボックス、span要素はインラインボックスとなっています。


