# 論文のようなページになるCSS

を目指してだらだらCSSを作ってます。

body からガッツリ影響しますのでご注意ください。

## 使い方

### CSS を追加

```html
<link rel="stylesheet" href="https://tanjoin.github.io/paper-css/main.css">
```

### タイトルの書き方

h1 タグに `class="title"` を追加してください。
英語のタイトルを書く場合は、 `class="title english"` を追加してください。

```html
<h1 class="title">論文のようなページになるCSS</h1>
<p class="title english">A CSS for Creating Paper-like Pages</p>
```

### 著者の書き方

`class="author"` を追加してください。
英語の著者を書く場合は、 `class="author english"` を追加してください。

```html
<p class="author">著者名</p>
<p class="author english">Author Name</p>
```

### 本文の書き方

section タグ内に本文を記述してください。

後は index.html を参考にしてください。

