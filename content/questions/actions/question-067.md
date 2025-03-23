---
question: "構成変数 `MY_VAR` が `MY_VALUE` の値を持つ場合にのみジョブをトリガーする正しい方法はどれですか？"
archetype: "questions"
title: "Question 067"
---

> https://docs.github.com/en/actions/learn-github-actions/contexts#example-usage-of-the-vars-context
1. [x] ジョブレベルで次の条件を作成する
```yaml
  my-job:
    if: ${{ vars.MY_VAR == 'MY_VALUE' }}
```
1. [ ] ジョブレベルで次の条件を作成する
```yaml
  my-job:
    if: ${{ vars.MY_VAR }} == 'MY_VALUE'
```
> これは常に True と評価されます
1. [ ] 構成変数は `if` 条件で使用できないため不可能です
> これは `secrets` に当てはまりますが、構成変数には当てはまりません
1. [ ] 構成変数はジョブレベルの `if` 条件で使用できないため不可能です
> これは `secrets` に当てはまりますが、構成変数には当てはまりません
