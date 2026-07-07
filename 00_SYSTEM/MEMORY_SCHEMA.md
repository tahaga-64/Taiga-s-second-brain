# MEMORY_SCHEMA

updated: 2026-07-07

## Memory Candidateの種類

- user_profile: 人物像
- preference: 好み
- project: プロジェクト情報
- decision: 意思決定
- task: タスク
- skill: スキル・学習
- constraint: 制約条件
- relationship: 人間関係。ただし慎重に扱う

## status

- pending: 未確認
- approved: 採用
- rejected: 却下
- conflict: 矛盾あり

## confidence

- high
- medium
- low

## privacy_level

- public
- normal
- sensitive

## 自動承認禁止条件

以下は自動承認しない。

- privacy_level=sensitive
- confidence=low
- memory_type=relationship
- 住所、口座、APIキー、会社機密を含む
- 既存のCanonical Memoryと矛盾する
- 一時的な感情や雑談に見える
