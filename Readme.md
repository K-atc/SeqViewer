SeqViewer
====

連番画像をブラウザで快適に閲覧する機能を1つのhtmlファイルで実現しました。
連番画像があるフォルダにviewer.htmlをコピーしてブラウザで開きましょう。

特徴
----
canvasを利用して画像をウインドウ内いっぱいに表示します。そのため画像の描画が高速です。

ショートカット
----
画面内のShortcutsをご覧ください。

<!--
ユースケース
----
例えば画像への索引をMarkdownで記述します。
```Markdown
阿笠博士が回転
====

[0](agasa-viewer.html#0)
----
初期状態

[90](agasa-viewer.html#2)
----

```

MarkdownファイルはMarkdown対応のビューア[^1]を入れたブラウザで開くとhtmlの様に閲覧できます。
リンクをクリックするとその画像の閲覧画面が表示されます。

[^1]: Firefoxであれば [Markdown Viewer](https://github.com/Thiht/markdown-viewer) などがあります
-->