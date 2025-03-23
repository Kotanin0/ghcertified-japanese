---
question: "`caching` を使用するのはどのような場合ですか？"
archetype: "questions"
title: "Question 041"
---



> https://docs.github.com/en/actions/using-workflows/caching-dependencies-to-speed-up-workflows#comparing-artifacts-and-dependency-caching

1. [x] ジョブやワークフロー実行間であまり変更されないファイル（パッケージ管理システムのビルド依存関係など）を再利用したい場合。
1. [ ] ジョブやワークフロー実行間で頻繁に変更されるファイル（パッケージ管理システムのビルド依存関係など）を再利用したい場合。
1. [ ] ワークフロー実行が終了した後に表示するために、ジョブで生成されたファイル（ビルド済みバイナリやビルドログなど）を保存したい場合。
> アーティファクトを使用するべきです https://docs.github.com/en/actions/using-workflows/storing-workflow-data-as-artifacts
1. [ ] ビルドジョブで生成されたバイナリを保存し、新しいバージョンのアプリケーションをデプロイするための後続のデプロイジョブで使用したい場合。
> アーティファクトを使用するべきです https://docs.github.com/en/actions/using-workflows/storing-workflow-data-as-artifacts
