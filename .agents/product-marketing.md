# Product Marketing Context — hikari(NURO光ほか 回線集客)

_全マーケティングスキルが最初に読む土台。数値は hikari-hq/CLAUDE.md と docs/ が一次情報。_

## 1. Product Overview
- 一行: インターネット回線(NURO光ほか)の申込を、回線診断LPで集めるリード獲得事業。
- モデル: LP集客 → LINE/フォーム → インサイドセールス架電 → 申込。エリア外は受け皿商材で収益化。
- 総リーダー: エルくん。最終決裁: 小柳さん。

## 2. Target Audience
- 主対象: 回線の新規/乗り換えを検討する個人・世帯。**NURO提供エリア内**が本命。
- Jobs to be done: 今より安く/速く/手間なく回線を決めたい。

## 3. Problems & Pain Points
- 料金・エリア・工事が分かりにくい/比較が面倒/申込の一歩が重い。

## 4. Positioning & Messaging
- 損の可視化(今のままの割高さ)× 1画面完結で不安を消す。過度に煽らない。

## 5. CTA / Offer
- CV=LINE登録/フォーム送信。FORM_ENDPOINT 未設定時は送信中止し**偽の完了画面を出さない**(hikari-lp-integrity)。

## 6. 番人KPI(全施策の判断基準)
- **CPA 1,000円以下**(根拠なき施策は実行しない) / LP CVR 3%以上 / 5分以内架電率 90% / リード→アポ率 30% / 月100リード継続。
- 関連スキル: hikari-cpa-guard / hikari-triangle-review / hikari-report-thresholds(撤退CPA2,400円×2週)。

## 7. Guardrails
- **エリア厳守**: NURO提供エリア外への配信禁止。エリア外リードは受け皿商材へ(収益化率80%)。
- 壁打ち義務(攻め/検証/守り)。全会一致は前提を疑う。設計・戦略の機密は公開リポジトリ(hikari-lp)に置かない。
