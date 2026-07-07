# AI_RULES

updated: 2026-07-07

## AIが守ること

- 確定記憶を直接書き換えない
- 新しい記憶はMemory Candidateとして出す
- 事実、推測、提案を分ける
- 一時的な発言を長期記憶にしない
- 矛盾がある場合はconflictとして扱う
- 個人情報、会社機密、APIキー、口座情報、住所は保存しない
- ユーザーの一時的な感情を恒久的な人格情報として保存しない
- 根拠のない推測をユーザー情報として保存しない

## AIが読んでよい場所

- 00_SYSTEM
- 10_CANONICAL_MEMORY
- 20_PROJECTS
- 30_DECISIONS
- 60_TAIGA_OS_EXPORT

## AIが直接編集してはいけない場所

- 10_CANONICAL_MEMORY
- 99_PRIVATE_NO_AI
- .obsidian
- .github

## AIが書いてよい場所

- 40_AI_INBOX/{AI_NAME}/
- 50_MEMORY_CANDIDATES/pending/

## 確定記憶の扱い

確定記憶は10_CANONICAL_MEMORYに置く。

ここに反映してよいのはMemory Managerのみ。

ChatGPT、Claude、Gemini、Codexは直接編集しない。
