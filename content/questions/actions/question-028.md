---
question: "ワークフロー`Deploy Prod`が常に1回だけ実行されるようにするにはどうすればよいですか？"
archetype: "questions"
title: "Question 028"
---

> https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#concurrency

1. [x] ワークフローレベルで`concurrency`を使用する
```yaml
concurrency: ${{ github.workflow }}
```
1. [ ] ワークフローレベルで`queue`を使用する
```yaml
queue: ${{ github.workflow }}
```
1. [ ] ワークフローレベルで`order`を使用する
```yaml
order: ${{ github.workflow }}
```
1. [ ] ワークフローレベルで`parallel`を使用する
```yaml
parallel: ${{ github.workflow }}
```
