---
question: "このワークフローは、次の条件を満たすすべてのプルリクエストで実行されます："
archetype: "questions"
title: "Question 018"
---

```yaml
on:
  pull_request:
    branches:
      - 'release/**'
      - '!release/**-alpha'
```
> https://docs.github.com/en/actions/using-workflows/triggering-a-workflow#example-including-and-excluding-branches
1. [x] 対象ブランチ名が `release` で始まり、`-alpha` で終わらない場合
1. [ ] 対象ブランチ名が `release` で始まる場合
1. [ ] ソースブランチ名が `release` で始まり、`-alpha` で終わらない場合
1. [ ] ソースブランチ名が `release` で始まる場合
