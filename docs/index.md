<style>
  body {
    background: lightcyan;
    width: 800px;
    margin: auto;
  }

  h1 {
    color: maroon;
    text-align: center;
  }

  p {
    color: gray;
    border: 1px solid gray;
    padding: 10px;
  }
</style>

## Images

![義母と娘のブルースの紹介画像](assets/gibomusu.jpg)

# Youtube Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/XzpKlwETET4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# マークダウンで書いたページ

人生は、生きてるだけで丸儲け、争わない、楽しみ、チャレンジするそれで、人の役に立てれば最高!

## 中野信子氏「生きてるだけで丸儲け」は生物学的にも正しい

脳科学を通して伝えたいことはシンプルで「生きている者が勝ち！」ということです。

ほとんどの生物の目的というのは「生き延びること」と「子孫を残すこと」なんですね。

ですが人間だけはそうではない。「ひと花咲かせよう！」みたいなのがあって、これがすごい特異的なんですよ。本当は生き延びて生殖するために脳ができたんですけど、でもその脳が発達しすぎてしまったがために「ひと花咲かせよう！」ができちゃうわけです。

# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

## Emphasis

**This is bold text**
__This is bold text__

*This is italic text*
_This is italic text_

~~Strikethrough~~

## Blockquotes

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar

## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 2 of code
    line 3 of code

Block code "fences"

```
Sample text here...
```

Syntax highlighting

```js
var foo = function (bar) {
  return bar++;
};
console.log(foo(5));
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica

### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^second].

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**.

    and multiple paragraphs.

[^second]: Footnote text.
