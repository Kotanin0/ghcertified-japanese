---
question: "48 KB を超えるシークレットを保存するための推奨されるアプローチは何ですか？"
archetype: "questions"
title: "Question 099"
---

> https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions#limits-for-secrets
1. [ ] セキュリティを確保するために大きなシークレットの保存を完全に避けます
1. [ ] 48 KB を超えるシークレットは保存できません
1. [x] シークレットを暗号化してリポジトリに保存し、復号化パスフレーズをシークレットとして保持します
1. [ ] 制限を回避するために大きなシークレットを直接リポジトリシークレットとして保存します
