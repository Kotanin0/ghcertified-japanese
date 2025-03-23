---
question: "パブリックリポジトリでセルフホストランナーを有効にすることの潜在的な悪用ベクトルにはどのようなものがありますか？（4つ選択してください）"
archetype: "questions"
title: "Question 084"
---

> https://docs.github.com/en/actions/hosting-your-own-runners/managing-self-hosted-runners/about-self-hosted-runners#self-hosted-runner-security
- [x] マシン上で悪意のあるプログラムが実行される
- [x] ランナーのサンドボックス環境からの脱出
- [x] ネットワーク環境の露出
- [x] 危険なデータの永続化
- [ ] ジョブ実行後の自動環境クリーンアップがデータ損失を引き起こす可能性
- [ ] セキュリティ対策による計算効率の低下
- [ ] GitHubホストサービスとの統合の制限
