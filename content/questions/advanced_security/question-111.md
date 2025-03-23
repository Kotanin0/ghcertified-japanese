---
archetype: "questions"
title: "質問 111"
question: "GitHub Actions を有効にする必要があるのはどれですか？"
---

> https://docs.github.com/en/code-security/dependabot/dependabot-version-updates/about-dependabot-version-updates#about-dependabot-version-updates
1. [x] Dependency Review（依存関係レビュー）
1. [ ] Dependabot Security Updates（Dependabot セキュリティ更新）
1. [ ] Dependabot Version Updates（Dependabot バージョン更新）
1. [ ] これらすべて
> GitHub Actions は Dependabot バージョン更新やセキュリティ更新の実行には必要ありません。ただし、Dependabot によって開かれたプルリクエストは、アクションを実行するワークフローをトリガーする可能性があります。
1. [ ] これらのいずれでもない
> Dependency Review は `actions/dependency-review-action` GitHub Action を使用します。
