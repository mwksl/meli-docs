---
title: 'Slack hooks'
excerpt: 'Configure Slack with Meli'
---

# Slack

## Get your Mattermost hook URL:

Slack webhook URL. To get this URL:

1. [Create](https://api.slack.com/apps?new_app=1) a custom Slack App. Fill in the form as follows:
    - *App Name*: `Pmbot`
    - *Development Slack Workspace*: Workspace where you want Pmbot to be integrated to
2. Click "Create App". You are redirected to your app's page.
3. Under menu section *Features*, select *Incoming Webhooks*, then toggle on *Activate Incoming Webhooks*. A new section named *Webhook URLs for Your Workspace* appears.
4. Under section *Webhook URLs for Your Workspace*, click *Add New Webhook To Workspace*, then select the channel to which you want messages to be sent, for example `#pmbot`.
5. Once added, copy the webhook URL and configure this action with it

Or if you prefer watching:

![Get Slack hook url](../../images/get-slack-webhook-url.mp4)

## Creating a webhook

1. Go to one of your sites
1. Go to the "Hooks" tab
1. Click "Add"
1. Select type **Slack**
1. Fill in the URL
