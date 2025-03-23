---
question: "シークレット `MY_SECRET` が設定されている場合にのみ `step` を実行するにはどうすればよいですか？"
archetype: "questions"
title: "Question 068"
---

> https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#example-using-secrets
1. [x] シークレット `MY_SECRET` をジョブレベルの環境変数として設定し、その環境変数を参照してステップを条件付きで実行する
```yaml
  my-job:
    runs-on: ubuntu-latest
    env:
      my_secret: ${{ secrets.MY_SECRET }}
    steps:
      - if: ${{ env.my_secret != '' }}
```
1. [ ] ジョブレベルで次の条件を作成する
```yaml
  my-job:
    runs-on: ubuntu-latest
    if: ${{ secrets.MY_SECRET == '' }}
```
> secrets は if: 条件内で直接参照できません
1. [ ] ステップレベルで次の条件を作成する
```yaml
  my-job:
    runs-on: ubuntu-latest
    steps:
      - if: ${{ secrets.MY_SECRET == '' }}
```
> secrets は if: 条件内で直接参照できません
1. [ ] ステップレベルで次の条件を作成する
```yaml
  my-job:
    runs-on: ubuntu-latest
    steps:
      - if: ${{ secrets.MY_SECRET }}
```
> secrets は if: 条件内で直接参照できません
