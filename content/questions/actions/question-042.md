---
question: "`artifacts` を使用するのはどのような場合ですか？（2つ選択してください）"
archetype: "questions"
title: "Question 042"
---



> https://docs.github.com/en/actions/using-workflows/storing-workflow-data-as-artifacts#about-workflow-artifacts

- [x] ワークフロー実行が終了した後に表示するために、ジョブで生成されたファイル（テスト結果やビルドログなど）を保存するためにアーティファクトを使用します。
- [x] ビルドジョブで生成されたバイナリを保存し、新しいバージョンのアプリケーションをデプロイするための後続のデプロイジョブで使用するためにアーティファクトを使用します。
- [ ] ジョブやワークフロー実行間であまり変更されないファイル（パッケージ管理システムのビルド依存関係など）を再利用するためにアーティファクトを使用します。
> キャッシュを使用するべきです https://docs.github.com/en/actions/using-workflows/caching-dependencies-to-speed-up-workflows#comparing-artifacts-and-dependency-caching
- [ ] アーティファクトを使用して、リリースノート、メンション、および/またはコントリビューターとともにアプリケーションの新しいバージョンを作成します。
> それはリリースのユースケースです、アーティファクトではありません
