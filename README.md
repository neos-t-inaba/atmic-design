# Atomic Design

[http://bradfrost.com/blog/post/atomic-web-design/](http://bradfrost.com/blog/post/atomic-web-design/)

デザインシステム（スタイルガイドやブランドガイドライン等）を作る方法論で、  
5つのレベルがあり、パーツを組み合わせて繰り返し可能なエレメントやテンプレートが作成できるシステムを構築すること。


5つのレベル 
![](https://github.com/neos-t-inaba/atmic-design/blob/master/_readme/img/compressed/atomic-design.img.stage.png)


## 段階

###  Atoms 原子

![](https://github.com/neos-t-inaba/atmic-design/blob/master/_readme/img/compressed/atomic-design.img.atoms.png)

基本的なビルディングブロックで、これ以上分解できないもの。

> カラーパレット、フォント、ボタン、テキスト、ラベル、ヘディング、アイコン、フォームパーツ、アニメーション etc...

### Molecules 分子

![](https://github.com/neos-t-inaba/atmic-design/blob/master/_readme/img/compressed/atomic-design.img.molecules.png)

原子を結合した、独自の特性を持った化合物の最小単位。  
比較的単純だが意味をもつUI？

> ラベルとinput:textとsubmitボタンを組み合わせた検索フォーム etc...

### Organisms 有機体

![](https://github.com/neos-t-inaba/atmic-design/blob/master/_readme/img/compressed/atomic-design.img.organisms.png)

分子を組み合わせたもの。  
より複雑で明瞭なUI？

> ロゴと主要ナビゲーションと検索フォームを組み合わせたヘッダー etc...

### Templates テンプレート

![](https://github.com/neos-t-inaba/atmic-design/blob/master/_readme/img/compressed/atomic-design.img.templates.png)

有機体を組み合わせたワイヤーフレームとなるもの。構成が見えるもの。  
コンテンツは入ってない状態。  
（実際のコンテンツが必要でなければシステムのプログラミングを始められる状態？）

### Pages ページ

![](https://github.com/neos-t-inaba/atmic-design/blob/master/_readme/img/compressed/atomic-design.img.pages.png)

実際の写真やテキスト等のコンテンツが入った状態。


## コード（参考）

### Pattern Lab

Atmic Design を取り入れたUIコンポーネント生成ツール

[http://patternlab.io/](http://patternlab.io/)

[Qiitaの参考になる記事](http://qiita.com/Mwrote/items/3eaed745185364135fa4)

### APBCSSなるCSS設計を提唱してる方もいたりする
[http://apbcss.com/](http://apbcss.com/)


## 考察

ざっくりリード文の翻訳
> Webデザインの技術が進化するにつれて、単純なコレクションを作るのではなく、思慮深い設計システムを開発する必要性を感じてます。
> 色、タイポグラフィ、グリッド、質感などの基礎を確立することに焦点をあててるが結局それは主観です。
> インターフェースがどんなものでできてるか、より組織的な方法で設計システムを構築することはできないかを考えてきました。
> いろいろ探し求めて科学に戻ってきました。全ての物質は原子でできてると考えられてます。原子は互いに結合し分子を形成し、より複雑な有機体に結合し、最終的には宇宙のすべての物質を創造します。
> 同様にインターフェースは小さなコンポーネントで構成されてます。つまり、インターフェイス全体を基本的なビルディングブロックに分割してそこから処理することができます。それが原子設計の基本です。


> 抽象的から具体的に通過する能力を与えます。
> 一貫性と拡張性を促進すると同時に、最終的な状況で物事を表示するシステムを作成することができます。

設計システムの方法論なので、デザイナーとかエンジニアとかそーゆーことではなく、みんなが主観じゃなく統一した思想（システム）でコンポーネント単位で考えて作っていこうよ！って感。  
そのためにこんな方法あるよ！的な感。


