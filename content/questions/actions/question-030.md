---
question: "job3はいつ実行されますか？"
archetype: "questions"
title: "Question 030"
---

```yaml
  jobs:
    job1:
    job2:
      needs: job1
    job3:
      if: ${{ always() }}
      needs: [job1, job2]
```
> https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#example-not-requiring-successful-dependent-jobs
1. [x] job1とjob2が完了した後、成功したかどうかに関係なくjob3が実行されます。
1. [ ] `if: ${{ always() }}` と `needs` を一緒に使用することはできません。ワークフローは起動時に失敗します。
1. [ ] job1とjob2が正常に完了した後にjob3が実行されます。
1. [ ] job1とjob2の両方が失敗した後にjob3が実行されます。
