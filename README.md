# 制作サンプル

坂上／ライティング・LP制作・Webコーディング

公開ページ: https://ge7188-code.github.io/portfolio/

## 収録物

### 記事コンテンツ型LP「平日の夕食づくりが「30分」で終わる家の共通点」

PPC広告からの流入を想定した記事コンテンツ型LP。ワイヤーフレームの作成からデザイン、HTML / CSS でのコーディングまで通しで制作。

- ページ: [/article-lp/](https://ge7188-code.github.io/portfolio/article-lp/)
- 制作意図・設計方針: [/article-lp/about.html](https://ge7188-code.github.io/portfolio/article-lp/about.html)

技術面の特徴:

- スマートフォン基準で設計し、`min-width` でタブレット・PCへレスポンシブ対応
- **JavaScript不使用**（FAQは `<details>`、目次はアンカー、追従CTAは `position: fixed`）
- **Webフォント不使用・画像リクエスト0件**（アイコン・図版はすべてインラインSVG）
- 外部読み込みは CSS 1本のみ
- `prefers-reduced-motion` 対応、フォーカス表示確保、`env(safe-area-inset-bottom)` 対応

```
article-lp/
├── index.html      ページ本体
├── about.html      制作意図・設計方針
└── css/style.css   スタイル一式
```

## 注意

掲載しているのはポートフォリオ用に制作したサンプルです。
登場するサービス名・企業名・価格・調査結果・利用者の声はすべて架空のものであり、実在のものとは一切関係ありません。
