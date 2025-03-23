---
question: "GitHub Enterprise Server でサポートバンドルを生成する正しい手順はどれですか？（2 つ選択してください）"
archetype: "questions"
title: "質問 006"
---

> https://docs.github.com/en/enterprise-server@3.15/support/contacting-github-support/providing-data-to-github-support#creating-and-sharing-support-bundles
- [x] GitHub Enterprise Server インスタンスに移動し、`サイト管理者` ページを選択して `管理コンソール` を開きます。上部ナビゲーションバーの `サポート` を選択し、`サポートバンドルをダウンロード` をクリックします。
- [x] SSH を使用して `ghe-support-bundle -o > support-bundle.tgz` CLI コマンドを実行し、サポートバンドルを直接ローカルマシンに生成してダウンロードします。
- [ ] まずエンタープライズアカウントの `設定` にアクセスし、`ライセンス` をクリックします。その後、`GitHub Enterprise ヘルプ` の下で `サポートバンドルをアップロード` を選択します。これによりサポートバンドルが自動的に生成されてダウンロードされます。
- [ ] プロファイルをクリックし、`あなたのエンタープライズ` を選択します。エンタープライズアカウントのサイドバーで `設定` を選択し、`ライセンス` の下で `サポートバンドルを生成` をクリックします。これによりバンドルが作成されてダウンロードされます。
