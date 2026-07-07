---
type: canonical_memory
updated_at: 2026-07-07T12:00:00+09:00
---

# CURRENT_CONTEXT

## 現在の最重要テーマ

- Taiga OSを自分専用AIエージェントとして完成させる
- Obsidianを複数AIが読み書きする記憶基盤にする
- ChatGPT、Claude、Gemini、Codexが作った記憶をTaiga OSが理解できるようにする

## 現在の方針

- Obsidian VaultはGitHub private repoと連携済み
- AIは確定記憶を直接編集しない
- AIはMemory Candidateを作成する
- Taiga OSはCanonical Memoryとcontext_pack.jsonを読む
- Memory Managerが候補を審査して確定記憶へ昇格させる

## 直近の課題

- フォルダ構成の確定
- Memory Candidate形式の統一
- Taiga OS側の読み取りAPI実装
- GitHub Webhookまたは定期取得の実装
- context_pack.jsonの自動生成
