---
question: "ワークフローが `feature-a` ブランチで実行される場合、デフォルトの `main` ブランチで作成された `caches` を復元できますか？"
archetype: "questions"
title: "Question 043"
---


> https://docs.github.com/en/actions/using-workflows/caching-dependencies-to-speed-up-workflows#restrictions-for-accessing-a-cache
1. [x] はい、すべてのブランチはデフォルトブランチで作成されたキャッシュを復元できます
1. [ ] はい、すべてのキャッシュは同じリポジトリ内の任意のブランチのワークフローでアクセスできます
1. [ ] いいえ、キャッシュは同じブランチからのみ復元できます
1. [ ] はい、ただし `feature-a` ブランチでファイルが変更されていない場合のみです
