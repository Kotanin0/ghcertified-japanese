---
question: "プルリクエスト分析ワークフローは複数のコード分析ツールを使用し、完全に完了するまでに約20分かかります。このワークフローは`pull_request`イベントでトリガーされ、`branches`フィルターが`master`に設定されています。そのため、開発者が数分以内に複数のコミットをプッシュすると、複数のワークフローが並行して実行されます。すべての以前のワークフロー実行を停止し、最新の変更のみを実行するにはどうすればよいですか？"
archetype: "questions"
title: "Question 029"
---

> https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#example-using-concurrency-to-cancel-any-in-progress-job-or-run

1. [x] `cancel-in-progress` を使用した並行処理を使用する
```yaml
  concurrency:
    group: ${{ github.workflow }}-${{ github.ref }}
    cancel-in-progress: true
```
1. [ ] 並行処理を使用する
```yaml
  concurrency:
    group: ${{ github.ref }}
```
> これはそのGitHubリファレンスで実行をキューに入れますが、以前の実行を停止しません。

1. [ ] アクティビティタイプフィルターを使用する
```yaml
  on:
    pull_request:
      branches:
        - master
      types: [latest]
```
> `pull_request`イベントには`latest`というアクティビティタイプはありません。

1. [ ] `pull_request`イベントに対して`cancel-in-progress`フラグを使用する
```yaml
  on:
    pull_request:
      branches:
        - master
      cancel-in-progress: true
```
