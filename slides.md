---
theme: default
background: https://images.unsplash.com/photo-1533001236066-0d375adf514e?q=80&w=2574&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
class: text-center
highlighter: shiki
lineNumbers: false
colorSchema: "dark"
drawings:
  persist: false
transition: slide-left
title: Next.jsを選ぶ3つの問い
mdc: true
---

# Next.jsを選ぶ<br>3つの問い

重要な観点、重要でない観点

---

# Profile

<div class="pb-5">
  <img src="https://avatars.githubusercontent.com/u/25711332?v=4" width="100" height="100">
</div>

```jsonc
// profile.jsonc
{
  "name": "佐藤 昭文",
  "alias": ["akfm_sato", "あっきー"],
  "job": "フロントエンドエキスパート",
  "tags": ["Next.js", "React", "Test", "リーン開発"],
  "sns": {
    "x": "akfm_sato",
    "zenn.dev": "akfm",
  },
}
```

---

# 今日のテーマ: 技術選定とNext.js

ゴール: 「Next.jsを選ぶ」とはどういうことなのか、解像度を高めてほしい

- Agenda
  - 私見: 技術選定とは何なのか
  - Next.jsの立ち位置
  - Next.jsを選ぶ3つの問い
  - Next.jsを選ぶ上で重要でない問い
- 前提
  - Reactの採用

---

# 私見: 技術選定とは何なのか

技術選定に関する議論に対する私見

- 技術選定はトレードオフを「選ぶ」こと
- 複数の変数を鑑みて総合的に「選ぶ」必要がある
  - メンバーのスキルセット
  - プロダクト特性的相性
  - 採用マーケティング、モチベーション
  - etc...

---
transition: fade
---

# Next.jsの立ち位置

現状Reactフレームワークの代表格

- Next.jsは引き続き高い人気
  - [State of React(Rendering Frameworks)](https://2024.stateofreact.com/en-US/libraries/back-end-infrastructure/)
  - [State of JS(Rendering Frameworks)](https://2022.stateofjs.com/ja-JP/libraries/rendering-frameworks/)
  - AIによる調査（Gemini、Grok）
  - 会社やコミュニティでの話題性
  - ~~[npm trends](https://npmtrends.com/@remix-run/react-vs-next-vs-react-router)~~: ダウンロードと人気は違う

---
transition: fade
---

# Next.jsの立ち位置

現状Reactフレームワークの代表格

<div class="flex justify-center">
  <img src="/state-of-js.png" class="h-100">
</div>

---

# Next.jsの立ち位置

現状Reactフレームワークの代表格

<div class="flex justify-center">
  <img src="/state-of-react.png" class="h-100">
</div>

---

# Next.jsを選ぶ3つの問い

個人的にNext.jsを選ぶ上で重要だと思う基準

1. 「**Next.jsを使いたいか**」
1. 「RSCを受け入れるか」
1. 「インフラ制約を受け入れられるか」

---

# Next.jsを選ぶ上で重要でない問い

個人的にNext.jsを選ぶ上で**重要ではない**と思う基準

- 「Next.jsに将来性を見出せるか」: 遠い未来の話はあまり意味がない
- 「高いパフォーマンスが必要か」: パフォーマンスだけがNext.jsではない
- 「DBアクセスを扱うかどうか」: Next.jsはBFF的側面が大きい

---

# まとめ

Next.jsを選ぶかどうか迷った時に思い出してほしい

- Next.jsを選ぶ問い
  1. 「**Next.jsを使いたいか**」
  1. 「RSCを受け入れるか」
  1. 「インフラ制約を受け入れられるか」
- 重要でない問い
  - 「Next.jsに将来性を見出せるか」
  - 「高いパフォーマンスが必要か」
  - 「DBアクセスを扱うかどうか」

---
layout: section
---

# End
