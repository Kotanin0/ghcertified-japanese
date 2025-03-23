---
question: "コミットまたはプルリクエストを作成する際に、次のワークフローの実行をスキップするにはどうすればよいですか？"
archetype: "questions"
title: "Question 118"
---

```yaml
name: Build
on: [push, pull_request]

jobs:
  build:
    runs-on: ubuntu-latest
    name: Extract artifact version
...
```

>https://docs.github.com/en/actions/managing-workflow-runs/skipping-workflow-runs

1. [x] コミットメッセージまたはプルリクエストのタイトルに次のいずれかのキーワードを含める
```yaml
[skip ci]
[ci skip]
[no ci]
[skip actions]
[actions skip]
```

1. [ ] コミットメッセージに`SKIP_WORKFLOW`を指定する
1. [ ] 上記のワークフローは、プッシュまたはプルリクエストのすべてのイベントで常に実行される
