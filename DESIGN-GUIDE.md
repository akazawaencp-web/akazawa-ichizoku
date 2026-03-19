# 赤澤一族 デザイン擦り合わせ用 指示書

## 別ターミナルでの作業指示

このファイルを新しいターミナル（Claude Code）で開いて、以下の指示で作業してもらう。

---

### 指示内容

```
赤澤一族のサイトのデザイン擦り合わせをしたい。
以下のファイルを参考にして作業してほしい。

1. 現在のデザイン（石庭スタイル）:
   /Users/akazawa_encp/Desktop/赤澤一族/令和版/index.html
   /Users/akazawa_encp/Desktop/赤澤一族/令和版/family-tree.html

2. デザインテスト（v3の10番「石庭」が選ばれた）:
   /Users/akazawa_encp/Desktop/赤澤一族/令和版/design-test-v3.html

3. カード左ライン決定（3番「金直線4px」が選ばれた）:
   /Users/akazawa_encp/Desktop/赤澤一族/令和版/design-test-v4-card.html

4. デザイン好みのメモリ:
   ~/.claude/projects/-Users-akazawa-encp-Desktop-digirise-portfolio/memory/feedback_suiboku-design.md

5. HANDOVER:
   ~/.claude/HANDOVER.md

RIOと一緒にデザインを擦り合わせて、確定したCSSを
/Users/akazawa_encp/Desktop/赤澤一族/令和版/ 内のHTMLファイルに適用してほしい。

確定デザイン要素:
- 全体: 石庭スタイル（v3 #10）
- カード左ライン: 金直線4px (#8b6914)
- フォント: Shippori Mincho (見出し) + Noto Sans JP (本文)
- 背景: linear-gradient(160deg, #f4f4f2, #f8f8f6, #f2f2f0)

RIOが「もっと擦り合わせたい」と言っているので、
具体的にどの要素を変えたいか聞いてから、デザインテストHTMLで比較検証する形で進めてほしい。
```

---

### 注意事項
- HTMLファイルのコンテンツ（テキスト）は変更しない — CSSのみ変更
- 変更後は必ず `open` コマンドでブラウザ表示して確認
- デザイン決定したらHANDOVERを更新する
- 全ページへの適用はCSSの差し替えだけで可能（各ページの<style>タグ内を統一）
