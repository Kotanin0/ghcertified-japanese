---
question: "複数のジョブを持つワークフローで、すべてのジョブが GitHub ホストランナー上で実行される場合、すべてのジョブが同じランナーマシンで実行されることは保証されますか？"
archetype: "questions"
title: "Question 075"
---

> https://docs.github.com/en/actions/using-jobs/choosing-the-runner-for-a-job#choosing-github-hosted-runners
1. [x] いいえ
1. [ ] はい
> 各ジョブは、runs-on で指定されたランナーイメージの新しいインスタンスで実行されます
