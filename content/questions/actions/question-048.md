---
question: "`job2` というジョブが `job1` で作成されたアーティファクトを使用しています。そのため、`job2` がアーティファクトを探し始める前に `job1` が終了することを確認する必要があります。この依存関係をどのように作成しますか？"
archetype: "questions"
title: "Question 048"
---

> https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#jobsjob_idneeds

1. [x] `job2` で `needs` キーワードを使用してこの依存関係を作成する
1. [ ] `actions/download-artifact` を使用して `job1` からアーティファクトをダウンロードする際に、この依存関係が暗黙的に作成される
1. [ ] ワークフローの `.yaml` 定義で `job1` の後に `job2` を定義することで、この依存関係を作成する
1. [ ] `job2` で `concurrency` キーワードを使用してこの依存関係を作成する
