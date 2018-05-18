---
title: "Slack integration"
cover: "https://avatars.io/twitter/slackhq"
aliases: ["/post/78002079055/slack-integration"]
tags: ["slack", "team chat", "integration"]
date: 2014-02-27
draft: false
---

Although HipChat and Flowdock have been around for a while, there's a new kid on the block which is quickly gaining traction. Meet [Slack](https://slack.com)!

## What is Slack
   
In Slack's own words:

> Slack brings all your communication together in one place. It's real-time messaging, archiving and search for modern teams.


<!--more-->

So it makes perfect sense that Doorbell would notify [Slack](https://slack.com) when new feedback arrives!

## Setup

Go to Slack and setup [a new incoming webhook](http://blog.doorbell.io/post/78002079055/slack-integration). You should be looking at a page that looks like this:

![](/img/integrations/chat/slack/webhook.png)

1. Click on the green **Add integration** button at the bottom.
1. Expand the **Instructions for creating Incoming WebHooks** section.
1. Under the **Sending Messages** heading, you should see a URL (like the one in the screenshot below). **Copy that to your clipboard.**

![](/img/integrations/chat/slack/generated-webhook.png)

Next, go to [Doorbell.io](https://doorbell.io), open your application's setup page. Then go to the Notifications section. You can now find Slack under Group Chats. Now all you need to do is:

1. In the **Slack Webhook URL**, paste the URL you copied before.
1. Optionally specify the channel where we will send the notifications.
1. Click **Save**.

![](/img/integrations/chat/slack/form.png)

You should now have a notification in Slack saying that Doorbell has been successfully connected.

That's it! From now on, any new feedback you receive will result in a notification in your channel in Slack!

Go ahead, give it a try! If you haven't got an account yet, go sign up now: [https://doorbell.io](https://doorbell.io)!

P.S. You can keep up to date either via this blog, or you can follow Doorbell on [Twitter](https://twitter.com/doorbell_io).
