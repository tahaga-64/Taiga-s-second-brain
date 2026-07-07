# Taiga OS — Architecture

updated: 2026-07-07

## 構成

- Web PWA (Next.js) on Vercel
- Brain API (FastAPI) on Cloud Run
- PostgreSQL (Neon) / SQLite (local)
- Obsidian Vault on GitHub private repo

## メモリ二層

- Layer A: DB memory_items（チャット背景学習）
- Layer B: Obsidian Memory Candidate（外部 AI 書き込み）
