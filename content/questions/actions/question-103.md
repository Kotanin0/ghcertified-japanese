---
question: "GitHub Actions で `branches` フィルターと `paths` フィルターの両方を定義した場合、ワークフローの実行にどのような影響がありますか？"
archetype: "questions"
title: "Question 103"
---


> https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#onpull_requestpull_request_targetbranchesbranches-ignore
1. [x] ワークフローは `branches` と `paths` の両方が満たされた場合にのみ実行されます
1. [ ] ワークフローは `branches` または `paths` のいずれかが満たされた場合に実行されますが、一致するフィルターのみが適用されます
1. [ ] ワークフローは `branches` または `paths` のいずれかが満たされた場合に実行されます
1. [ ] ワークフローは `branches` と `paths` の両方が満たされた場合には実行されません
