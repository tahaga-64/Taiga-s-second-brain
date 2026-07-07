# WRITE_POLICY

updated: 2026-07-07

## 書き込みルール

AIは確定記憶を直接編集しない。

AIは必ずMemory Candidate形式で書き込む。

## 書き込み可能

- 40_AI_INBOX/{AI_NAME}/
- 50_MEMORY_CANDIDATES/pending/

## 書き込み禁止

- 10_CANONICAL_MEMORY/
- 99_PRIVATE_NO_AI/
- .obsidian/
- .github/

## ファイル命名規則

YYYY-MM-DDTHHmmss_AI名_memory_candidate.md

## 例

2026-07-07T113000_ChatGPT_memory_candidate.md

## 上書き禁止

AIは既存ファイルを上書きしない。

必ずタイムスタンプ付きの新規ファイルとして作成する。

## 確定記憶への反映

approvedになったMemory Candidateのみ、Memory ManagerがCanonical Memoryへ反映する。
