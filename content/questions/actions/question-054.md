---
question: "カスタム GitHub Actions を作成する際、すべてのアクション `メタデータ` を定義する必要があるファイルはどれですか？"
archetype: "questions"
title: "Question 054"
---

メタデータ例: 名前、説明、出力、または必要な入力
> https://docs.github.com/en/actions/creating-actions/metadata-syntax-for-github-actions
1. [x] アクションリポジトリ内の `action.yml` または `action.yaml` ファイル
1. [ ] リポジトリの `README` ファイル
> それを行うことは推奨されますが、アクションが動作するための要件ではありません
1. [ ] 共有のために公開する際に GitHub Marketplace UI で編集する
1. [ ] アクションリポジトリ内の `action.yml` または `action.yaml` ファイル。ただし、アクションが公開されて一般に使用されることを意図していない場合は必須ではありません
> すべてのアクションにはメタデータファイルが必要です。
