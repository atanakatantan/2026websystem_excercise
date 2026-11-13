<style>
  body {
    background: #f0fdff;
    width: min(860px, calc(100% - 32px));
    margin: auto;
    color: #334155;
    font-family: "Yu Gothic UI", "Yu Gothic", "Meiryo", sans-serif;
    line-height: 1.8;
  }

  h1 {
    color: maroon;
    text-align: center;
  }

  h2 {
    color: #0f766e;
    border-bottom: 2px solid #99f6e4;
    padding-bottom: 4px;
  }

  p,
  li,
  blockquote,
  table {
    color: #475569;
  }

  img {
    max-width: 100%;
    height: auto;
  }

  iframe {
    max-width: 100%;
  }
</style>

# 課題2：Markdownで書いたページ

[課題一覧へ戻る](../index.html)

このページは、課題資料の課題2に沿って、Markdown記法を使って作成したホームページです。
Markdownでも、見出し、強調、引用、リスト、表、リンク、画像、動画を組み合わせることで、読みやすいWebページを作ることができます。

## Emphasis

**Markdownでは太字を簡単に書けます。**

*斜体も使うことができます。*

~~取り消し線も表現できます。~~

## Blockquotes

> Webページは、HTMLだけでなくMarkdownのような軽量な記法でも作成できます。
>> GitHub PagesではMarkdownファイルを公開ページとして扱うこともできます。

## Lists

### 順序なしリスト

- 見出しを書く
- 本文を書く
- 画像を入れる
- YouTube動画を入れる
- 外部リンクを入れる

### 順序ありリスト

1. Markdownファイルを作成する
2. 内容を編集する
3. GitHub Pagesで公開する

## Code

インラインコードは `index.md` のように書けます。

```html
<h1>MarkdownからWebページを作る</h1>
<p>HTMLを直接書くこともできます。</p>
```

## Tables

| 項目 | 内容 |
|---|---|
| ファイル | `docs/index.md` |
| 記法 | Markdown |
| 追加要素 | 画像、動画、リンク、CSS |

## Images

![義母と娘のブルースの紹介画像](assets/gibomusu.jpg)

## Youtube Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/IX87le_EokM" title="義母と娘のブルース 主題歌" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Links

- [TBS公式サイト](https://www.tbs.co.jp/gibomusu_blues/)
- [課題3の自由制作ページ](../task3/index.html)
