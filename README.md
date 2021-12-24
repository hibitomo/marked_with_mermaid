# marked_with_mermaid

管理者権限ないけど、どうしてもMarkdownのドキュメントとMermaid.jsを使いたくて、
marked.jsのオプション弄ってみたhtmlのサンプル。

1. git cloneか、zipでダウンロードする
2. sample.htmlをメモ帳などで開き、 `<!-- Markdown area -->` で囲まれた箇所にMarkdownを書く。
3. sample.htmlをブラウザ（Not Internet Explorer）で開く

### 注意事項

- 直接、htmlを編集することから、HTMLのタグっぽいものを書くとバグる。
- ほかの場所で使いたいときは、jsとcssのフォルダも一緒に持っていくか、htmlのソースに記載してあるパスを書き換える。

### 呼び出しているjavascriptとかcssとか。

- Marked.js
  - https://github.com/markedjs/marked
- Mermaid.js
  - https://mermaid-js.github.io/mermaid/#/
- github-markdown-css
  - https://github.com/sindresorhus/github-markdown-css
