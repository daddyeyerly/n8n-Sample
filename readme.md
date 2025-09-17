# n8n GitHub Automation Workflow

This is a sample n8n workflow to automate GitHub event processing. It pulls GitHub webhooks, filters issues/PRs, auto-labels, assigns tasks, and sends notifications to both Google Sheets and Telegram.

## Nodes Used:
- GitHub Webhook
- Function (to filter issues/PRs)
- Google Sheets (to log tasks)
- Telegram (to send notifications)
