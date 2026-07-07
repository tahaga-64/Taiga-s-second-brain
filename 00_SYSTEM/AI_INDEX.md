# AI_INDEX

updated: 2026-07-07

## このVaultの目的

このVaultは、複数AIがユーザーの人物像、好み、進行中プロジェクト、判断履歴を共有するためのAI用セカンドブレインである。

目的は、ユーザーがChatGPT、Claude、Gemini、Codex、Taiga OSなどに対して、毎回自己紹介やプロジェクト説明をしなくて済む状態を作ること。

## AIが最初に読む順番

1. 00_SYSTEM/AI_RULES.md
2. 00_SYSTEM/WRITE_POLICY.md
3. 00_SYSTEM/MEMORY_SCHEMA.md
4. 10_CANONICAL_MEMORY/CURRENT_CONTEXT.md
5. 10_CANONICAL_MEMORY/USER_PROFILE.md
6. 10_CANONICAL_MEMORY/USER_PREFERENCES.md
7. 10_CANONICAL_MEMORY/ACTIVE_PROJECTS.md
8. 30_DECISIONS/DECISION_LOG.md
9. 60_TAIGA_OS_EXPORT/context_pack.json

## 原則

- AI_INBOXの情報は未確定として扱う
- CANONICAL_MEMORYの情報を優先する
- 古い情報と新しい情報が矛盾する場合は、updated_atが新しいものを優先する
- ただし、新しい情報でも未承認なら確定情報として扱わない
- 不明点は推測せず、確認事項として扱う
