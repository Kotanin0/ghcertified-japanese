---
question: "組織管理者がWebhookの変更に関連するイベントを監査ログで検索するにはどうすればよいですか？"
archetype: "questions"
title: "Question 065"
---

> https://docs.github.com/en/organizations/keeping-your-organization-secure/managing-security-settings-for-your-organization/reviewing-the-audit-log-for-your-organization
1. [x] 検索クエリで`operation`修飾子を使用し、`operation:modify`のように既存のリソース（Webhookなど）が変更されたイベントを見つける。
1. [ ] 監査ログの検索バーに「Webhookの変更」と直接入力する。
1. [ ] イベントタイプを指定せずに日付範囲のみで監査ログをフィルタリングする。
1. [ ] 音声コマンドを使用してWebhook変更イベントの検索を口頭でリクエストする。
