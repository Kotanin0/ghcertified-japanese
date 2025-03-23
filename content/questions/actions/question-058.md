---
question: "GitHub Actions を使用してクラウドプロバイダー（AWS、Azure、GCP など）のリソースにアクセスする場合、最も安全で推奨される認証方法は何ですか？"
archetype: "questions"
title: "Question 058"
---

> https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/about-security-hardening-with-openid-connect
1. [x] OIDC を使用する
1. [ ] Vault を使用する
1. [ ] アクセスキーを `secrets` に保存する
> 長期間有効なアクセスキーは、セキュリティ漏洩や [スクリプトインジェクション](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions#understanding-the-risk-of-script-injections) などの攻撃のリスクがあるため推奨されません
1. [ ] アクセスキーを `variables` に保存する
> 機密値は `variables` に保存すべきではありません
