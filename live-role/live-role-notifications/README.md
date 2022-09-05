# Live Role Notifications

## For beginners

Live Role Notifications allows you to set up automatic announcements whenever someone in your server goes live. These notifications also respect the filter role, if one is set.

Be aware that Live Role Notifications are not a full-fledged replacement for streamer notifications. At times, they can be buggy due to inconsistencies on Discord's end.

#### **What Live Role Notifications SHOULD be used for**

* An easy self-promotion system for streamers in your server
* Automatic notifications for your subscribers, moderators, and/or VIPs

#### **What Live Role Notifications SHOULD NOT be used for**

* Stream announcements for one person
  * We highly recommend you set up a [streamer notification](../../notifications/intro.md) instead. There's a chance that Streamcord may skip an announcement or announce multiple times with Live Role Notifications.
* Pinging @everyone, @here, or a role
  * As mentioned above, Streamcord may be inconsistent with notifications, which could lead to frustration from server members that are getting pinged.

{% hint style="info" %}
Live Role Notifications only announces for members who have their Twitch account connected to Discord. You can connect your Twitch under Discord Settings -> Connections.
{% endhint %}

### Set up Live Role Notifications

{% content-ref url="set-up.md" %}
[set-up.md](set-up.md)
{% endcontent-ref %}

## For advanced users

### Using variables with Live Role Notifications

Live Role Notifications uses a different set of variables than Streamer Notifications. You can find the list of variables here:

{% content-ref url="using-variables.md" %}
[using-variables.md](using-variables.md)
{% endcontent-ref %}

### Live Role Notifications vs. Legacy & Spyglass

This table compares features between Live Role notifications and streamer notifications ([Legacy ](../../notifications/legacy/)and [Spyglass](https://docs.streamcord.io/notifications/spyglass)).

|                    | Live Role Notifications | Legacy      | Spyglass  |
| ------------------ | ----------------------- | ----------- | --------- |
| Delivery time      | Near-instant\*          | 3–5 minutes | 3 minutes |
| Streamer limit     | Unlimited\*\*           | 25          | 25        |
| Custom message     | Yes                     | Yes         | Yes       |
| Notification embed | —                       | Yes         | Yes       |
| Supports failover  | —                       | Yes         | —         |
| Stream end cleanup | —                       | —           | Yes       |

\*Live Role Notifications relies completely on the user having a purple "streaming" status; Streamcord does not directly contact Twitch for information on whether or not the user is actually live.

\*\*Instead of adding notifications for each individual streamer, Live Role Notifications automatically works for every streamer who is eligible to receive the live role.
