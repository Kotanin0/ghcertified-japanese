---
question: "再利用可能なワークフローに権限を渡す際に正しい記述はどれですか？"
archetype: "questions"
title: "Question 001"
---

> https://docs.github.com/en/actions/using-workflows/reusing-workflows#access-and-permissions

1. [x] 呼び出し元ワークフローから渡された `GITHUB_TOKEN` の権限は、呼び出されたワークフローによってのみダウングレードできます。
1. [ ] 呼び出し元ワークフローから渡された `GITHUB_TOKEN` の権限は、呼び出されたワークフローによってのみ昇格できます。
1. [ ] 呼び出し元ワークフローから渡された `GITHUB_TOKEN` の権限は、呼び出されたワークフローによってダウングレードおよび昇格の両方が可能です。
1. [ ] 呼び出し元ワークフローから渡された `GITHUB_TOKEN` の権限は、呼び出されたワークフローによってダウングレードも昇格もできません。
