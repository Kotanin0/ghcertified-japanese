---
archetype: "questions"
title: "Question 122"
question: "ワークフロー内で定義されたカスタム変数のスコープは何ですか？（3つ選択してください）"
---


> https://docs.github.com/en/actions/learn-github-actions/variables#defining-environment-variables-for-a-single-workflow
- [x] ワークフローファイルのトップレベルで`env`を使用して、ワークフロー全体
- [x] ワークフロー内のジョブの内容で、`jobs.<job_id>.env`を使用
- [x] ジョブ内の特定のステップで、`jobs.<job_id>.steps[*].env`を使用
- [ ] ワークフロー内のすべてのジョブで、`jobs.env`を使用
- [ ] ワークフローファイルのトップレベルで`custom.env`を使用して、ワークフロー全体
- [ ] リポジトリ内の特定の環境で、`environment.<environment_id>.env`を使用
