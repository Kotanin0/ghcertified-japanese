---
question: "**defaults**を使用する有効なユースケースはどれですか？（2つ選択してください。）"
archetype: "questions"
title: "Question 027"
---

> https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#defaults

- [x] ワークフローレベルで`defaults.run`を使用して、ワークフロー全体のデフォルトシェル（例：bash）を設定する
- [x] ジョブレベルで`defaults.run`を使用して、単一ジョブ内のすべてのステップのデフォルト作業ディレクトリを設定する
- [ ] ステップレベルで`defaults.run`を使用して、その単一ステップのデフォルトシェル（例：bash）を設定する
> `defaults.run`はワークフローまたはジョブレベルでのみ設定できます。
- [ ] ワークフローレベルで`defaults.env`を使用して、ワークフロー全体のデフォルト環境変数を設定する
> `defaults.env`というものは存在しません。
- [ ] ジョブレベルで`defaults.env`を使用して、単一ジョブ内のすべてのステップのデフォルト環境変数を設定する
> `defaults.env`というものは存在しません。
