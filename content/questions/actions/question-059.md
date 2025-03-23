---
question: "オープンソースで公開されているリポジトリに `pull_request` イベントトリガーを持つワークフローがあります。リポジトリのフォークからトリガーされたワークフロー実行に承認を要求するにはどうすればよいですか？"
archetype: "questions"
title: "Question 059"
---

> https://docs.github.com/en/actions/managing-workflow-runs/approving-workflow-runs-from-public-forks#about-workflow-runs-from-public-forks
1. [x] リポジトリでフォーク実行に対する承認を設定する
1. [ ] リポジトリにデプロイ保護ルールを設定する
> デプロイ保護ルールは環境を保護するために使用されます
1. [ ] リポジトリにブランチ保護ルールを設定する
1. [ ] `pull_request` イベントを使用している場合、フォークに対してワークフローはトリガーされません。それを行うには、`fork_pull_request` イベントトリガーを `require-approval` フラグと共に使用する必要があります。
