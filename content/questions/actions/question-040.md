---
question: "次の例では、`workflow A` は `inherit` キーワードを使用してすべてのシークレットを `workflow B` に渡します。その後、`workflow B` は `workflow C` を呼び出します。この例における `secrets` に関する記述のうち正しいものはどれですか？"
archetype: "questions"
title: "Question 040"
---


```yaml
  jobs:
    workflowA-calls-workflowB:
      uses: octo-org/example-repo/.github/workflows/B.yml@main
      secrets: inherit
```

```yaml
  jobs:
    workflowB-calls-workflowC:
      uses: different-org/example-repo/.github/workflows/C.yml@main
```
> https://docs.github.com/en/actions/using-workflows/reusing-workflows#passing-secrets-to-nested-workflows
1. [x] `workflow A` で利用可能なすべてのシークレットは `workflow B` でも利用可能ですが、`workflow C` では利用できません。
1. [ ] `octo-org` 組織および `octo-org/example-repo` リポジトリのすべてのシークレットは `workflow B` で利用可能ですが、`workflow C` では利用できません。
> `octo-org` 組織のすべてのシークレットが `octo-org/example-repo` に提供される必要はありません。
1. [ ] `workflow A` で利用可能なすべてのシークレットは `workflow B` および `workflow C` でも利用可能です。
> `workflow B` が `workflow C` を呼び出す際に `secrets: inherit` を追加する必要があります。
1. [ ] `workflow A` で利用可能なリポジトリおよび環境シークレットのみが `workflow B` で利用可能ですが、`workflow C` では利用できません。組織スコープのシークレットは継承できません。
