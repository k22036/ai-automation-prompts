# AI Automation Prompts

Prompts for AI-powered scheduled automations.

ChatGPTなどの定期実行タスクで利用するプロンプトを管理するPublicリポジトリです。

## プロンプト

| タスク | 内容 | プロンプト |
| --- | --- | --- |
| セキュリティ速報 | エンジニア向けの重要なセキュリティ情報をWeb検索で調査し、日本語で報告 | [security-briefing.md](prompts/security-briefing.md) |
| 投資・マーケット速報 | 日本株・米国株・マクロ経済・為替・金利の重要情報を毎朝まとめて日本語で報告 | [investment-briefing.md](prompts/investment-briefing.md) |

## 実行設定（ChatGPT）

- **タスク名**：セキュリティ速報
- **実行時刻**：毎日 08:00、11:30、17:30（JST）
- **通知先**：ChatGPTのスケジュールタスク内（プッシュ通知・メールはChatGPTアカウントの設定に従う）
- **外部送信**：Slackなどへの投稿なし

### 投資・マーケット速報

- **タスク名**：投資・マーケット速報
- **実行時刻**：毎日 08:00（JST）
- **通知先**：ChatGPTのスケジュールタスク内（プッシュ通知・メールはChatGPTアカウントの設定に従う）
- **外部送信**：Slackなどへの投稿なし

## 公開に関する注意

Publicリポジトリです。APIキー、アクセストークン、パスワード、個人情報、社内限定情報をコミットしないでください。
