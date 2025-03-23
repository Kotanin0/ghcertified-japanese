---
question: "ステップの1つが失敗した場合にジョブの失敗を防ぐには、次のどれを含めることができますか？"
archetype: "questions"
title: "Question 035"
---

> https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#jobsjob_idstepscontinue-on-error
1. [x] 失敗するステップに `continue-on-error` フラグを含める
```yaml
  steps:
      - uses: my-org/failing-action@v1
        continue-on-error: true
```
1. [ ] 失敗するステップに `ignore-error` フラグを含める
```yaml
  steps:
      - uses: my-org/failing-action@v1
        ignore-error: true
```
1. [ ] 失敗するステップに `failure()` 条件を含める
```yaml
  steps:
      - uses: my-org/failing-action@v1
        if: failure()
```
1. [ ] 失敗するステップに `always()` 条件を含める
```yaml
  steps:
      - uses: my-org/failing-action@v1
        if: always()
```
