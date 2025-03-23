---
question: "GitHub Enterprise Server を使用している組織が、GitHub.com 上にホストされているサードパーティ GitHub Actions を GitHub Enterprise Server インスタンスに自動同期するにはどうすればよいですか？"
archetype: "questions"
title: "Question 064"
---

> https://docs.github.com/en/enterprise-server@3.6/admin/github-actions/managing-access-to-actions-from-githubcom/enabling-automatic-access-to-githubcom-actions-using-github-connect
1. [x] GitHub Connect を使用する
1. [ ] GitHub Enterprise Server はデフォルトですべての GitHub.com Actions にアクセスできます
> GitHub Enterprise Server 上の GitHub Actions は、完全なインターネットアクセスがない環境で動作するように設計されています。デフォルトでは、ワークフローは GitHub.com および GitHub Marketplace のアクションを使用できません。
1. [ ] actions-sync ツールを使用する
> https://docs.github.com/en/enterprise-server@3.6/admin/github-actions/managing-access-to-actions-from-githubcom/manually-syncing-actions-from-githubcom#about-the-actions-sync-tool
1. [ ] GitHub Enterprise Server はオンプレミスの性質上、インターネットアクセスがないため GitHub.com Actions を使用できません
