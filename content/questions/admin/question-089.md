---
question: "GitHubで組織用のセルフホストランナーグループを作成するには、どの手順が必要ですか？"
archetype: "questions"
title: "Question 089"
---

> https://docs.github.com/en/actions/hosting-your-own-runners/managing-access-to-self-hosted-runners-using-groups
1. [x] 組織設定に移動し、[Actions] を選択、[Runner groups] をクリック、新しいグループを作成し、リポジトリのアクセスポリシーを割り当てる。
1. [ ] `.github` リポジトリ内で `.gitconfig` ファイルを変更し、ランナーグループと関連するアクセスポリシーを指定する。
1. [ ] GitHubサポートに連絡してランナーグループの作成を依頼し、アクセス設定用のリポジトリリストを提供する。
1. [ ] GitHub Actionsワークフローを使用して、リポジトリアクティビティと使用パターンに基づいてランナーグループを自動生成する。
