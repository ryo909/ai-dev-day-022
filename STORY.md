# Day022 Story — Idea Combo Deck

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day022専用にテーマをseed固定して再生成時の見た目を安定化
- fun用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: idea_cards
- Mechanic: card_pairing
- Input/Output: multi_select_tokens -> card_stack
- Audience Promise: faster_idea_filtering
- Publish Hook: 失敗案を除外しながら次案を出す
- Complexity Tier: small
- Selected components: none
- Complexity hint: Keep the tool single-purpose and stable. Add at most one safe enhancement component.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day022｜Idea Combo Deck
制約付きのアイデア探索をカード操作で進める組み合わせツール。（話題:GitHub Trending (A）
