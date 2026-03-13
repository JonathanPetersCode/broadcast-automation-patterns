# Pexels to Slack

Click a button → Get a photo from Pexels → Send to Slack.

## Setup

1. Get a free Pexels API key: https://www.pexels.com/api/
2. Get a Slack webhook: https://api.slack.com/apps → Create App → Incoming Webhooks
3. Open Node-RED, go to Menu → Import
4. Paste the contents of `flow.json`
5. In the HTTP Request node, replace `YOUR_PEXELS_API_KEY` with your key
6. In the Slack node, replace `YOUR_SLACK_WEBHOOK` with your webhook URL
7. Click Deploy
8. Click the Inject button to test

That's it. Your photo data goes to Slack.

## What This Does

- Fetches a photo from Pexels API
- Formats the data (photographer name, link)
- Sends it to Slack

## Use This Pattern For

- Syncing work orders from Xytech
- Pushing asset data to Google Sheets
- Sending production alerts to Slack
- Any API to Slack integration