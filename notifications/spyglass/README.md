# Spyglass Notifications

Spyglass is the newest type of stream notification that can be created through Streamcord. It is intended to replace Webhooks v2 (now removed) and [Legacy](../legacy/), and offers several benefits over previous types of notifications.

## What makes Spyglass different?

* **It's fast.** Spyglass will notify within 1 to 3 minutes of a stream starting or ending, making it much faster than legacy notifications.
* **It's reliable.** Spyglass relies on [EventSub](https://dev.twitch.tv/docs/eventsub), Twitch's newest technology for providing automation like Streamcord with up-to-date information.
* **It's consistent.** Spyglass will notify exactly once for every stream, meaning that you'll never miss a stream notification.
* **It supports stream end events.** Spyglass can be configured to (a) send a new message, (b) edit the original notification, or (c) delete the original notification, when a user stops their stream.&#x20;
* **It has all the same features as Webhooks v2 and Legacy.** You can easily migrate all your existing Webhooks v2 and Legacy notifications with our easy [migration tool](transfer-notifications-to-spyglass.md).
* **It allows us to add new features more easily.** Spyglass is built to be our long-term solution to providing notifications for hundreds of thousands of channels; it's here to stay.

## How can I use Spyglass?

Spyglass is currently available to everyone using Streamcord.

Follow this guide for instructions on how to add a new Spyglass notification, or transfer your existing notifications to Spyglass:

{% content-ref url="add-spyglass.md" %}
[add-spyglass.md](add-spyglass.md)
{% endcontent-ref %}

{% content-ref url="transfer-notifications-to-spyglass.md" %}
[transfer-notifications-to-spyglass.md](transfer-notifications-to-spyglass.md)
{% endcontent-ref %}

