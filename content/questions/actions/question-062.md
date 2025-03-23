---
question: "組織がシークレット `SomeSecret` を定義していますが、ワークフローで `${{ secrets.SomeSecret }}` を使用してそのシークレットを参照すると、期待とは異なる値が提供されます。その理由として考えられるのは何ですか？"
archetype: "questions"
title: "Question 062"
---

> https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions#naming-your-secrets
1. [x] シークレット `SomeSecret` がリポジトリスコープでも宣言されている
1. [ ] シークレット `SomeSecret` がエンタープライズスコープでも宣言されている
> 同じ名前のシークレットが複数のレベルで存在する場合、最も低いレベルのシークレットが優先されます。
1. [ ] `${{ secrets.SomeSecret }}` 式はリポジトリスコープのシークレットにのみ使用されます
1. [ ] 組織スコープのシークレットにアクセスするには GitHub API を使用する必要があります
