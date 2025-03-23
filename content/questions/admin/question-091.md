---
question: "GitHub Actionsで秘密情報を管理するためにサードパーティのボールトをどのように使用できますか？"
archetype: "questions"
title: "Question 091"
---

> https://docs.github.com/en/actions/security-guides/encrypted-secrets#storing-large-secrets
1. [x] サードパーティのボールトに秘密情報を保存し、ワークフロー内で復号ステップを使用してアクセスします。復号キーはGitHub Actionsの秘密情報として保存します。
1. [ ] サードパーティのボールトとの直接統合はGitHub Actions内でネイティブにサポートされており、追加の設定は不要です。
1. [ ] サードパーティのボールトは、そのベンダーのAPIまたはCLIを使用してワークフローファイル内にAPIキーを埋め込むことでアクセスします。
1. [ ] GitHub Actionsは秘密情報管理のためにサードパーティのボールトをサポートしていません。すべての秘密情報はGitHub内に保存する必要があります。
