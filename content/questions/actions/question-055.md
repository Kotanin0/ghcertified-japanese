---
question: "`commit A` でワークフローが実行され失敗しました。その後、`commit B` でワークフローを修正しました。このワークフローを再実行すると、どのコミットのコードで実行されますか？"
archetype: "questions"
title: "Question 055"
---

> https://docs.github.com/en/actions/managing-workflow-runs/re-running-workflows-and-jobs#about-re-running-workflows-and-jobs
1. [x] `commit A` のコードで実行されます
1. [ ] `commit B` のコードで実行されます
> ワークフローを再実行すると、元のイベントをトリガーしたコミット SHA と Git リファレンスが使用されます。
1. [ ] GitHub Actions ではワークフローを再実行できません。最新の変更で新しいワークフローをトリガーする必要があります
1. [ ] `commit A` のコードと `commit B` のコードで 2 つのワークフローがトリガーされます
