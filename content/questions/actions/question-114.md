---
question: "以下の例で、ジョブ内のマトリックス変数の現在の値にアクセスするにはどうすればよいですか？"
archetype: "questions"
title: "Question 114"
---

```yaml
jobs:
    example_matrix:
        strategy:
            matrix:
                version: [10, 12, 14]
                os: [ubuntu-latest, windows-latest]
```
> https://docs.github.com/en/actions/using-jobs/using-a-matrix-for-your-jobs#using-a-matrix-strategy
1. [x] `matrix`コンテキストを使用して、`matrix.version`や`matrix.os`のような構文で変数を参照する
1. [ ] `matrix.property`構文を使用する
1. [ ] ジョブ構成内で`context`キーワードを使用する
1. [ ] `version`や`os`のような構文で変数に直接アクセスする
