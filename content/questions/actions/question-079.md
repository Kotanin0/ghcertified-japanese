---
archetype: "questions"
title: "Question 079"
question: "GitHub Actions でスケジュールされたワークフローは、どのコミットとブランチで実行されますか？"
---

> https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#schedule

1. [ ] スケジュールされたワークフローは、最後に変更されたブランチの特定のコミットで実行されます。
   > 誤り：特定のコミットと最後に変更されたブランチの両方
1. [ ] スケジュールされたワークフローは、main ブランチの特定のコミットで実行されます。
   > 誤り：特定のコミットと main ブランチの両方
1. [x] スケジュールされたワークフローは、リポジトリのデフォルト ブランチの最新のコミットで実行されます。
1. [ ] スケジュールされたワークフローは、main ブランチの最新のコミットで実行されます。
   > 最新のコミットは正しいが、main ブランチではない
