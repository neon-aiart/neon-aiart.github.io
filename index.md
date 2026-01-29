---
layout: default
---

<div id="content"></div>

<script>
  // ProfileリポジトリのREADME（Rawデータ）を取得
  fetch('https://raw.githubusercontent.com/neon-aiart/neon-aiart/main/README.md')
    .then(response => response.text())
    .then(text => {
      // MarkdownをHTMLに変換して表示（簡易的な方法）
      // もし複雑な装飾があるなら、ここにMarkdownパーサーを入れるか、
      // 以下の「もっとシンプルな方法」を使ってください
      document.getElementById('content').innerText = text;
    });
</script>