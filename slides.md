---
theme: default
background: https://images.unsplash.com/photo-1504966981333-1ac8809be1ca?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
class: text-center
highlighter: shiki
lineNumbers: false
colorSchema: "dark"
drawings:
  persist: false
transition: slide-left
title: Next.jsを選ぶ恩恵と制約
mdc: true
---

# Next.jsを選ぶ恩恵と制約

「Next.jsを選ぶ」とはどういうことなのか

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

「Next.jsを選ぶ」とはどういうことなのか、解像度を高めてほしい

- Agenda
  - 技術選定とは何なのか
  - Next.jsを選ぶ恩恵
  - Next.jsを選ぶ制約
  - Next.jsを選ぶ上で枝葉末節な論点
- 前提
  - Reactの採用

---

# 技術選定とは何なのか

技術選定に関する議論に対する私見

技術選定とは<span class="font-bold" v-mark="{ at: 1, color: 'red', type: 'underline'}">選ぶこと</span>

- 得られる**恩恵**が大きく、**制約**が許容できることが選定基準になる
- 恩恵と制約は、様々な観点で洗い出す必要がある
  - プロダクト特性
  - 開発効率（短期、中長期）
  - 開発規模
  - スキルセット
  - 採用マーケティング、モチベーション
  - etc...

---

# Next.jsを選ぶ恩恵

個人的にNext.jsを選ぶ上で魅力だと思う点

- 現在最も人気なフレームワーク
- 破壊的変更に対する慎重な姿勢
- デフォルトで高いパフォーマンス

中長期的開発や大規模開発においては魅力的な要素が多い

---
transition: fade
---

# 余談: Next.jsの人気

現状Reactフレームワークの代表格

- [State of React(Rendering Frameworks)](https://2024.stateofreact.com/en-US/libraries/back-end-infrastructure/)
- [State of JS(Rendering Frameworks)](https://2022.stateofjs.com/ja-JP/libraries/rendering-frameworks/)
- AIによる調査（Gemini、Grok）
- 会社やコミュニティでの話題性
- ~~[npm trends](https://npmtrends.com/@remix-run/react-vs-next-vs-react-router)~~: ダウンロードと人気は違う

---
transition: fade
---

# 余談: Next.jsの人気

現状Reactフレームワークの代表格

<div class="flex justify-center">
  <img src="/state-of-js.png" class="h-100">
</div>

---

# 余談: Next.jsの人気

現状Reactフレームワークの代表格

<div class="flex justify-center">
  <img src="/state-of-react.png" class="h-100">
</div>

---

# Next.jsを選ぶ制約

個人的にNext.jsを選ぶ上で重要だと思う点

- RSCへの共感
- インフラ制約
- 実装品質への不安
- 孤立したエコシステム

他のフレームワークには他の制約があるので、許容できずとも<span class="font-bold" v-mark="{ at: 1, color: 'red', type: 'underline'}">選択肢があるとは限らない</span>

---

# Next.jsを選ぶ上で枝葉末節な論点

個人的にNext.jsを選ぶ上で**重要ではない**と思う点

- 将来的な人気
  - 遠い未来の話は妄想にしかならないので考慮しても意味がない
- 高いパフォーマンスの必要有無
  - 「パフォーマンス不要、Next.js不要」は短絡的
  - 「パフォーマンス不要」の大半は無知
- DBアクセスの有無
  - Next.jsはいわゆるフルスタックフレームワーク**ではない**

---

# まとめ

Next.jsを選ぶかどうか迷った時に思い出してほしい

- Next.jsを選ぶ恩恵
  - 現在最も人気なフレームワーク
  - 破壊的変更に対する慎重な姿勢
  - デフォルトで高いパフォーマンス
- Next.jsを選ぶ制約
  - RSCへの共感
  - インフラ制約
  - 実装品質への不安
  - 孤立したエコシステム

---
layout: section
---

# End
