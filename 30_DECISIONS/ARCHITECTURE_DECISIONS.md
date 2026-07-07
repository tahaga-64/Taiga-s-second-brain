# ARCHITECTURE_DECISIONS

updated: 2026-07-07

## ADR-001: 二層メモリモデル

- Layer A: PostgreSQL memory_items（Taiga OS チャット学習）
- Layer B: Obsidian Markdown Memory Candidate（外部 AI）

## ADR-002: context_pack.json を最優先読取

チャット開始時は Markdown 全文ではなく `60_TAIGA_OS_EXPORT/context_pack.json` を先に読む。
