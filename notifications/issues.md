# Common Issues

## Streamcord announces my stream after I've been live for several minutes

| Type                                                                        | Delay           |
| --------------------------------------------------------------------------- | --------------- |
| [Legacy Notifications](legacy/) (Streamcord)                                | 3 to 10 minutes |
| [Legacy Notifications](legacy/) (Streamcord Pro)                            | 1 to 3 minutes  |
| [Spyglass Notifications](https://docs.streamcord.io/notifications/spyglass) | 2 to 5 minutes  |
| [Live Role Notifications](../live-role/live-role-notifications/)            | <1 minute       |

Due to the way how Twitch API works and the number of notifications that Streamcord serves, the bot takes some time to send out messages. Timing may vary based on the type of notification used.

## Streamcord doesn't send announcements/notifications

Ensure that Streamcord has correct permissions in order to send notifications.

Give Streamcord the following permissions for your notifications channel:

* View Channel
* Send Messages
* Embed Links
* Attach Files
* Use External Emoji
* Mention @everyone, @here, and All Roles

![List of permissions to enable. Click to expand](<../.gitbook/assets/image (13) (1).png>)

## My notifications are disabled

Notifications are automatically disabled when Streamcord encounters an error with Discord permissions when trying to send an announcement message. Ensure that Streamcord has all of the necessary permissions in your notification channel, and then click the "Re-enable all notifications" button.

**Streamcord needs these permissions:**

* View Channel
* Send Messages
* Embed Links
* Attach Files
* Use External Emoji
* Mention @everyone, @here, and All Roles

**Then, re-enable the notification on the dashboard:**\
****Re-enable your notifications by clicking on the "Re-enable notifications" button under your server's notification page on the [dashboard](https://dash.streamcord.io/).

**NOTE:** The error _may_ not disappear immediately after clicking the "Re-enable notifications" button. In such a case, the error should go away once the user starts the next stream and Streamcord successfully sends the notification.

![](<../.gitbook/assets/image (27).png>)

## My dashboard displays an error code

If your dashboard server notifications page displays an error with a code number, please follow the steps on this page:

{% content-ref url="dashboard-error-codes.md" %}
[dashboard-error-codes.md](dashboard-error-codes.md)
{% endcontent-ref %}
