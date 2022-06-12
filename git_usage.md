# How to use git
## リモートの main ブランチをローカルブランチに取り込む
---
こまめに main の変更を取り込むことで、マージする時に問題が起こりにくい。
ローカルブランチ上で以下を実行。
```bash
$ git fetch origin
$ git merge origin/main
```
