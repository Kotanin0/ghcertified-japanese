---
question: "再利用可能なワークフロー`build`がZIPファイルのアーティファクトを作成します。このZIPファイルの場所を、`build`ワークフローを呼び出す呼び出し元ワークフローに渡すにはどうすればよいですか？（3つ選択してください。）"
archetype: "questions"
title: "Question 026"
---

> https://docs.github.com/en/actions/using-workflows/reusing-workflows#using-outputs-from-a-reusable-workflow

- [x] `build`ワークフローでワークフローレベルで出力を定義する
- [x] `build`ワークフローでジョブレベルで出力を定義する
- [x] `build`ワークフロー内のステップで出力を`$GITHUB_OUTPUT`に書き込む
- [ ] すべての出力は自動的に呼び出し元ワークフローに渡されます。
