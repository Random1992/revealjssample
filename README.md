# revealjssample

- 公式サンプルは以下

https://raw.githubusercontent.com/evilz/vscode-reveal/master/sample.md

- VSCのエクステンションのページは以下。プレビューだが、人気度高い。

https://marketplace.visualstudio.com/items?itemName=evilz.vscode-reveal

## 基本はmarkdown通りの使い方。スライド特有のことは以下

- --- で横ベージ遷移
- -- で縦ページ遷移

## デフォルトでは、Hタグは大文字になってしまうので、以下で対応する必要がある


<style type="text/css">
  .reveal h1,
  .reveal h2,
  .reveal h3,
  .reveal h4,
  .reveal h5,
  .reveal h6 {
    text-transform: none;
  }
</style>

https://srz-zumix.blogspot.com/2014/09/revealjs-markdown.html
