---
description: >-
  This guide will show you how to set up automatic announcements for when a
  specific streamer goes live.
---

# Add a Legacy Notification

{% hint style="danger" %}
**Legacy Notifications are deprecated.** Instead, you should use [Spylgass Notifications](../spyglass/add-spyglass.md). If you want to read more about the EOL process for Legacy, visit [this page](../legacy-end-of-life.md).
{% endhint %}

## Set up your notification channel

**1.** Create a channel for stream announcements if you haven't already.

**2.** Edit your channel's settings, and go to the "Permissions" tab.

**3.** From the "Roles/Members" selection, add Streamcord.

![Add Streamcord to the channel's permission overrides.](<../../.gitbook/assets/image (10).png>)

**4.** Allow Streamcord to have the following permissions in the channel:

* View Channel
* Send Messages
* Embed Links
* Attach Files
* Use External Emoji
* Mention @everyone, @here, and All Roles

![Give Streamcord the needed permissions.](../../.gitbook/assets/image.png)

**5.** Click "Save changes".

## Add the notification from the dashboard

**1.** Go to [https://dash.streamcord.io/](https://dash.streamcord.io/) in your browser.

**2.** Log in with Discord.

**3.** Choose your server from the list.

**4.** Under the "Stream notifications" section, click "Add notification".

![Click the "Add notification" link.](<../../.gitbook/assets/image (29).png>)

**5.** Fill in the streamer's name, choose your announcement channel, and type a custom message.\
In this example, we're adding a notification for _summit1g_ in the _#live-streams_ channel.

![Enter your streamer, channel, and custom message.](<../../.gitbook/assets/image (46).png>)

**6.** Click the "Add notification" button.

{% hint style="success" %}
**Congrats, you just set up your first stream notification!** You can also experiment with different settings and change up the custom message.
{% endhint %}

## Make the most out of your notifications

Did you know that Streamcord can do more than just what we covered in this article?

[Spyglass ](../spyglass/)supports extra features like stream end messages.

You can also spice up your notification message with [variables](../variables.md).

## Resolving common issues

Having trouble getting your notification to work? Follow these steps to troubleshoot and solve some common issues:

{% content-ref url="../issues.md" %}
[issues.md](../issues.md)
{% endcontent-ref %}

You can also join our [Discord server](https://link.streamcord.io/support) to get extra help.
