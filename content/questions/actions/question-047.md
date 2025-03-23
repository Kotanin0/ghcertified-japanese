---
question: "`deploy` というジョブで、`build` というジョブで作成されたバイナリ（アプリケーションを含む）にアクセスしたい場合、どうすればよいですか？"
archetype: "questions"
title: "Question 047"
---

> https://docs.github.com/en/actions/using-workflows/storing-workflow-data-as-artifacts#comparing-artifacts-and-dependency-caching

1. [x] `build` でバイナリをアーティファクトとしてアップロードし、`deploy` でそれをダウンロードする
1. [ ] `deploy` でバイナリをアーティファクトとしてアップロードし、`build` でそれをダウンロードする
1. [ ] `build` でバイナリをキャッシュし、`deploy` でキャッシュからファイルを読み取る
1. [ ] `deploy` でバイナリをキャッシュし、`build` でキャッシュからファイルを読み取る
